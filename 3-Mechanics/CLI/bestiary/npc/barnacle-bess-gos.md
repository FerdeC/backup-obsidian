---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/1-8
- monster/size/medium
- monster/type/beast
aliases: ["Barnacle Bess"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 220
---
# [Barnacle Bess](2-Mechanics\CLI\bestiary\npc/barnacle-bess-gos.md)
*Source: Ghosts of Saltmarsh p. 220*  

```statblock
"name": "Barnacle Bess (GoS)"
"size": "Medium"
"type": "beast"
"alignment": "Lawful Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "13"
"hit_dice": "3d8"
"stats":
- !!int "13"
- !!int "15"
- !!int "11"
- !!int "10"
- !!int "9"
- !!int "3"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Stealth": !!int "4"
"senses": "blindsight 30 ft., passive Perception 9"
"languages": "Common"
"cr": "1/8"
"traits":
- "desc": "Bess can breathe air and water."
  "name": "Amphibious"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) bludgeoning damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 11). Bess has two claws, each of which can grapple only one target."
  "name": "Claw"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Barnacle%20Bess.webp"
```
^statblock

```encounter-table
name: Barnacle Bess
creatures:
 - 1: Barnacle Bess
```