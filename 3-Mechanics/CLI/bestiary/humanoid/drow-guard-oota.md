---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Drow Guard"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Out of the Abyss p. 195
---
# [Drow Guard](2-Mechanics\CLI\bestiary\humanoid/drow-guard-oota.md)
*Source: Out of the Abyss p. 195*  

```statblock
"name": "Drow Guard (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[chain shirt](/2-Mechanics/CLI/items/chain-shirt.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "13"
- !!int "12"
- !!int "12"
- !!int "10"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "any one language (usually Common), Elvish"
"cr": "1/8"
"traits":
- "desc": "The drow guard\n\nAt will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\
    \n1/day each: [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md)"
  "name": "Innate Spellcasting"
- "desc": "The drow guard"
  "name": "Fey Ancestry"
- "desc": "the drow guard"
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d6 + 1) piercing damage, or 5 (1d8 + 1) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Spear"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Drow%20Guard.webp"
```
^statblock

```encounter-table
name: Drow Guard
creatures:
 - 1: Drow Guard
```