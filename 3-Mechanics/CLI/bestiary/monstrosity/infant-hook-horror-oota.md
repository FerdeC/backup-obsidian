---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/0
- monster/size/tiny
- monster/type/monstrosity
aliases: ["Infant Hook Horror"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Out of the Abyss p. 34
---
# [Infant Hook Horror](2-Mechanics\CLI\bestiary\monstrosity/infant-hook-horror-oota.md)
*Source: Out of the Abyss p. 34*  

```statblock
"name": "Infant Hook Horror (OotA)"
"size": "Tiny"
"type": "monstrosity"
"alignment": "Neutral"
"ac": !!int "10"
"ac_class": "natural armor"
"hp": !!int "4"
"hit_dice": "1d4 + 2"
"stats":
- !!int "9"
- !!int "10"
- !!int "15"
- !!int "6"
- !!int "12"
- !!int "7"
"speed": "10 ft., climb 10 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 13"
"languages": "Hook Horror"
"cr": "0"
"traits":
- "desc": "The hook horror can't use its blindsight while [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened)."
  "name": "Echolocation"
- "desc": "The hook horror has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing."
  "name": "Keen Hearing"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Infant%20Hook%20Horror.webp"
```
^statblock

```encounter-table
name: Infant Hook Horror
creatures:
 - 1: Infant Hook Horror
```