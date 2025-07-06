---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/1-4
- monster/size/medium
- monster/type/humanoid/lizardfolk
aliases: ["Lizardfolk Commoner"]
NoteIcon: monster
BestiaryType: humanoid (lizardfolk)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 241
---
# [Lizardfolk Commoner](2-Mechanics\CLI\bestiary\humanoid/lizardfolk-commoner-gos.md)
*Source: Ghosts of Saltmarsh p. 241*  

These lizardfolk, found wandering the halls in Danger at Dunwater, are just as fierce as their armed kin, and can equip themselves with weapons and shields if such are available.

```statblock
"name": "Lizardfolk Commoner (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "lizardfolk"
"alignment": "Neutral"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"stats":
- !!int "15"
- !!int "10"
- !!int "12"
- !!int "7"
- !!int "12"
- !!int "7"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Stealth": !!int "2"
  "Perception": !!int "3"
  "Survival": !!int "3"
"senses": "passive Perception 13"
"languages": "Draconic"
"cr": "1/4"
"traits":
- "desc": "The lizardfolk can hold its breath for 15 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Bite"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Lizardfolk%20Commoner.webp"
```
^statblock

```encounter-table
name: Lizardfolk Commoner
creatures:
 - 1: Lizardfolk Commoner
```