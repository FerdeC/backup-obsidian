---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Drow Bandit"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Out of the Abyss p. 194
---
# [Drow Bandit](2-Mechanics\CLI\bestiary\humanoid/drow-bandit-oota.md)
*Source: Out of the Abyss p. 194*  

```statblock
"name": "Drow Bandit (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Lawful alignment"
"ac": !!int "12"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "11"
- !!int "12"
- !!int "12"
- !!int "10"
- !!int "10"
- !!int "10"
"speed": "30 ft."
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "any one language (usually Common), Elvish"
"cr": "1/8"
"traits":
- "desc": "The drow bandit\n\nAt will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\
    \n1/day each: [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md)"
  "name": "Innate Spellcasting"
- "desc": "The drow bandit"
  "name": "Fey Ancestry"
- "desc": "the drow bandit"
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) slashing damage."
  "name": "Scimitar"
- "desc": "Ranged Weapon Attack: +3 to hit, range 80/320 ft., one target. Hit:\
    \ 5 (1d8 + 1) piercing damage."
  "name": "Light Crossbow"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Drow%20Bandit.webp"
```
^statblock

```encounter-table
name: Drow Bandit
creatures:
 - 1: Drow Bandit
```