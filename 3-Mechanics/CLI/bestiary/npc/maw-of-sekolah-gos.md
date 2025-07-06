---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/7
- monster/size/huge
- monster/type/monstrosity
aliases: ["Maw of Sekolah"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 244
---
# [Maw of Sekolah](2-Mechanics\CLI\bestiary\npc/maw-of-sekolah-gos.md)
*Source: Ghosts of Saltmarsh p. 244*  

Summoned from the shadowy depths of the ocean through ritual and tidal magic, the Maw of Sekolah appears in The Final Enemy as the avatar of the hungry sahuagin god. This huge, two-headed shark is fed a steady diet of sentient creatures, captured by the sahuagin and offered up as tribute. Sahuagin priestesses adorn the fins of the maw of Sekolah with gemmed bands and polished skulls.

```statblock
"name": "Maw of Sekolah (GoS)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "114"
"hit_dice": "12d12 + 36"
"stats":
- !!int "21"
- !!int "12"
- !!int "17"
- !!int "2"
- !!int "14"
- !!int "7"
"speed": "0 ft., swim 50 ft."
"saves":
  "Strength": !!int "8"
  "Constitution": !!int "6"
"skillsaves":
  "Athletics": !!int "8"
  "Perception": !!int "5"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": "Sahuagin, telepathy 100 ft."
"cr": "7"
"traits":
- "desc": "If the maw of Sekolah fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (2/Day)"
- "desc": "The maw of Sekolah can breathe only underwater."
  "name": "Water Breathing"
"actions":
- "desc": "The maw of Sekolah makes one attack with its bite and one attack with its\
    \ tail smash."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 16\
    \ (2d10 + 5) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 9\
    \ (1d8 + 5) bludgeoning damage."
  "name": "Tail Smash"
"legendary_actions":
- "desc": "The maw of Sekolah makes a Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ check."
  "name": "Detect"
- "desc": "The maw of Sekolah moves up to its speed."
  "name": "Speed of Sekolah"
- "desc": "The ferocious spirit of Sekolah flashes through the water, tearing through\
    \ the foes of the maw of Sekolah. Each creature of the maw's choosing within 60\
    \ feet of it must make a DC 16 Dexterity saving throw, taking 7 (2d6) slashing\
    \ damage on a failed save, or half as much damage on a successful one."
  "name": "Feed (Costs 2 Actions)"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Maw%20of%20Sekolah.webp"
```
^statblock

```encounter-table
name: Maw of Sekolah
creatures:
 - 1: Maw of Sekolah
```