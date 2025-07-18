---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wbtw
- monster/cr/2
- monster/size/large
- monster/type/construct
aliases: ["Glass Pegasus"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: The Wild Beyond the Witchlight p. 181
---
# [Glass Pegasus](2-Mechanics\CLI\bestiary\construct/glass-pegasus-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 181*  

```statblock
"name": "Glass Pegasus (WBtW)"
"size": "Large"
"type": "construct"
"alignment": "Chaotic Good"
"ac": !!int "15"
"hp": !!int "59"
"hit_dice": "7d10 + 21"
"stats":
- !!int "18"
- !!int "15"
- !!int "16"
- !!int "10"
- !!int "15"
- !!int "13"
"speed": "60 ft., fly 90 ft."
"saves":
  "Charisma": !!int "3"
  "Dexterity": !!int "4"
  "Wisdom": !!int "4"
"skillsaves":
  "Perception": !!int "6"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified)"
"senses": "passive Perception 16"
"languages": "Celestial, Common, Elvish and Sylvan but can't speak"
"cr": "2"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) bludgeoning damage."
  "name": "Hooves"
"source":
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WBtW/Glass%20Pegasus.webp"
```
^statblock

```encounter-table
name: Glass Pegasus
creatures:
 - 1: Glass Pegasus
```