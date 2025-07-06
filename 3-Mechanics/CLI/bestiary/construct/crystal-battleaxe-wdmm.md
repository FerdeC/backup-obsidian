---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/1-4
- monster/size/small
- monster/type/construct
aliases: ["Crystal Battleaxe"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 89
---
# [Crystal Battleaxe](2-Mechanics\CLI\bestiary\construct/crystal-battleaxe-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 89*  

```statblock
"name": "Crystal Battleaxe (WDMM)"
"size": "Small"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "17"
"hit_dice": "5d6"
"stats":
- !!int "12"
- !!int "15"
- !!int "11"
- !!int "1"
- !!int "5"
- !!int "1"
"speed": "0 ft., fly 50 ft. (hover)"
"saves":
  "Dexterity": !!int "4"
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 7"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The battleaxe is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ while in the area of an [antimagic field](/2-Mechanics/CLI/spells/antimagic-field.md).\
    \ If targeted by [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), the\
    \ battleaxe must succeed on a Constitution saving throw against the caster's spell\
    \ save DC or fall [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)\
    \ for 1 minute."
  "name": "Antimagic Susceptibility"
- "desc": "While the battleaxe remains motionless and isn't flying, it is indistinguishable\
    \ from a normal battleaxe."
  "name": "False Appearance"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d8\
    \ + 1) slashing damage."
  "name": "Battleaxe"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Crystal%20Battleaxe.webp"
```
^statblock

```encounter-table
name: Crystal Battleaxe
creatures:
 - 1: Crystal Battleaxe
```