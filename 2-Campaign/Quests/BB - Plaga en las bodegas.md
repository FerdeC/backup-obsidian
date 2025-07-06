---
questObtained: 
questStatus: Not Started
questGiver: Tablón de anuncios
questLocationObtained: 
questSessionObtained: 
questNotes: Eliminar una infestación de ratas (algunas podrían ser de tamaño anormal).
questLootAvail: Nota con lore
questLookEarned: 
NoteIcon: quest
obsidianUIMode: preview
tags:
  - quest
---

# `=this.file.name`

> [!infobox]+
> # `=this.file.name`
> ## Quest Details
> Type |  Stat |
> ---|---|
> Date Obtained | `INPUT[datePicker:questObtained]` |
> Status | `INPUT[inlineSelect(option(Not Started), option(In Progress), option(Complete)):questStatus]` |
> Quest Giver | `INPUT[suggester(optionQuery(#npc)):questGiver]` |
> Quest Location | `INPUT[suggester(optionQuery(#Category/Settlement)):questLocationObtained]` |
> Session Obtained | `INPUT[suggester(optionQuery(#journal)):questSessionObtained]` |
> Available Loot | `INPUT[suggester(optionQuery(#item)):questLootAvail]` |
> Acquired Loot | `INPUT[suggester(optionQuery(#item)):questLookEarned]` |

_“Los roedores han tomado la bodega de la posada ‘El Ancla Volcada’. Se comen el grano y muerden los barriles. No puedo abrir sin ayuda. ¡Traigan trampas, espadas o gatos feroces!”_  
**– [[Rulgar Hondo]], posadero.**

### Quest Objective

- Eliminar una infestación de ratas (algunas podrían ser de tamaño anormal).

### Rewards

- 8 piezas de oro + una comida caliente diaria para cada uno.

### Loot available

- [[NOTE - Ratas inusualmente grandes]]