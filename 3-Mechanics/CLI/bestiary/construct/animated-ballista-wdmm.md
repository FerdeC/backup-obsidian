---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/2
- monster/size/large
- monster/type/construct
aliases: ["Animated Ballista"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 39
---
# [Animated Ballista](2-Mechanics\CLI\bestiary\construct/animated-ballista-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 39*  

Each animated ballista is a Large wood-and-iron construct.

```statblock
"name": "Animated Ballista (WDMM)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "15"
"hp": !!int "50"
"hit_dice": "50d1"
"stats":
- !!int "14"
- !!int "10"
- !!int "10"
- !!int "3"
- !!int "3"
- !!int "1"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 120 ft. (blind beyond this radius), passive Perception 6"
"languages": ""
"cr": "2"
"actions":
- "desc": "Ranged Weapon Attack: +6 to hit, range 120 ft., one target. Hit:\
    \ 16 (3d10) fire damage"
  "name": "Magic Bolt"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Animated%20Ballista.webp"
```
^statblock

```encounter-table
name: Animated Ballista
creatures:
 - 1: Animated Ballista
```