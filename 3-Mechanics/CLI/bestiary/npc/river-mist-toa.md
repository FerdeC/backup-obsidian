---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/tabaxi
aliases: ["River Mist"]
NoteIcon: monster
BestiaryType: humanoid (tabaxi)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 35
---
# [River Mist](2-Mechanics\CLI\bestiary\npc/river-mist-toa.md)
*Source: Tomb of Annihilation p. 35*  

```statblock
"name": "River Mist (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "tabaxi"
"alignment": "Chaotic Good"
"ac": !!int "14"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "40"
"hit_dice": "9d8"
"stats":
- !!int "10"
- !!int "17"
- !!int "11"
- !!int "13"
- !!int "14"
- !!int "15"
"speed": "30 ft., climb 20 ft."
"skillsaves":
  "Athletics": !!int "2"
  "Stealth": !!int "5"
  "Perception": !!int "4"
  "Survival": !!int "6"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common plus any one language"
"cr": "1"
"traits":
- "desc": "When River Mist moves on its turn in combat, it can double its speed until\
    \ the end of the turn. Once it uses this ability, River Mist can't use it again\
    \ until it moves 0 feet on one of its turns."
  "name": "Feline Agility"
"actions":
- "desc": "River Mist makes two attacks with its claws, its shortsword, or its shortbow."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d4)\
    \ slashing damage."
  "name": "Claws"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +5 to hit, range 80/320 ft., one target. Hit:\
    \ 6 (1d6 + 3) piercing damage."
  "name": "Shortbow"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/River%20Mist.webp"
```
^statblock

```encounter-table
name: River Mist
creatures:
 - 1: River Mist
```