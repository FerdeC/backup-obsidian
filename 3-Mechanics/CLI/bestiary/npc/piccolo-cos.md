---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cos
- monster/cr/0
- monster/size/small
- monster/type/beast
aliases: ["Piccolo"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Curse of Strahd p. 118
---
# [Piccolo](2-Mechanics\CLI\bestiary\npc/piccolo-cos.md)
*Source: Curse of Strahd p. 118*  

```statblock
"name": "Piccolo (CoS)"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "3"
"hit_dice": "1d6"
"stats":
- !!int "8"
- !!int "14"
- !!int "11"
- !!int "4"
- !!int "12"
- !!int "6"
"speed": "30 ft., climb 30 ft."
"senses": "passive Perception 11"
"languages": ""
"cr": "0"
"traits":
- "desc": "Piccolo has advantage on an attack roll against a creature if at least\
    \ one of Piccolo's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Weapon Attack: +1 to hit, reach 5 ft., one target. Hit: 1 (1d4\
    \ - 1) piercing damage."
  "name": "Bite"
"source":
- "CoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CoS/Piccolo.webp"
```
^statblock

```encounter-table
name: Piccolo
creatures:
 - 1: Piccolo
```