---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/5
- monster/size/huge
- monster/type/giant
aliases: ["Fire Giant Servant"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 171
---
# [Fire Giant Servant](2-Mechanics\CLI\bestiary\giant/fire-giant-servant-tftyp.md)
*Source: Tales from the Yawning Portal p. 171*  

```statblock
"name": "Fire Giant Servant (TftYP)"
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
- !!int "5"
- !!int "9"
- !!int "6"
"speed": "40 ft."
"skillsaves":
  "Perception": !!int "2"
"damage_immunities": "fire"
"senses": "passive Perception 12"
"languages": "Giant"
"cr": "5"
"actions":
- "desc": "The giant makes two longsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 18\
    \ (3d8 + 5) slashing damage, or 21 (3d10 + 5) slashing damage if used with\
    \ both hands."
  "name": "Longsword"
- "desc": "Ranged Weapon Attack: +8 to hit, range 60/240 ft., one target. Hit:\
    \ 21 (3d10 + 5) bludgeoning damage."
  "name": "Rock"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Fire%20Giant%20Servant.webp"
```
^statblock

```encounter-table
name: Fire Giant Servant
creatures:
 - 1: Fire Giant Servant
```