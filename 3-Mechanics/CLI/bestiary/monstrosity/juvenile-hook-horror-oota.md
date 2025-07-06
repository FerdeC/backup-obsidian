---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/2
- monster/size/medium
- monster/type/monstrosity
aliases: ["Juvenile Hook Horror"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Out of the Abyss p. 34
---
# [Juvenile Hook Horror](2-Mechanics\CLI\bestiary\monstrosity/juvenile-hook-horror-oota.md)
*Source: Out of the Abyss p. 34*  

```statblock
"name": "Juvenile Hook Horror (OotA)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Neutral"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"stats":
- !!int "15"
- !!int "10"
- !!int "15"
- !!int "6"
- !!int "12"
- !!int "7"
"speed": "20 ft., climb 20 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 13"
"languages": "Hook Horror"
"cr": "2"
"traits":
- "desc": "The hook horror can't use its blindsight while [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened)."
  "name": "Echolocation"
- "desc": "The hook horror has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing."
  "name": "Keen Hearing"
"actions":
- "desc": "The hook horror makes two hook attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Hook"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Juvenile%20Hook%20Horror.webp"
```
^statblock

```encounter-table
name: Juvenile Hook Horror
creatures:
 - 1: Juvenile Hook Horror
```