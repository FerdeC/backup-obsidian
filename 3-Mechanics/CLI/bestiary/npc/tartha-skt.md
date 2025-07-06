---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/9
- monster/size/huge
- monster/type/giant
aliases: ["Tartha"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Storm King's Thunder p. 207
---
# [Tartha](2-Mechanics\CLI\bestiary\npc/tartha-skt.md)
*Source: Storm King's Thunder p. 207*  

```statblock
"name": "Tartha (SKT)"
"size": "Huge"
"type": "giant"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[plate armor](/2-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "162"
"hit_dice": "13d12 + 78"
"stats":
- !!int "25"
- !!int "9"
- !!int "23"
- !!int "10"
- !!int "14"
- !!int "13"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Dexterity": !!int "3"
  "Constitution": !!int "10"
"skillsaves":
  "Athletics": !!int "11"
  "Perception": !!int "6"
"damage_immunities": "fire"
"senses": "passive Perception 16"
"languages": "Giant"
"cr": "9"
"actions":
- "desc": "Tartha makes two greatsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 28\
    \ (6d6 + 7) slashing damage."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +11 to hit, range 60/240 ft., one target. Hit:\
    \ 29 (4d10 + 7) bludgeoning damage."
  "name": "Rock"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Tartha.webp"
```
^statblock

```encounter-table
name: Tartha
creatures:
 - 1: Tartha
```