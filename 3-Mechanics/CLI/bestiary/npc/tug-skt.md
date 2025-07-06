---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/5
- monster/size/huge
- monster/type/giant
aliases: ["Tug"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Storm King's Thunder p. 209
---
# [Tug](2-Mechanics\CLI\bestiary\npc/tug-skt.md)
*Source: Storm King's Thunder p. 209*  

```statblock
"name": "Tug (SKT)"
"size": "Huge"
"type": "giant"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "[scale mail](/2-Mechanics/CLI/items/scale-mail.md)"
"hp": !!int "105"
"hit_dice": "10d12 + 40"
"stats":
- !!int "21"
- !!int "8"
- !!int "19"
- !!int "5"
- !!int "9"
- !!int "6"
"speed": "40 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "Giant"
"cr": "5"
"actions":
- "desc": "The giant makes two greatclub attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 18\
    \ (3d8 + 5) bludgeoning damage."
  "name": "Greatclub"
- "desc": "Ranged Weapon Attack: +8 to hit, range 60/240 ft., one target. Hit:\
    \ 21 (3d10 + 5) bludgeoning damage."
  "name": "Rock"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Tug.webp"
```
^statblock

```encounter-table
name: Tug
creatures:
 - 1: Tug
```