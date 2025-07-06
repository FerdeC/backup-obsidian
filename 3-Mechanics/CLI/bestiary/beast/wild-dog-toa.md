---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/0
- monster/size/small
- monster/type/beast
aliases: ["Wild Dog"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 96
---
# [Wild Dog](2-Mechanics\CLI\bestiary\beast/wild-dog-toa.md)
*Source: Tomb of Annihilation p. 96*  

```statblock
"name": "Wild Dog (ToA)"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "3"
"hit_dice": "1d6"
"stats":
- !!int "8"
- !!int "15"
- !!int "11"
- !!int "3"
- !!int "12"
- !!int "6"
"speed": "40 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "0"
"traits":
- "desc": "The dog has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or smell."
  "name": "Keen Hearing and Smell"
- "desc": "The dog has advantage on an attack roll against a creature if at least\
    \ one of the dog's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Weapon Attack: +1 to hit, reach 5 ft., one target. Hit: 1 (1d4\
    \ - 1) piercing damage."
  "name": "Bite"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Wild%20Dog.webp"
```
^statblock

```encounter-table
name: Wild Dog
creatures:
 - 1: Wild Dog
```