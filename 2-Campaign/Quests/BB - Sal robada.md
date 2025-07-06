---
questObtained: 
questStatus: Not Started
questGiver: Tablón de anuncios
questLocationObtained: 
questSessionObtained: 
questNotes: Recuperar sacos de sal robados de un grupo de bandidos de baja monta.
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

_“Una caravana reporta que salerosos bandidos han saqueado un cargamento de sal refinada. Han sido vistos cerca del viejo faro. ¿Quién limpia el camino?”_  
**– [[Sigrun Monedazul]], gremio de mercaderes.**

Al llegar cerca del viejo faro, son embozcados.

```encounter-table
name: Individual
creatures:
 - 15: Bandit
 - 1: Bandit Captain
```

### Quest Objective

- Recuperar sacos de sal robados de un grupo de bandidos de baja monta.

### Rewards

- 15 piezas de oro + opción a escoltar futuras caravanas.

### Loot available

- N/A