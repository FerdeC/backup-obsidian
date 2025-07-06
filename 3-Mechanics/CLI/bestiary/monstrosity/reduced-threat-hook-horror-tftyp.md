---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/3
- monster/size/large
- monster/type/monstrosity
aliases: ["Reduced-Threat Hook Horror"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 113
---
# [Reduced-Threat Hook Horror](2-Mechanics\CLI\bestiary\monstrosity/reduced-threat-hook-horror-tftyp.md)
*Source: Tales from the Yawning Portal p. 113*  

```statblock
"name": "Reduced-Threat Hook Horror (TftYP)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "37"
"hit_dice": "10d10 + 20"
"stats":
- !!int "18"
- !!int "10"
- !!int "15"
- !!int "6"
- !!int "12"
- !!int "7"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Perception": !!int "1"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 13"
"languages": "Hook Horror"
"cr": "3"
"traits":
- "desc": "A reduced-threat monster takes a −2 penalty on attack rolls (included in\
    \ the stat block), ability checks (included in the stat block for skill proficiencies),\
    \ saving throws (included in the stat block for saving throw proficiencies), and\
    \ saving throw DCs (included in the stat block)."
  "name": "Reduced Threat"
- "desc": "The hook horror can't use its blindsight while [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened)."
  "name": "Echolocation"
- "desc": "The hook horror has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing."
  "name": "Keen Hearing"
"actions":
- "desc": "The hook horror makes two hook attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 10 ft., one target. Hit: 11\
    \ (2d6 + 4) piercing damage."
  "name": "Hook"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Reduced-Threat%20Hook%20Horror.webp"
```
^statblock

```encounter-table
name: Reduced-Threat Hook Horror
creatures:
 - 1: Reduced-Threat Hook Horror
```