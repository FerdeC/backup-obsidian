# Tabla de Experiencia D&D 5e (4 Columnas)

| Nivel | XP Requerida | Nivel | XP Requerida |
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

// Asegúrate de que la página se cargó correctamente y tiene las propiedades
let xpActual = 0;
let nivelActual = 0;

if (sideScreenPage) {
    if (sideScreenPage.xpActual !== undefined) {
        xpActual = Number(sideScreenPage.xpActual); // Asegura que sea un número
    } else {
        dv.el("p", `⚠️ Error: Propiedad 'xpActual' no encontrada en "${sideScreenNotePath}".`);
        return; // Detiene la ejecución si falta xpActual
    }
    if (sideScreenPage.nivel !== undefined) {
        nivelActual = Number(sideScreenPage.nivel); // Asegura que sea un número
    } else {
        dv.el("p", `⚠️ Error: Propiedad 'nivel' no encontrada en "${sideScreenNotePath}".`);
        return; // Detiene la ejecución si falta nivel
    }
} else {
    dv.el("p", `⚠️ Error: No se pudo cargar la nota "${sideScreenNotePath}".`);
    return; // Detiene la ejecución si la nota no se encuentra
}

// Extrae los datos de la tabla de XP en esta misma nota
// `dv.current().file.lists[0]` obtiene la primera tabla de la nota actual.
const xpData = dv.current().file.lists[0];

let xpNextLevel = "N/A (Máximo nivel)";
let nivelDestino = "N/A";

if (xpData) {
    const nextLevelEntry = xpData.find(row => row.Nivel === (nivelActual + 1));

    if (nextLevelEntry) {
        xpNextLevel = Number(nextLevelEntry['XP Requerida']); // Asegura que sea un número
        nivelDestino = nextLevelEntry.Nivel;
    } else if (nivelActual >= 20) {
        xpNextLevel = "Ya eres nivel máximo!";
        nivelDestino = "20";
    }
} else {
    dv.el("p", "⚠️ Error: No se pudo encontrar la tabla de XP en esta nota.");
    return;
}

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