# Tabla de Experiencia D&D 5e

| Nivel | XP Requerida |
| :---- | :----------- |
| 1     | 0            |
| 2     | 300          |
| 3     | 900          |
| 4     | 2700         |
| 5     | 6500         |
| 6     | 14000        |
| 7     | 23000        |
| 8     | 34000        |
| 9     | 48000        |
| 10    | 64000        |
| 11    | 85000        |
| 12    | 100000       |
| 13    | 120000       |
| 14    | 140000       |
| 15    | 165000       |
| 16    | 195000       |
| 17    | 225000       |
| 18    | 265000       |
| 19    | 305000       |
| 20    | 355000       |

---
```dataviewjs
// --- BLOQUE DE DEPURACIÓN TEMPORAL ---
dv.el("h3", "Resultados de Depuración de Dataview (Temporal)");
dv.el("p", `Ruta del archivo actual: ${dv.current().file.path}`);

const allLists = dv.current().file.lists;

if (allLists && allLists.length > 0) {
    dv.el("p", `Número de "listas" detectadas: ${allLists.length}`);
    let tableFound = false;
    allLists.forEach((item, index) => {
        dv.el("h4", `Elemento ${index + 1}:`);
        dv.el("p", `Tipo: ${item.type}`);
        if (item.type === 'table') {
            tableFound = true;
            dv.el("p", `  **¡Es una tabla!**`);
            dv.el("p", `  Encabezados: ${item.headers ? item.headers.join(' | ') : 'N/A'}`);
            dv.el("p", `  Número de filas: ${item.rows ? item.rows.length : 'N/A'}`);
            if (item.rows && item.rows.length > 0) {
                dv.el("p", `  Primera fila: ${item.rows[0].join(' | ')}`);
            }
        } else {
            dv.el("p", `  No es una tabla.`);
            if (item.text) {
                dv.el("p", `  Primeras palabras: "${item.text.substring(0, 50)}..."`);
            }
        }
    });
    if (!tableFound) {
        dv.el("p", "⚠️ **ADVERTENCIA: Ningún elemento fue detectado como 'tabla' por Dataview.**");
    }
} else {
    dv.el("p", "Dataview no detectó ninguna 'lista' (incluyendo tablas) en este archivo.");
}
// --- FIN DEL BLOQUE DE DEPURACIÓN TEMPORAL ---

```



## Progreso de XP Actual

```dataviewjs
// Ruta a la nota donde se encuentran xpActual y nivel
const sideScreenNotePath = "1-DM Toolkit/DnD5e-SideScreen.md"; // ¡Verifica que esta ruta sea exacta!

// Carga la página de la pantalla lateral
const sideScreenPage = dv.page(sideScreenNotePath);

// Inicializa las variables
let xpActual = 0;
let nivelActual = 0;
let canProceed = true; // Bandera para controlar la ejecución

// --- Validación y obtención de datos ---
if (!sideScreenPage) {
    dv.el("p", `⚠️ Error: No se pudo cargar la nota "${sideScreenNotePath}".`);
    canProceed = false;
} else {
    if (sideScreenPage.xpActual === undefined) {
        dv.el("p", `⚠️ Error: Propiedad 'xpActual' no encontrada en "${sideScreenNotePath}".`);
        canProceed = false;
    } else {
        xpActual = Number(sideScreenPage.xpActual); // Asegura que sea un número
    }

    if (sideScreenPage.nivel === undefined) {
        dv.el("p", `⚠️ Error: Propiedad 'nivel' no encontrada en "${sideScreenNotePath}".`);
        canProceed = false;
    } else {
        nivelActual = Number(sideScreenPage.nivel); // Asegura que sea un número
    }
}

// Solo procede si la bandera 'canProceed' es verdadera
if (canProceed) {
    let xpData = null;
    const allListsInNote = dv.current().file.lists;

    // Buscar la tabla de XP con dos columnas
    if (allListsInNote && allListsInNote.length > 0) {
        for (const list of allListsInNote) {
            if (list.type === 'table' && list.headers && list.rows && list.rows.length > 0) {
                const cleanHeaders = list.headers.map(h => h.trim());
                // Buscamos los encabezados esperados para la tabla de 2 columnas
                const expectedHeaders = ['Nivel', 'XP Requerida'];

                if (cleanHeaders.length === expectedHeaders.length && 
                    cleanHeaders.every((val, index) => val === expectedHeaders[index])) {
                    
                    // Verificación adicional de la primera fila
                    const firstLevelCol = Number(list.rows[0][0]);
                    const firstXpCol = Number(list.rows[0][1]);

                    if (firstLevelCol === 1 && firstXpCol === 0) {
                        xpData = list;
                        break; // ¡Tabla encontrada!
                    }
                }
            }
        }
    }

    let xpNextLevel = "N/A (Máximo nivel)";
    let nivelDestino = "N/A";

    if (xpData && xpData.rows && xpData.rows.length > 0) {
        let found = false;
        // La tabla ahora solo tiene 2 columnas, buscamos Nivel+1 en la primera columna
        for (const row of xpData.rows) {
            const rowNivel = Number(row[0]); // Nivel está en la primera columna

            if (rowNivel === (nivelActual + 1)) {
                xpNextLevel = Number(row[1]); // XP Requerida está en la segunda columna
                nivelDestino = row[0];
                found = true;
                break;
            }
        }

        if (!found && nivelActual < 20) {
             dv.el("p", `⚠️ Error: Nivel ${nivelActual + 1} no encontrado en la tabla de XP.`);
             canProceed = false;
        } else if (nivelActual >= 20) {
            xpNextLevel = "Ya eres nivel máximo!";
            nivelDestino = "20";
        }

    } else {
        dv.el("p", "⚠️ Error: No se pudo encontrar una tabla válida de 2 columnas en esta nota, o está vacía.");
        canProceed = false;
    }
}

// --- Renderizado de resultados (solo si todo fue bien) ---
if (canProceed) {
    let xpFaltante = "No aplica";
    if (typeof xpNextLevel === 'number' && typeof xpActual === 'number') {
        xpFaltante = xpNextLevel - xpActual;
    } else if (typeof xpNextLevel === 'string' && xpNextLevel.includes("Máximo")) {
        xpFaltante = "Ya eres nivel máximo!";
    } else {
        xpFaltante = "Error al calcular (verificar datos o formato de XP)";
    }

    dv.el("h3", "Resumen de Progreso");
    dv.el("p", `**Nivel Actual:** ${nivelActual}`);
    dv.el("p", `**XP Actual:** ${xpActual}`);
    dv.el("p", `**Siguiente Nivel:** ${nivelDestino}`);
    dv.el("p", `**XP para el Siguiente Nivel:** ${xpNextLevel}`);
    dv.el("p", `**XP Faltante:** ${xpFaltante}`);
}