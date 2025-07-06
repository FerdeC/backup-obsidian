---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/0
- monster/size/tiny
- monster/type/beast
aliases: ["Chimeric Weasel"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 246
---
# [Chimeric Weasel](2-Mechanics\CLI\bestiary\beast/chimeric-weasel-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 246*  

```statblock
"name": "Chimeric Weasel (IDRotF)"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"stats":
- !!int "3"
- !!int "16"
- !!int "8"
- !!int "2"
- !!int "12"
- !!int "3"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "0"
"traits":
- "desc": "The weasel has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or smell."
  "name": "Keen Hearing and Smell"
- "desc": "The weasel has glowing eyes that emit bright light out in a 20-foot radius\
    \ and dim light for an additional 20 feet."
  "name": "Chimeric Creation"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 1 piercing\
    \ damage."
  "name": "Bite"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Chimeric%20Weasel.webp"
```
^statblock

```encounter-table
name: Chimeric Weasel
creatures:
 - 1: Chimeric Weasel
```