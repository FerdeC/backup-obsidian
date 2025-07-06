---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/1-8
- monster/size/medium
- monster/type/construct
aliases: ["Wooden Donkey"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 84
---
# [Wooden Donkey](2-Mechanics\CLI\bestiary\construct/wooden-donkey-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 84*  

A crude wooden constructs resembling a donkey. Each of these magic dummies has a body made of a wooden keg turned on its side. A head and neck made of wood and sackcloth is attached to one end of the keg. At the other end is a tail made from a straw broom. Each keg is held up by four 2-foot-long peg legs.

```statblock
"name": "Wooden Donkey (WDMM)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "14"
- !!int "10"
- !!int "13"
- !!int "2"
- !!int "10"
- !!int "5"
"speed": "40 ft."
"damage_immunities": "poison"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 30 ft. (blind beyond this radius), passive Perception 10"
"languages": ""
"cr": "1/8"
"traits":
- "desc": "The donkey is considered to be a Large animal for the purpose of determining\
    \ its carrying capacity."
  "name": "Beast of Burden"
- "desc": "The donkey has advantage on Strength and Dexterity saving throws made against\
    \ effects that would knock it [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Sure-Footed"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) bludgeoning damage."
  "name": "Hooves"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Wooden%20Donkey.webp"
```
^statblock

```encounter-table
name: Wooden Donkey
creatures:
 - 1: Wooden Donkey
```