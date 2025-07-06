---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/0
- monster/size/tiny
- monster/type/beast
aliases: ["Chimeric Cat"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 246
---
# [Chimeric Cat](2-Mechanics\CLI\bestiary\beast/chimeric-cat-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 246*  

The chimeric cat has antennae that grant it blindsight and tremorsense out to a range of 60 feet

```statblock
"name": "Chimeric Cat (IDRotF)"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "2"
"hit_dice": "1d4"
"stats":
- !!int "3"
- !!int "15"
- !!int "10"
- !!int "3"
- !!int "12"
- !!int "7"
"speed": "40 ft., climb 30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "3"
"senses": "blindsight 60 ft., tremorsense 60 ft., passive Perception 13"
"languages": ""
"cr": "0"
"traits":
- "desc": "The cat has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
"actions":
- "desc": "Melee Weapon Attack: +0 to hit, reach 5 ft., one target. Hit: 1 slashing\
    \ damage."
  "name": "Claws"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Chimeric%20Cat.webp"
```
^statblock

```encounter-table
name: Chimeric Cat
creatures:
 - 1: Chimeric Cat
```