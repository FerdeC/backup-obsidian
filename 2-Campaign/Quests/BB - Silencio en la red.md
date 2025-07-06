---
questObtained: 
questStatus: Not Started
questGiver: Tablón de anuncios
questLocationObtained: Thalmyr (Varkass)
questSessionObtained: 
questNotes: Investigar la zona del muelle bajo.
questLootAvail: 
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

_“Los pescadores no atrapan nada desde hace tres días. Sospechan que una criatura se ha instalado cerca del muelle bajo. Necesitamos voluntarios con valor y anzuelo.”_  
**– Consejo de Barqueros de Thalmyr.**

Al llegar al lugar, son atacados por por sorpresa.
```encounter-table
name: Individual
creatures:
 - 3: Grick
```

### Quest Objective

- Investigar la zona del muelle bajo. 

### Rewards

- 12 piezas de oro + 1 acceso gratuito al ferry.

### Loot available

- N/A