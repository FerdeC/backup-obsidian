---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wbtw
- monster/cr/1-8
- monster/size/medium
- monster/type/construct
aliases: ["Flying Rocking Horse"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: The Wild Beyond the Witchlight p. 121
---
# [Flying Rocking Horse](2-Mechanics\CLI\bestiary\construct/flying-rocking-horse-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 121*  

```statblock
"name": "Flying Rocking Horse (WBtW)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"stats":
- !!int "10"
- !!int "10"
- !!int "13"
- !!int "1"
- !!int "3"
- !!int "1"
"speed": "0 ft., fly 40 ft. (only while mounted; hover)"
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 6"
"languages": ""
"cr": "1/8"
"traits":
- "desc": "If the rocking horse is motionless at the start of combat, it has advantage\
    \ on its initiative roll. Moreover, if a creature hasn't observed the rocking\
    \ horse move or act, that creature must succeed on a DC 18 Intelligence ([Investigation](/2-Mechanics/CLI/rules/skills.md#Investigation))\
    \ check to discern that the rocking horse is animate."
  "name": "False Appearance"
- "desc": "The rocking horse can serve as a mount for a Medium or smaller creature\
    \ and can fly only while mounted."
  "name": "Flying Mount"
- "desc": "The rocking horse doesn't require air, food, drink, or sleep, and it regains\
    \ no hit points or Hit Dice at the end of a long rest."
  "name": "Unusual Nature"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 3 (1d6)\
    \ bludgeoning damage."
  "name": "Head Butt"
"source":
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WBtW/Flying%20Rocking%20Horse.webp"
```
^statblock

```encounter-table
name: Flying Rocking Horse
creatures:
 - 1: Flying Rocking Horse
```