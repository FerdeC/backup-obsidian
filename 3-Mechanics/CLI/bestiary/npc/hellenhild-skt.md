---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/8
- monster/size/huge
- monster/type/giant
aliases: ["Hellenhild"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Storm King's Thunder p. 207
---
# [Hellenhild](2-Mechanics\CLI\bestiary\npc/hellenhild-skt.md)
*Source: Storm King's Thunder p. 207*  

```statblock
"name": "Hellenhild (SKT)"
"size": "Huge"
"type": "giant"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "patchwork armor"
"hp": !!int "138"
"hit_dice": "12d12 + 60"
"stats":
- !!int "23"
- !!int "9"
- !!int "21"
- !!int "9"
- !!int "10"
- !!int "12"
"speed": "40 ft."
"saves":
  "Charisma": !!int "4"
  "Wisdom": !!int "3"
  "Constitution": !!int "8"
"skillsaves":
  "Athletics": !!int "9"
  "Perception": !!int "3"
"damage_immunities": "cold"
"senses": "passive Perception 13"
"languages": "Giant"
"cr": "8"
"actions":
- "desc": "The giant makes two greataxe attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 25\
    \ (3d12 + 6) slashing damage."
  "name": "Greataxe"
- "desc": "Ranged Weapon Attack: +9 to hit, range 60/240 ft., one target. Hit:\
    \ 28 (4d10 + 6) bludgeoning damage."
  "name": "Rock"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Hellenhild.webp"
```
^statblock

```encounter-table
name: Hellenhild
creatures:
 - 1: Hellenhild
```