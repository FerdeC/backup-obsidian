---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1-4
- monster/size/small
- monster/type/monstrosity
aliases: ["Young Hook Horror"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Out of the Abyss p. 34
---
# [Young Hook Horror](2-Mechanics\CLI\bestiary\monstrosity/young-hook-horror-oota.md)
*Source: Out of the Abyss p. 34*  

```statblock
"name": "Young Hook Horror (OotA)"
"size": "Small"
"type": "monstrosity"
"alignment": "Neutral"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "11"
"hit_dice": "2d6 + 4"
"stats":
- !!int "12"
- !!int "10"
- !!int "15"
- !!int "6"
- !!int "12"
- !!int "7"
"speed": "15 ft., climb 15 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 13"
"languages": "Hook Horror"
"cr": "1/4"
"traits":
- "desc": "The hook horror can't use its blindsight while [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened)."
  "name": "Echolocation"
- "desc": "The hook horror has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing."
  "name": "Keen Hearing"
"actions":
- "desc": "The hook horror makes two hook attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d4\
    \ + 1) piercing damage."
  "name": "Hook"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Young%20Hook%20Horror.webp"
```
^statblock

```encounter-table
name: Young Hook Horror
creatures:
 - 1: Young Hook Horror
```