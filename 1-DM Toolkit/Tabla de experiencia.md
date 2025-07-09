# Tabla de Experiencia D&D 5e (4 Columnas)

| Nivel | XP Requerida | Nivel | XP Requerida |
| :---- | :----------- | :---- | :----------- |
| 1     | 0            | 11    | 85000        |
| 2     | 300          | 12    | 100000       |
| 3     | 900          | 13    | 120000       |
| 4     | 2700         | 14    | 140000       |
| 5     | 6500         | 15    | 165000       |
| 6     | 14000        | 16    | 195000       |
| 7     | 23000        | 17    | 225000       |
| 8     | 34000        | 18    | 265000       |
| 9     | 48000        | 19    | 305000       |
| 10    | 64000        | 20    | 355000       |

---

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
    const allListsInNote = dv.current().file.lists; // Dataview pone las tablas aquí también.

    // ENFOQUE SIMPLIFICADO: Intentar tomar la primera tabla que Dataview encuentre.
    if (allListsInNote && allListsInNote.length > 0) {
        for (const list of allListsInNote) {
            // Un poco de depuración adicional, que puedes descomentar si quieres ver lo que Dataview ve
            // dv.el("p", `DEBUG: Lista encontrada - Tipo: ${list.type}, Headers: ${list.headers ? list.headers.join('|') : 'N/A'}, Rows: ${list.rows ? list.rows.length : 'N/A'}`);

            if (list.type === 'table' && list.rows && list.rows.length > 0) {
                // Hemos encontrado una tabla. Asumimos que es la tabla de XP.
                xpData = list;
                break; // Salimos del bucle una vez que la encontramos.
            }
        }
    }

    let xpNextLevel = "N/A (Máximo nivel)";
    let nivelDestino = "N/A";

    // Si encontramos una tabla y tiene filas, procedemos.
    if (xpData && xpData.rows && xpData.rows.length > 0) {
        let found = false;
        for (const row of xpData.rows) {
            // Asegúrate de convertir a número antes de comparar
            const rowNivel1 = Number(row[0]);
            const rowNivel2 = Number(row[2]);

            // Revisa la primera mitad de la tabla
            if (rowNivel1 === (nivelActual + 1)) {
                xpNextLevel = Number(row[1]);
                nivelDestino = row[0];
                found = true;
                break;
            }
            // Revisa la segunda mitad de la tabla
            if (rowNivel2 === (nivelActual + 1)) {
                xpNextLevel = Number(row[3]);
                nivelDestino = row[2];
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
        // Este mensaje de error ahora debería ser más preciso si realmente no hay tablas.
        dv.el("p", "⚠️ Error: No se pudo encontrar una tabla válida en esta nota, o está vacía.");
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