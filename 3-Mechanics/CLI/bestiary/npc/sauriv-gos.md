---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Sauriv"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 79
---
# [Sauriv](2-Mechanics\CLI\bestiary\npc/sauriv-gos.md)
*Source: Ghosts of Saltmarsh p. 79*  

```statblock
"name": "Sauriv (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Neutral"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "11"
- !!int "12"
- !!int "11"
- !!int "12"
- !!int "18"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "7"
  "Insight": !!int "6"
  "Persuasion": !!int "7"
"senses": "passive Perception 14"
"languages": "Common, Draconic"
"cr": "1/8"
"traits":
- "desc": "Sauriv"
  "name": "Hold Breath"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d8\
    \ + 1) piercing damage."
  "name": "Rapier"
"reactions":
- "desc": "Sauriv adds 2 to its AC against one melee attack that would hit it. To\
    \ do so, Sauriv must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Sauriv.webp"
```
^statblock

```encounter-table
name: Sauriv
creatures:
 - 1: Sauriv
```