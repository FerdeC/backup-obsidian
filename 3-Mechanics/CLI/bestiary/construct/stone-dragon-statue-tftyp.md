---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/10
- monster/size/large
- monster/type/construct
aliases: ["Stone Dragon Statue"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 85
---
# [Stone Dragon Statue](2-Mechanics\CLI\bestiary\construct/stone-dragon-statue-tftyp.md)
*Source: Tales from the Yawning Portal p. 85*  

```statblock
"name": "Stone Dragon Statue (TftYP)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "178"
"hit_dice": "17d10 + 85"
"stats":
- !!int "22"
- !!int "9"
- !!int "20"
- !!int "3"
- !!int "11"
- !!int "1"
"speed": "30 ft."
"damage_immunities": "poison; psychic; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't adamantine"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "10"
"traits":
- "desc": "The statue is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
- "desc": "The statue has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The statue's weapon attacks are magical."
  "name": "Magic Weapons"
"actions":
- "desc": "The statue exhales steam in a line that is 30 feet long and 10 feet wide.\
    \ Each creature in that area must make a DC 15 Constitution saving throw, taking\
    \ 7 (2d4 + 2) fire damage on a failed save, or half as much damage on a successful\
    \ one."
  "name": "Steam Breath"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Stone%20Dragon%20Statue.webp"
```
^statblock

```encounter-table
name: Stone Dragon Statue
creatures:
 - 1: Stone Dragon Statue
```