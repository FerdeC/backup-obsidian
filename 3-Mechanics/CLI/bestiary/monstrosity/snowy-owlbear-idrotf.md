---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/3
- monster/size/large
- monster/type/monstrosity
aliases: ["Snowy Owlbear"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 309
---
# [Snowy Owlbear](2-Mechanics\CLI\bestiary\monstrosity/snowy-owlbear-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 309*  

A snowy owlbear combines the physical features of a snowy owl and a polar bear. When not asleep or hibernating, it galumphs across the icy tundra in search of food.

```statblock
"name": "Snowy Owlbear (IDRotF)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "59"
"hit_dice": "7d10 + 21"
"stats":
- !!int "20"
- !!int "12"
- !!int "17"
- !!int "3"
- !!int "12"
- !!int "7"
"speed": "40 ft., swim 30 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": ""
"cr": "3"
"traits":
- "desc": "The owlbear has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on sight or smell."
  "name": "Keen Sight and Smell"
"actions":
- "desc": "The owlbear makes two attacks: one with its beak and one with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. Hit: 10\
    \ (1d10 + 5) piercing damage."
  "name": "Beak"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 14\
    \ (2d8 + 5) slashing damage."
  "name": "Claws"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Snowy%20Owlbear.webp"
```
^statblock

```encounter-table
name: Snowy Owlbear
creatures:
 - 1: Snowy Owlbear
```