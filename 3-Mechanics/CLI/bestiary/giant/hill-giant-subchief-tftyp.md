---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/7
- monster/size/huge
- monster/type/giant
aliases: ["Hill Giant Subchief"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 170
---
# [Hill Giant Subchief](2-Mechanics\CLI\bestiary\giant/hill-giant-subchief-tftyp.md)
*Source: Tales from the Yawning Portal p. 170*  

```statblock
"name": "Hill Giant Subchief (TftYP)"
"size": "Huge"
"type": "giant"
"alignment": "Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "11d12 + 55"
"stats":
- !!int "23"
- !!int "15"
- !!int "20"
- !!int "10"
- !!int "12"
- !!int "9"
"speed": "40 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "4"
  "Constitution": !!int "8"
"skillsaves":
  "Athletics": !!int "12"
  "Perception": !!int "4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Giant"
"cr": "7"
"actions":
- "desc": "The giant makes two greatclub attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 15 ft., one target. Hit: 19\
    \ (3d8 + 6) bludgeoning damage."
  "name": "Greatclub"
- "desc": "Ranged Weapon Attack: +9 to hit, range 60/240 ft., one target. Hit:\
    \ 28 (4d10 + 6) bludgeoning damage. If the target is a creature, it must succeed\
    \ on a DC 17 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Rock"
"reactions":
- "desc": "If a rock or similar object is hurled at the giant, the giant can, with\
    \ a successful DC 10 Dexterity saving throw, catch the missile and take no bludgeoning\
    \ damage from it."
  "name": "Rock Catching"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Hill%20Giant%20Subchief.webp"
```
^statblock

```encounter-table
name: Hill Giant Subchief
creatures:
 - 1: Hill Giant Subchief
```