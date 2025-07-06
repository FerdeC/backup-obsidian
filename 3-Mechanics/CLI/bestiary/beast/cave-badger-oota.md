---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1-4
- monster/size/medium
- monster/type/beast
aliases: ["Cave Badger"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Out of the Abyss p. 96
---
# [Cave Badger](2-Mechanics\CLI\bestiary\beast/cave-badger-oota.md)
*Source: Out of the Abyss p. 96*  

```statblock
"name": "Cave Badger (OotA)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "13"
"hit_dice": "2d8 + 4"
"stats":
- !!int "13"
- !!int "10"
- !!int "15"
- !!int "2"
- !!int "12"
- !!int "5"
"speed": "30 ft., burrow 15 ft."
"senses": "darkvision 30 ft., tremorsense 60 ft., passive Perception 11"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The badger has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "When the badger burrows, it leaves tunnels behind."
  "name": "Tunneler"
"actions":
- "desc": "The badger makes two attacks: one with its bite and one with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 6 (2d4\
    \ + 1) slashing damage."
  "name": "Claws"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Cave%20Badger.webp"
```
^statblock

```encounter-table
name: Cave Badger
creatures:
 - 1: Cave Badger
```