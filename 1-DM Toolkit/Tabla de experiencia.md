```dataviewjs
const sideScreenNotePath = "1-DM Toolkit/DnD5e-SideScreen.md";

// Obtener los datos del personaje
const sideScreenPage = dv.page(sideScreenNotePath);

if (!sideScreenPage) {
    dv.paragraph(`⚠️ No se encontró la nota: "${sideScreenNotePath}"`);
} else {
    const xpActual = Number(sideScreenPage.xpActual ?? 0);
    const nivelActual = Number(sideScreenPage.nivel ?? 1);

    // Tabla de experiencia
    const xpTable = [
        { nivel: 1, xp: 0 },
        { nivel: 2, xp: 300 },
        { nivel: 3, xp: 900 },
        { nivel: 4, xp: 2700 },
        { nivel: 5, xp: 6500 },
        { nivel: 6, xp: 14000 },
        { nivel: 7, xp: 23000 },
        { nivel: 8, xp: 34000 },
        { nivel: 9, xp: 48000 },
        { nivel: 10, xp: 64000 },
        { nivel: 11, xp: 85000 },
        { nivel: 12, xp: 100000 },
        { nivel: 13, xp: 120000 },
        { nivel: 14, xp: 140000 },
        { nivel: 15, xp: 165000 },
        { nivel: 16, xp: 195000 },
        { nivel: 17, xp: 225000 },
        { nivel: 18, xp: 265000 },
        { nivel: 19, xp: 305000 },
        { nivel: 20, xp: 355000 }
    ];

    let xpNextLevel, xpFaltante, nivelDestino;

    if (nivelActual >= 20) {
        xpNextLevel = "Ya eres nivel máximo";
        xpFaltante = "0";
        nivelDestino = "20";
    } else {
        const nextEntry = xpTable.find(row => row.nivel === nivelActual + 1);
        xpNextLevel = nextEntry?.xp ?? "Desconocido";
        xpFaltante = nextEntry ? nextEntry.xp - xpActual : "Desconocido";
        nivelDestino = nextEntry?.nivel ?? "Desconocido";
    }

    // Render
    dv.header(3, "Resumen de Progreso");
    dv.paragraph(`**Nivel Actual:** ${nivelActual}`);
    dv.paragraph(`**XP Actual:** ${xpActual}`);
    dv.paragraph(`**Siguiente Nivel:** ${nivelDestino}`);
    dv.paragraph(`**XP para el Siguiente Nivel:** ${xpNextLevel}`);
    dv.paragraph(`**XP Faltante:** ${xpFaltante}`);
}
```