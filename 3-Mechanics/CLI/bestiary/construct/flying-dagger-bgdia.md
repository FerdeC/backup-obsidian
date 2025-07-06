---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/1-8
- monster/size/tiny
- monster/type/construct
aliases: ["Flying Dagger"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 30
---
# [Flying Dagger](2-Mechanics\CLI\bestiary\construct/flying-dagger-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 30*  

```statblock
"name": "Flying Dagger (BGDIA)"
"size": "Tiny"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "7"
"hit_dice": "3d4"
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
"cr": "1/8"
"traits":
- "desc": "The dagger is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ while in the area of an [antimagic field](/2-Mechanics/CLI/spells/antimagic-field.md).\
    \ If targeted by [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), the\
    \ dagger must succeed on a Constitution saving throw against the caster's spell\
    \ save DC or fall [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)\
    \ for 1 minute."
  "name": "Antimagic Susceptibility"
- "desc": "While the dagger remains motionless and isn't flying, it is indistinguishable\
    \ from a normal dagger."
  "name": "False Appearance"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d4\
    \ + 1) piercing damage."
  "name": "Dagger"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Flying%20Dagger.webp"
```
^statblock

```encounter-table
name: Flying Dagger
creatures:
 - 1: Flying Dagger
```