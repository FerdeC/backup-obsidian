---
questObtained: 
questStatus: Not Started
questGiver: Tablón de anuncios
questLocationObtained: 
questSessionObtained: 
questNotes: 
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

_“Las plantas de la anciana [[Armelia Serenval]] han comenzado a marchitarse con rapidez. Dice que algo oscuro ronda por las noches.”_  
**– Firmado con tinta temblorosa.**

Al llegar al lugar indicado, el patio de la anciana Armelia, son recibidos por un aire gelido:

```encounter-table
name: Armelia Serenval
creatures:
 - 1: Wight
```

### Quest Objective

- Investigar y neutralizar lo que está envenenando las plantas. Puede involucrar alimañas mágicas o un espíritu menor.

### Rewards

- 5 piezas de oro + 3 poción de curación casera.

### Loot available

- [[NOTE - Fragmento del diario de Armelia]]