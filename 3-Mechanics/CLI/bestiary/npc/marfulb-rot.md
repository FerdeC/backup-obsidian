---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/rot
- monster/cr/1
- monster/size/medium
- monster/type/monstrosity
aliases: ["Marfulb"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: The Rise of Tiamat p. 35
---
# [Marfulb](2-Mechanics\CLI\bestiary\npc/marfulb-rot.md)
*Source: The Rise of Tiamat p. 35*  

```statblock
"name": "Marfulb (RoT)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Neutral"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"stats":
- !!int "13"
- !!int "10"
- !!int "14"
- !!int "13"
- !!int "10"
- !!int "6"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Perception": !!int "2"
"damage_immunities": "cold"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Ice Toad"
"cr": "1"
"traits":
- "desc": "The toad can breathe air or water."
  "name": "Amphibious"
- "desc": "Any creature that starts its turn within 5 feet of the toad takes 3 (1d6)\
    \ cold damage."
  "name": "Cold Aura"
- "desc": "The toad's long jump is up to 20 feet and its high jump is up to 10 feet,\
    \ with or without a running start."
  "name": "Standing Leap"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d8)\
    \ cold damage. If the target is a Medium or smaller creature it is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 11). Until this grapple ends, the toad can't bite another target."
  "name": "Bite"
"source":
- "RoT"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/RoT/Marfulb.webp"
```
^statblock

```encounter-table
name: Marfulb
creatures:
 - 1: Marfulb
```