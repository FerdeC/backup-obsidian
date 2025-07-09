# Tabla de Experiencia D&D 5e (4 Columnas)
<div id="xp-table"></div>  | Nivel | XP Requerida | Nivel | XP Requerida |
| :---- | :----------- | :---- | :----------- |
| 1     | 0            | 11    | 85,000       |
| 2     | 300          | 12    | 100,000      |
| 3     | 900          | 13    | 120,000      |
| 4     | 2,700        | 14    | 140,000      |
| 5     | 6,500        | 15    | 165,000      |
| 6     | 14,000       | 16    | 195,000      |
| 7     | 23,000       | 17    | 225,000      |
| 8     | 34,000       | 18    | 265,000      |
| 9     | 48,000       | 19    | 305,000      |
| 10    | 64,000       | 20    | 355,000      |

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
    // MODIFICADO: Extrae los datos de la tabla de XP por su ID en esta misma nota
    // Busca todas las tablas en la nota actual y filtra por el ID 'xp-table'
    const allTables = dv.current().file.tables;
    const xpData = allTables.find(table => table.id === "xp-table");

    let xpNextLevel = "N/A (Máximo nivel)";
    let nivelDestino = "N/A";

    if (xpData && xpData.rows) { // Asegúrate de que 'rows' exista en la tabla encontrada
        // Aquí necesitamos aplanar los datos de la tabla porque tiene 4 columnas
        // Queremos buscar en las columnas de nivel y XP de ambas "mitades"
        let found = false;
        for (const row of xpData.rows) {
            // Revisa la primera mitad de la tabla
            if (row[0] === (nivelActual + 1)) { // row[0] es la primera columna 'Nivel'
                xpNextLevel = Number(row[1]); // row[1] es la primera columna 'XP Requerida'
                nivelDestino = row[0];
                found = true;
                break;
            }
            // Revisa la segunda mitad de la tabla
            if (row[2] === (nivelActual + 1)) { // row[2] es la segunda columna 'Nivel'
                xpNextLevel = Number(row[3]); // row[3] es la segunda columna 'XP Requerida'
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
        dv.el("p", "⚠️ Error: No se pudo encontrar la tabla de XP con el ID 'xp-table' en esta nota, o está vacía.");
        canProceed = false; // Si no hay tabla, no podemos calcular
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