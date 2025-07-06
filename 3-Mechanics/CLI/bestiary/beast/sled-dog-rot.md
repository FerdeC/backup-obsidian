---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/rot
- monster/cr/1-4
- monster/size/medium
- monster/type/beast
aliases: ["Sled Dog"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: The Rise of Tiamat p. 27
---
# [Sled Dog](2-Mechanics\CLI\bestiary\beast/sled-dog-rot.md)
*Source: The Rise of Tiamat p. 27*  

```statblock
"name": "Sled Dog (RoT)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "12"
- !!int "15"
- !!int "12"
- !!int "3"
- !!int "12"
- !!int "6"
"speed": "40 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The dog has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or smell."
  "name": "Keen Hearing and Smell"
- "desc": "The dog has advantage on an attack roll against a creature if at least\
    \ one of the dog's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (2d4\
    \ + 2) piercing damage. If the target is a creature, it must succeed on a DC\
    \ 11 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Bite"
"source":
- "RoT"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/RoT/Sled%20Dog.webp"
```
^statblock

```encounter-table
name: Sled Dog
creatures:
 - 1: Sled Dog
```