---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wbtw
- monster/cr/1
- monster/size/small
- monster/type/construct
aliases: ["Tin Soldier"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: The Wild Beyond the Witchlight p. 115
---
# [Tin Soldier](2-Mechanics\CLI\bestiary\construct/tin-soldier-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 115*  

These automatons are fashioned to look like stout infantry soldiers, and they obey Skabatha without question. They charge forth to investigate any suspicious activity they see or hear, meaning that they are easily distracted.

```statblock
"name": "Tin Soldier (WBtW)"
"size": "Small"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "27"
"hit_dice": "6d6 + 6"
"stats":
- !!int "14"
- !!int "11"
- !!int "13"
- !!int "1"
- !!int "3"
- !!int "1"
"speed": "25 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 6"
"languages": ""
"cr": "1"
"traits":
- "desc": "The tin soldier is incapacitated while in the area of an [antimagic field](/2-Mechanics/CLI/spells/antimagic-field.md).\
    \ If targeted by [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), the\
    \ tin soldier must succeed on a Constitution saving throw against the caster's\
    \ spell save DC or fall unconscious for 1 minute."
  "name": "Antimagic Susceptibility"
- "desc": "While the tin soldier remains motionless, it is indistinguishable from\
    \ a normal suit of armor."
  "name": "False Appearance"
"actions":
- "desc": "The tin soldier makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage."
  "name": "Slam"
"source":
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WBtW/Tin%20Soldier.webp"
```
^statblock

```encounter-table
name: Tin Soldier
creatures:
 - 1: Tin Soldier
```