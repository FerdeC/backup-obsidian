---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/3
- monster/size/huge
- monster/type/beast
aliases: ["Amphisbaena"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 84
---
# [Amphisbaena](2-Mechanics\CLI\bestiary\beast/amphisbaena-tftyp.md)
*Source: Tales from the Yawning Portal p. 84*  

```statblock
"name": "Amphisbaena (TftYP)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "60"
"hit_dice": "8d12 + 8"
"stats":
- !!int "19"
- !!int "14"
- !!int "12"
- !!int "1"
- !!int "10"
- !!int "3"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "blindsight 10 ft., passive Perception 12"
"languages": ""
"cr": "3"
"actions":
- "desc": "The amphisbaena makes two attacks, only one of which can be a constrict\
    \ attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one creature. Hit:\
    \ 11 (2d6 + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. Hit: 13\
    \ (2d8 + 4) bludgeoning damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 16). Until this grapple ends, the creature is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and the snake can't constrict another target."
  "name": "Constrict"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Amphisbaena.webp"
```
^statblock

```encounter-table
name: Amphisbaena
creatures:
 - 1: Amphisbaena
```