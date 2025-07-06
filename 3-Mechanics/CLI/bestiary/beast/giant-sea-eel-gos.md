---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/1-2
- monster/size/large
- monster/type/beast
aliases: ["Giant Sea Eel"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 237
---
# [Giant Sea Eel](2-Mechanics\CLI\bestiary\beast/giant-sea-eel-gos.md)
*Source: Ghosts of Saltmarsh p. 237*  

Snaking predators lurking in the dark waters of the ocean, these kelp-colored beasts serve as guards and mounts for the locathah (including those found in Danger at Dunwater).

```statblock
"name": "Giant Sea Eel (GoS)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "19"
"hit_dice": "3d10 + 3"
"stats":
- !!int "11"
- !!int "14"
- !!int "12"
- !!int "7"
- !!int "10"
- !!int "7"
"speed": "0 ft., swim 40 ft."
"saves":
  "Dexterity": !!int "4"
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "2"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "The eel can breathe only underwater."
  "name": "Water Breathing"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d10 + 2) piercing damage."
  "name": "Bite"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Giant%20Sea%20Eel.webp"
```
^statblock

```encounter-table
name: Giant Sea Eel
creatures:
 - 1: Giant Sea Eel
```