---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/0
- monster/size/tiny
- monster/type/beast
aliases: ["Chimeric Fox"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 246
---
# [Chimeric Fox](2-Mechanics\CLI\bestiary\beast/chimeric-fox-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 246*  

The white arctic foxes of Icewind Dale live in burrows and are acclimated to cold weather. They prowl the outskirts of Ten-Towns and nearby forests for food, hunting hares or stealing fish. These timid creatures avoid contact with humanoids, but they are sometimes used as mounts by chwingas.

```statblock
"name": "Chimeric Fox (IDRotF)"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "2"
"hit_dice": "1d4"
"stats":
- !!int "2"
- !!int "16"
- !!int "11"
- !!int "3"
- !!int "12"
- !!int "6"
"speed": "30 ft., burrow 5 ft."
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": ""
"cr": "0"
"traits":
- "desc": "The fox has fur that changes color to match its surroundings, giving it\
    \ advantage on Dexterity (Stealth) checks."
  "name": "Chimeric Creation"
- "desc": "The fox has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing."
  "name": "Keen Hearing"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 1\
    \ piercing damage."
  "name": "Bite"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Chimeric%20Fox.webp"
```
^statblock

```encounter-table
name: Chimeric Fox
creatures:
 - 1: Chimeric Fox
```