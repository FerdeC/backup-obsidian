---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/1
- monster/size/medium
- monster/type/construct
aliases: ["Play-by-Play Generator"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 205
---
# [Play-by-Play Generator](2-Mechanics\CLI\bestiary\npc/play-by-play-generator-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 205*  

```statblock
"name": "Play-by-Play Generator (WDMM)"
"size": "Medium"
"type": "construct"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"stats":
- !!int "12"
- !!int "14"
- !!int "12"
- !!int "10"
- !!int "10"
- !!int "11"
"speed": "30 ft., fly 30 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "truesight 120 ft., passive Perception 12"
"languages": "Common"
"cr": "1"
"traits":
- "desc": "the generator can't be compelled to act in a manner contrary to its nature\
    \ or its instructions."
  "name": "Axiomatic Mind"
- "desc": "If the generator dies, its body disintegrates into dust, leaving behind\
    \ its weapons and anything else it was carrying."
  "name": "Disintegration"
"actions":
- "desc": "The generator makes two fist attacks or four dart attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d4\
    \ + 1) bludgeoning damage."
  "name": "Fist"
- "desc": "The generator hurls a magic dart at a target it can see up to 60 feet away\
    \ from it. The dart hits its target automatically (no attack roll required) for\
    \ 5 (2d4) force damage."
  "name": "Magic Dart"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Play-by-Play%20Generator.webp"
```
^statblock

```encounter-table
name: Play-by-Play Generator
creatures:
 - 1: Play-by-Play Generator
```