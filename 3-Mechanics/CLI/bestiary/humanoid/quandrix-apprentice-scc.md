---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/scc
- monster/cr/2
- monster/size/small-or-medium
- monster/type/humanoid/wizard
aliases: ["Quandrix Apprentice"]
NoteIcon: monster
BestiaryType: humanoid (wizard)
SourceType: Bestiary
BookSource: Strixhaven: A Curriculum of Chaos p. 208
---
# [Quandrix Apprentice](2-Mechanics\CLI\bestiary\humanoid/quandrix-apprentice-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 208*  

The students of Quandrix College—first as apprentices and then as pledgemages—immerse themselves in the magic of geometry and metaphysics. Their ultimate goal isn't mastery, however. Rather, in their projects they explore and expand knowledge without expecting concrete answers. Whether students are extrapolating mathematical patterns in nature or engaging in speculative dives into topological formulas that bend reality, their studies blur the line between abstract numerical theory and natural reality.

## Quandrix Scholars

The scholars of Quandrix College focus on the mathematical principles that govern reality. Through these formulas, they can manipulate properties of matter and space, as well as abstract and conceptual space such as the mind, probability, and the flow of magic itself.

```statblock
"name": "Quandrix Apprentice (SCC)"
"size": "Small or Medium"
"type": "humanoid"
"subtype": "wizard"
"alignment": "Any alignment"
"ac": !!int "11"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"stats":
- !!int "10"
- !!int "12"
- !!int "13"
- !!int "15"
- !!int "14"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
  "Intelligence": !!int "4"
"skillsaves":
  "Nature": !!int "4"
  "Investigation": !!int "6"
  "Arcana": !!int "6"
"senses": "passive Perception 12"
"languages": "Common plus any two languages"
"cr": "2"
"traits":
- "desc": "The apprentice casts one of the following spells, requiring no material\
    \ components and using Intelligence as the spellcasting ability (spell save DC\
    \ 12):\n\nAt will: [guidance](/2-Mechanics/CLI/spells/guidance.md), [mage\
    \ hand](/2-Mechanics/CLI/spells/mage-hand.md)\n\n1/day each: [enlarge/reduce](/2-Mechanics/CLI/spells/enlarge-reduce.md),\
    \ [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The apprentice makes two Exponential Lash attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +4 to hit, reach 5 ft. or range 60 ft.,\
    \ one target. Hit: 5 (1d6 + 2) force damage, and the apprentice can cause\
    \ one creature it can see within 30 feet of the target to take 9 (2d6 + 2) force\
    \ damage."
  "name": "Exponential Lash"
"source":
- "SCC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SCC/Quandrix%20Apprentice.webp"
```
^statblock

```encounter-table
name: Quandrix Apprentice
creatures:
 - 1: Quandrix Apprentice
```