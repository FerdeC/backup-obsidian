---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Drow Noble"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Out of the Abyss p. 196
---
# [Drow Noble](2-Mechanics\CLI\bestiary\humanoid/drow-noble-oota.md)
*Source: Out of the Abyss p. 196*  

```statblock
"name": "Drow Noble (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "[breastplate](/2-Mechanics/CLI/items/breastplate.md)"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "11"
- !!int "12"
- !!int "11"
- !!int "12"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Insight": !!int "4"
  "Persuasion": !!int "5"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "any two languages, Elvish"
"cr": "1/8"
"traits":
- "desc": "The drow noble\n\nAt will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\
    \n1/day each: [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md)"
  "name": "Innate Spellcasting"
- "desc": "The drow noble"
  "name": "Fey Ancestry"
- "desc": "the drow noble"
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d8\
    \ + 1) piercing damage."
  "name": "Rapier"
"reactions":
- "desc": "The noble adds 2 to its AC against one melee attack that would hit it.\
    \ To do so, the noble must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Drow%20Noble.webp"
```
^statblock

```encounter-table
name: Drow Noble
creatures:
 - 1: Drow Noble
```