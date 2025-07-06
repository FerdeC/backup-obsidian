---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/5
- monster/size/large
- monster/type/monstrosity
aliases: ["Sea Lion"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 242, Ghosts of Saltmarsh p. 252
---
# [Sea Lion](2-Mechanics\CLI\bestiary\monstrosity/sea-lion-tftyp.md)
*Source: Tales from the Yawning Portal p. 242, Ghosts of Saltmarsh p. 252*  

These large marine mammals live along coastal regions and around islands at sea

```statblock
"name": "Sea Lion (TftYP)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "90"
"hit_dice": "12d10 + 24"
"stats":
- !!int "17"
- !!int "15"
- !!int "15"
- !!int "3"
- !!int "12"
- !!int "8"
"speed": "10 ft., swim 40 ft."
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "4"
"senses": "passive Perception 14"
"languages": ""
"cr": "5"
"traits":
- "desc": "The sea lion can breathe air and water."
  "name": "Amphibious"
- "desc": "The sea lion has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "The sea lion has advantage on an attack roll against a creature if at least\
    \ one of the sea lion's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
- "desc": "With a 10-foot swimming start, the sea lion can long jump out of or across\
    \ the water up to 25 feet."
  "name": "Swimming Leap"
"actions":
- "desc": "The sea lion makes three attacks: one bite attack and two claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d8 + 3) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d8 + 3) piercing damage."
  "name": "Claw"
"source":
- "TftYP"
- "LR"
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Sea%20Lion.webp"
```
^statblock

```encounter-table
name: Sea Lion
creatures:
 - 1: Sea Lion
```