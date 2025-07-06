---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1-4
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Drow Acolyte"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Out of the Abyss p. 201
---
# [Drow Acolyte](2-Mechanics\CLI\bestiary\humanoid/drow-acolyte-oota.md)
*Source: Out of the Abyss p. 201*  

```statblock
"name": "Drow Acolyte (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "10"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "14"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Medicine": !!int "4"
  "Religion": !!int "2"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "any one language (usually Common), Elvish"
"cr": "1/4"
"traits":
- "desc": "The acolyte is a 1st-level spellcaster. Its spellcasting ability is Wisdom\
    \ (spell save DC 12, +4 to hit with spell attacks). The acolyte has following\
    \ cleric spells prepared:\n\nCantrips (at will): [light](/2-Mechanics/CLI/spells/light.md),\
    \ [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1st level (3 slots): [bless](/2-Mechanics/CLI/spells/bless.md), [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md),\
    \ [sanctuary](/2-Mechanics/CLI/spells/sanctuary.md)"
  "name": "Spellcasting"
- "desc": "The drow acolyte\n\nAt will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\
    \n1/day each: [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md)"
  "name": "Innate Spellcasting"
- "desc": "The drow acolyte"
  "name": "Fey Ancestry"
- "desc": "the drow acolyte"
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d4)\
    \ bludgeoning damage."
  "name": "Club"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Drow%20Acolyte.webp"
```
^statblock

```encounter-table
name: Drow Acolyte
creatures:
 - 1: Drow Acolyte
```