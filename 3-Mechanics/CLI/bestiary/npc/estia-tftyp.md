---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/9
- monster/size/huge
- monster/type/giant
aliases: ["Estia"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 189
---
# [Estia](2-Mechanics\CLI\bestiary\npc/estia-tftyp.md)
*Source: Tales from the Yawning Portal p. 189*  

```statblock
"name": "Estia (TftYP)"
"size": "Huge"
"type": "giant"
"alignment": "Neutral Good or Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "200"
"hit_dice": "16d12 + 96"
"stats":
- !!int "27"
- !!int "10"
- !!int "22"
- !!int "12"
- !!int "16"
- !!int "16"
"speed": "40 ft."
"saves":
  "Charisma": !!int "7"
  "Wisdom": !!int "7"
  "Constitution": !!int "10"
"skillsaves":
  "Insight": !!int "7"
  "Perception": !!int "7"
"damage_immunities": "cold"
"senses": "passive Perception 17"
"languages": "Common, Giant"
"cr": "9"
"actions":
- "desc": "Estia makes two morningstar attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 23\
    \ (3d8 + 10) piercing damage."
  "name": "Morningstar +2"
- "desc": "Ranged Weapon Attack: +12 to hit, range 60/240 ft., one target. Hit:\
    \ 30 (4d10 + 8) bludgeoning damage."
  "name": "Rock"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Estia.webp"
```
^statblock

```encounter-table
name: Estia
creatures:
 - 1: Estia
```