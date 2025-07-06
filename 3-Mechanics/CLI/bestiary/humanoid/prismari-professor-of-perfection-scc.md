---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/scc
- monster/cr/7
- monster/size/small-or-medium
- monster/type/humanoid/sorcerer
aliases: ["Prismari Professor of Perfection"]
NoteIcon: monster
BestiaryType: humanoid (sorcerer)
SourceType: Bestiary
BookSource: Strixhaven: A Curriculum of Chaos p. 206
---
# [Prismari Professor of Perfection](2-Mechanics\CLI\bestiary\humanoid/prismari-professor-of-perfection-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 206*  

Professors of perfection combine elemental magic with precise, forceful physical motion. Their sweeping gestures and dance-like steps gather the power of crashing waves, conjure the protection of unyielding stone, and shape great structures of ice. Binding and channeling these natural elements allow the professors to mold their environment to their needs, both for breathtaking performances and to control the fabric of a battlefield against their foes.

These teachers stress attention to fine details, drilling their students on the most minuscule points. The perfect foundation ultimately leads to a flawless work of art, and the professors of perfection produce sculptural and architectural marvels.

## Prismari Scholars

The scholars of Prismari College believe that art is the truest form of spellcraft. They use magic to make splendid art, and they employ artistry to make their magic spectacular.

```statblock
"name": "Prismari Professor of Perfection (SCC)"
"size": "Small or Medium"
"type": "humanoid"
"subtype": "sorcerer"
"alignment": "Any alignment"
"ac": !!int "13"
"hp": !!int "97"
"hit_dice": "15d8 + 30"
"stats":
- !!int "14"
- !!int "16"
- !!int "15"
- !!int "15"
- !!int "13"
- !!int "19"
"speed": "30 ft."
"saves":
  "Charisma": !!int "7"
  "Dexterity": !!int "6"
  "Wisdom": !!int "4"
  "Intelligence": !!int "5"
"skillsaves":
  "Athletics": !!int "5"
  "Perception": !!int "4"
  "Performance": !!int "10"
  "Acrobatics": !!int "6"
  "Arcana": !!int "5"
"damage_resistances": "cold"
"senses": "passive Perception 14"
"languages": "Common plus any four languages"
"cr": "7"
"traits":
- "desc": "The professor casts one of the following spells, requiring no material\
    \ components and using Charisma as the spellcasting ability (spell save DC 15):\n\
    \nAt will: [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md)\n\n\
    1/day: [wall of ice](/2-Mechanics/CLI/spells/wall-of-ice.md)\n\n2/day each:\
    \ [control water](/2-Mechanics/CLI/spells/control-water.md), [create or destroy\
    \ water](/2-Mechanics/CLI/spells/create-or-destroy-water.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md),\
    \ [stone shape](/2-Mechanics/CLI/spells/stone-shape.md)"
  "name": "Spellcasting"
- "desc": "The professor can walk across water and other liquids as if they were solid\
    \ ground."
  "name": "Water Walking"
"actions":
- "desc": "The professor makes three Tidal Strike attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 60 ft.,\
    \ one target. Hit: 13 (2d8 + 4) cold damage."
  "name": "Tidal Strike"
"bonus_actions":
- "desc": "The professor is momentarily surrounded by a swirling wave of water and\
    \ moves up to 30 feet. When the professor moves within 5 feet of any other creature\
    \ during this bonus action, that creature must succeed on a DC 15 Strength saving\
    \ throw, or the creature is knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)\
    \ and it can't take reactions until the start of its next turn. A creature can\
    \ suffer this effect only once during a turn."
  "name": "Rushing Wave"
"source":
- "SCC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SCC/Prismari%20Professor%20of%20Perfection.webp"
```
^statblock

```encounter-table
name: Prismari Professor of Perfection
creatures:
 - 1: Prismari Professor of Perfection
```