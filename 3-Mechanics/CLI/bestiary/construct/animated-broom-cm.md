---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cm
- monster/cr/1-4
- monster/size/small
- monster/type/construct
aliases: ["Animated Broom"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Candlekeep Mysteries p. 20
---
# [Animated Broom](2-Mechanics\CLI\bestiary\construct/animated-broom-cm.md)
*Source: Candlekeep Mysteries p. 20*  

```statblock
"name": "Animated Broom (CM)"
"size": "Small"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "17"
"hit_dice": "5d6"
"stats":
- !!int "10"
- !!int "17"
- !!int "10"
- !!int "1"
- !!int "5"
- !!int "1"
"speed": "0 ft., fly 50 ft. (hover)"
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned), [prone](/2-Mechanics/CLI/rules/conditions.md#prone)"
"senses": "blindsight 120 ft. (blind beyond this radius), passive Perception 7"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "If the broom is motionless at the start of combat, it has advantage on\
    \ its initiative roll. Moreover, if a creature hasn't observed the broom move\
    \ or act, that creature must succeed on a DC 15 Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ check to discern that the broom is animate."
  "name": "False Object"
- "desc": "The broom doesn't provoke opportunity attacks when it flies out of an enemy's\
    \ reach."
  "name": "Flyby"
"actions":
- "desc": "The broom makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
    \ + 3) bludgeoning damage."
  "name": "Broomstick"
"source":
- "CM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CM/Animated%20Broom.webp"
```
^statblock

```encounter-table
name: Animated Broom
creatures:
 - 1: Animated Broom
```