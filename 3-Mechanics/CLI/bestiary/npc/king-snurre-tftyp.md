---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/11
- monster/size/huge
- monster/type/giant
aliases: ["King Snurre"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 193
---
# [King Snurre](2-Mechanics\CLI\bestiary\npc/king-snurre-tftyp.md)
*Source: Tales from the Yawning Portal p. 193*  

```statblock
"name": "King Snurre (TftYP)"
"size": "Huge"
"type": "giant"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[plate armor](/2-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "187"
"hit_dice": "15d12 + 90"
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
"damage_resistances": "cold"
"damage_immunities": "fire"
"senses": "passive Perception 16"
"languages": "Common, Giant"
"cr": "11"
"actions":
- "desc": "Snurre makes two greatsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 28\
    \ (6d6 + 7) slashing damage plus 7 (2d6) fire damage."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +11 to hit, range 60/240 ft., one target. Hit:\
    \ 29 (4d10 + 7) bludgeoning damage."
  "name": "Rock"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/King%20Snurre.webp"
```
^statblock

```encounter-table
name: King Snurre
creatures:
 - 1: King Snurre
```