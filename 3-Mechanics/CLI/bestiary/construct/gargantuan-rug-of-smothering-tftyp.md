---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/2
- monster/size/gargantuan
- monster/type/construct
aliases: ["Gargantuan Rug of Smothering"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 56
---
# [Gargantuan Rug of Smothering](2-Mechanics\CLI\bestiary\construct/gargantuan-rug-of-smothering-tftyp.md)
*Source: Tales from the Yawning Portal p. 56*  

```statblock
"name": "Gargantuan Rug of Smothering (TftYP)"
"size": "Gargantuan"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "63"
"hit_dice": "6d20"
"stats":
- !!int "17"
- !!int "14"
- !!int "10"
- !!int "1"
- !!int "3"
- !!int "1"
"speed": "10 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 6"
"languages": ""
"cr": "2"
"traits":
- "desc": "The rug is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ while in the area of an [antimagic field](/2-Mechanics/CLI/spells/antimagic-field.md).\
    \ If targeted by [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), the\
    \ rug must succeed on a Constitution saving throw against the caster's spell save\
    \ DC or fall [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious) for\
    \ 1 minute."
  "name": "Antimagic Susceptibility"
- "desc": "While it is grappling a creature, the rug takes only half the damage dealt\
    \ to it, and the creature [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ by the rug takes the other half."
  "name": "Damage Transfer"
- "desc": "While the rug remains motionless, it is indistinguishable from a normal\
    \ rug."
  "name": "False Appearance"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one Medium or smaller\
    \ creature. Hit: The creature is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 13). Until this grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
    \ [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded), and at risk of suffocating,\
    \ and the rug can't smother another target. In addition, at the start of each\
    \ of the target's turns, the target takes 10 (2d6 + 3) bludgeoning damage."
  "name": "Smother"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Gargantuan%20Rug%20of%20Smothering.webp"
```
^statblock

```encounter-table
name: Gargantuan Rug of Smothering
creatures:
 - 1: Gargantuan Rug of Smothering
```