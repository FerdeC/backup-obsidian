---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/0
- monster/size/tiny
- monster/type/beast
aliases: ["Hawk"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 330, Waterdeep: Dragon Heist, Baldur's Gate: Descent Into Avernus, Icewind Dale: Rime of the Frostmaiden, Candlekeep Mysteries, The Wild Beyond the Witchlight, Journeys through the Radiant Citadel. Available in the SRD and the Basic Rules.
---
# [Hawk](2-Mechanics\CLI\bestiary\beast/hawk.md)
*Source: Monster Manual p. 330, Waterdeep: Dragon Heist, Baldur's Gate: Descent Into Avernus, Icewind Dale: Rime of the Frostmaiden, Candlekeep Mysteries, The Wild Beyond the Witchlight, Journeys through the Radiant Citadel. Available in the SRD and the Basic Rules.*  

```statblock
"name": "Hawk"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"stats":
- !!int "5"
- !!int "16"
- !!int "8"
- !!int "2"
- !!int "14"
- !!int "6"
"speed": "10 ft., fly 60 ft."
"skillsaves":
  "Perception": !!int "4"
"senses": "passive Perception 14"
"languages": ""
"cr": "0"
"traits":
- "desc": "The hawk has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on sight."
  "name": "Keen Sight"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 1 slashing\
    \ damage."
  "name": "Talons"
"source":
- "MM"
- "WDH"
- "BGDIA"
- "IDRotF"
- "CM"
- "WBtW"
- "JttRC"
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Hawk.webp"
```
^statblock

```encounter-table
name: Hawk
creatures:
 - 1: Hawk
```