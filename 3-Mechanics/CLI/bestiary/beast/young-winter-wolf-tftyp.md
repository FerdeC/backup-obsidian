---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/1
- monster/size/large
- monster/type/beast
aliases: ["Young Winter Wolf"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 181
---
# [Young Winter Wolf](2-Mechanics\CLI\bestiary\beast/young-winter-wolf-tftyp.md)
*Source: Tales from the Yawning Portal p. 181*  

```statblock
"name": "Young Winter Wolf (TftYP)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "37"
"hit_dice": "5d10 + 10"
"stats":
- !!int "17"
- !!int "15"
- !!int "15"
- !!int "3"
- !!int "12"
- !!int "7"
"speed": "50 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "1"
"traits":
- "desc": "The wolf has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or smell."
  "name": "Keen Hearing and Smell"
- "desc": "The wolf has advantage on an attack roll against a creature if at least\
    \ one of the wolf's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) piercing damage. If the target is a creature, it must succeed on\
    \ a DC 13 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Bite"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Young%20Winter%20Wolf.webp"
```
^statblock

```encounter-table
name: Young Winter Wolf
creatures:
 - 1: Young Winter Wolf
```