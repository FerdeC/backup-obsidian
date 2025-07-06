---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cm
- monster/cr/1
- monster/size/large
- monster/type/construct
aliases: ["Animated Chained Library"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Candlekeep Mysteries p. 24
---
# [Animated Chained Library](2-Mechanics\CLI\bestiary\construct/animated-chained-library-cm.md)
*Source: Candlekeep Mysteries p. 24*  

The three shelves are filled with books bound in iron covers, which are attached to chains that secure them to the shelves—a chained library. The reading desk is used to support the chained books while they are being read.

```statblock
"name": "Animated Chained Library (CM)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "45"
"hit_dice": "6d10 + 12"
"stats":
- !!int "15"
- !!int "8"
- !!int "14"
- !!int "1"
- !!int "5"
- !!int "1"
"speed": "10 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned), [prone](/2-Mechanics/CLI/rules/conditions.md#prone)"
"senses": "blindsight 30 ft. (blind beyond this radius), passive Perception 7"
"languages": ""
"cr": "1"
"traits":
- "desc": "If the library is motionless at the start of combat, it has advantage on\
    \ its initiative roll. Moreover, if a creature hasn't observed the library move\
    \ or act, that creature must succeed on a DC 15 Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ check to discern that the library is animate."
  "name": "False Object"
"actions":
- "desc": "The library makes two attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) bludgeoning damage, and if the target is a creature, it is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 12)."
  "name": "Chained Book"
"source":
- "CM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CM/Animated%20Chained%20Library.webp"
```
^statblock

```encounter-table
name: Animated Chained Library
creatures:
 - 1: Animated Chained Library
```