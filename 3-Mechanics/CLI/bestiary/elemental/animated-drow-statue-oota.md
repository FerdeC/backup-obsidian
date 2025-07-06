---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1
- monster/size/medium
- monster/type/elemental
aliases: ["Animated Drow Statue"]
NoteIcon: monster
BestiaryType: elemental
SourceType: Bestiary
BookSource: Out of the Abyss p. 96
---
# [Animated Drow Statue](2-Mechanics\CLI\bestiary\elemental/animated-drow-statue-oota.md)
*Source: Out of the Abyss p. 96*  

```statblock
"name": "Animated Drow Statue (OotA)"
"size": "Medium"
"type": "elemental"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
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
- "desc": "The statue is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ while in the area of an [antimagic field](/2-Mechanics/CLI/spells/antimagic-field.md).\
    \ If targeted by [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), the\
    \ statue must succeed on a Constitution saving throw against the caster's spell\
    \ save DC or fall [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)\
    \ for 1 minute."
  "name": "Antimagic Susceptibility"
- "desc": "While the statue remains motionless, it is indistinguishable from a normal\
    \ statue."
  "name": "False Appearance"
"actions":
- "desc": "The statue makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage."
  "name": "Slam"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Animated%20Drow%20Statue.webp"
```
^statblock

```encounter-table
name: Animated Drow Statue
creatures:
 - 1: Animated Drow Statue
```