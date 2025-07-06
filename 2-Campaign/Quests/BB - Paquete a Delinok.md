---
questObtained: 
questStatus: Not Started
questGiver: Tablón de anuncios
questLocationObtained: Thalmyr (Varkass)
questSessionObtained: 
questNotes: Transportar una pequeña caja sin daños ni preguntas.
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

_“Se necesita persona confiable para entregar una caja cerrada a un comerciante llamado Felian en Delinok. No abrir. No preguntar.”_  
**– [[Lehter Marnic]], Encargado del Puerto 7.**

**Razón del envío:**  
Lehter no sabe lo que contiene exactamente. Solo dice que lo recogió de una nave que atracó “de noche y sin bandera clara” hace unos días, y que **debe ser llevado al contacto de confianza en la biblioteca privada de Delinok**, sin abrirlo.

Al entregar la caja los atacan para intentar eliminarlos.

```encounter-table
name: Individual
creatures:
 - 8: Thug
 - 1: Commoner
```



### Quest Objective

- Transportar una pequeña caja; No abrir. No preguntar.

### Rewards

- 10 piezas de oro al regreso con prueba de entrega.

### Loot available

- [[CX-087-MYR Rituales de estabilización mágica]]
