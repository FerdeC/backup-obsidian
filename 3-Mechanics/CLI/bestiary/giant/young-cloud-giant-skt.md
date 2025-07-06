---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/5
- monster/size/huge
- monster/type/giant
aliases: ["Young Cloud Giant"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Storm King's Thunder p. 112
---
# [Young Cloud Giant](2-Mechanics\CLI\bestiary\giant/young-cloud-giant-skt.md)
*Source: Storm King's Thunder p. 112*  

```statblock
"name": "Young Cloud Giant (SKT)"
"size": "Huge"
"type": "giant"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "105"
"hit_dice": "10d12 + 40"
"stats":
- !!int "21"
- !!int "8"
- !!int "19"
- !!int "10"
- !!int "12"
- !!int "12"
"speed": "40 ft."
"skillsaves":
  "Insight": !!int "4"
  "Perception": !!int "4"
"senses": "passive Perception 14"
"languages": "Common, Giant"
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
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Young%20Cloud%20Giant.webp"
```
^statblock

```encounter-table
name: Young Cloud Giant
creatures:
 - 1: Young Cloud Giant
```