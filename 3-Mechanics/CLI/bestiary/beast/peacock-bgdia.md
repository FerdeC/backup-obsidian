---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/0
- monster/size/medium
- monster/type/beast
aliases: ["Peacock"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 195
---
# [Peacock](2-Mechanics\CLI\bestiary\beast/peacock-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 195*  

```statblock
"name": "Peacock (BGDIA)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "5"
"hit_dice": "1d8 + 1"
"stats":
- !!int "7"
- !!int "10"
- !!int "13"
- !!int "2"
- !!int "12"
- !!int "4"
"speed": "10 ft., fly 50 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "0"
"traits":
- "desc": "The peacock has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on sight or smell."
  "name": "Keen Sight and Smell"
- "desc": "The peacock has advantage on an attack roll against a creature if at least\
    \ one of the peacock's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d4)\
    \ piercing damage."
  "name": "Beak"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Peacock.webp"
```
^statblock

```encounter-table
name: Peacock
creatures:
 - 1: Peacock
```