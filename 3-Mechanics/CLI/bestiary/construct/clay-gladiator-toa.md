---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/5
- monster/size/medium
- monster/type/construct
aliases: ["Clay Gladiator"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 100
---
# [Clay Gladiator](2-Mechanics\CLI\bestiary\construct/clay-gladiator-toa.md)
*Source: Tomb of Annihilation p. 100*  

A clay gladiator fights if attacked or when called to the gladiatorial pit. If reduced to 0 hit points outside of the gladiatorial pit, the gladiator disappears along with its possessions, reappears in its cell at full health with spear and shield in hand, and returns to the gladiatorial pit if it can. If defeated in the gladiatorial pit, the gladiator leaves its spear behind before reforming in its cell

```statblock
"name": "Clay Gladiator (ToA)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor, [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"stats":
- !!int "18"
- !!int "15"
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "15"
"speed": "30 ft., climb 30 ft."
"saves":
  "Dexterity": !!int "5"
  "Strength": !!int "7"
  "Constitution": !!int "6"
"skillsaves":
  "Intimidation": !!int "5"
  "Athletics": !!int "10"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "passive Perception 11"
"languages": ""
"cr": "5"
"traits":
- "desc": "The gladiator can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Climbing"
- "desc": "The gladiator can't be disarmed, and cannot make ranged attacks."
  "name": "Steadfast"
- "desc": "A melee weapon deals one extra die of its damage when the gladiator hits\
    \ with it (included in the attack)."
  "name": "Brute"
"actions":
- "desc": "The gladiator makes three melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) piercing damage, or 13 (2d8 + 4) piercing damage if used with\
    \ two hands."
  "name": "Spear"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. Hit: 9\
    \ (2d4 + 4) bludgeoning damage. If the target is a Medium or smaller creature,\
    \ it must succeed on a DC 15 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Shield Bash"
"reactions":
- "desc": "The gladiator adds 3 to its AC against one melee attack that would hit\
    \ it. To do so, the gladiator must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Clay%20Gladiator.webp"
```
^statblock

```encounter-table
name: Clay Gladiator
creatures:
 - 1: Clay Gladiator
```