---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/1-4
- monster/size/small
- monster/type/monstrosity
aliases: ["Young Griffon (Small)"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 163
---
# [Young Griffon (Small)](2-Mechanics\CLI\bestiary\monstrosity/young-griffon-small-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 163*  

A griffon is a ferocious avian carnivore with the muscular body of a lion and the head, forelegs, and wings of an eagle.

```statblock
"name": "Young Griffon (Small) (IDRotF)"
"size": "Small"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "13"
"hit_dice": "2d6 + 6"
"stats":
- !!int "8"
- !!int "15"
- !!int "16"
- !!int "2"
- !!int "13"
- !!int "8"
"speed": "30 ft., fly 80 ft."
"skillsaves":
  "Perception": !!int "5"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The griffon has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on sight."
  "name": "Keen Sight"
"actions":
- "desc": "The griffon makes two attacks: one with its beak and one with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +1 to hit, reach 5 ft., one target. Hit: 2 (1d4)\
    \ piercing damage."
  "name": "Beak"
- "desc": "Melee Weapon Attack: +1 to hit, reach 5 ft., one target. Hit: 2 (1d4)\
    \ slashing damage."
  "name": "Claws"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Young%20Griffon%20%28Small%29.webp"
```
^statblock

```encounter-table
name: Young Griffon (Small)
creatures:
 - 1: Young Griffon (Small)
```