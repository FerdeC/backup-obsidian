---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/0
- monster/size/tiny
- monster/type/monstrosity
aliases: ["Tressym"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 241
---
# [Tressym](2-Mechanics\CLI\bestiary\monstrosity/tressym-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 241*  

```statblock
"name": "Tressym (BGDIA)"
"size": "Tiny"
"type": "monstrosity"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "5"
"hit_dice": "2d4"
"stats":
- !!int "3"
- !!int "15"
- !!int "10"
- !!int "11"
- !!int "12"
- !!int "12"
"speed": "40 ft., climb 30 ft., fly 40 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "5"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "understands Common but can't speak"
"cr": "0"
"traits":
- "desc": "Within 60 feet of the tressym, magical invisibility fails to conceal anything\
    \ from the tressym's sight."
  "name": "Detect Invisibility"
- "desc": "The tressym has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "The tressym can detect whether a substance is poisonous by taste, touch,\
    \ or smell."
  "name": "Poison Sense"
- "desc": "With the DM's permission, a person who casts the [find familiar](/2-Mechanics/CLI/spells/find-familiar.md)\
    \ spell can choose to conjure a tressym in stead of a normal cat."
  "name": "Familiar"
"actions":
- "desc": "Melee Weapon Attack: +0 to hit, reach 5 ft., one target. Hit: 1 slashing\
    \ damage."
  "name": "Claws"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Tressym.webp"
```
^statblock

```encounter-table
name: Tressym
creatures:
 - 1: Tressym
```