---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cm
- monster/cr/11
- monster/size/huge
- monster/type/undead
aliases: ["Parasite-infested Behir"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Candlekeep Mysteries p. 220
---
# [Parasite-infested Behir](2-Mechanics\CLI\bestiary\undead/parasite-infested-behir-cm.md)
*Source: Candlekeep Mysteries p. 220*  

When a parasite-infested behir roars or discharges their lightning breath, thousands of gray, parasitic blood worms can be seen writhing inside their mouths. Targeting the behir with magic that removes a disease kills off its blood parasites.

```statblock
"name": "Parasite-infested Behir (CM)"
"size": "Huge"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "168"
"hit_dice": "16d12 + 64"
"stats":
- !!int "23"
- !!int "16"
- !!int "18"
- !!int "7"
- !!int "14"
- !!int "12"
"speed": "50 ft., climb 40 ft."
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "6"
"damage_immunities": "lightning"
"senses": "darkvision 90 ft., passive Perception 16"
"languages": "Draconic"
"cr": "11"
"actions":
- "desc": "The behir makes two attacks: one with its bite and one to constrict."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 22\
    \ (3d10 + 6) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one Large or smaller\
    \ creature. Hit: 17 (2d10 + 6) bludgeoning damage plus 17 (2d10 + 6) slashing\
    \ damage. The target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 16) if the behir isn't already constricting a creature, and the target\
    \ is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained) until this\
    \ grapple ends."
  "name": "Constrict"
- "desc": "The behir exhales a line of lightning that is 20 feet long and 5 feet wide.\
    \ Each creature in that line must make a DC 16 Dexterity saving throw, taking\
    \ 66 (12d10) lightning damage on a failed save, or half as much damage on a\
    \ successful one."
  "name": "Lightning Breath (Recharge 5-6)"
- "desc": "The behir makes one bite attack against a Medium or smaller target it is\
    \ grappling. If the attack hits, the target is also swallowed, and the grapple\
    \ ends. While swallowed, the target is [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded)\
    \ and [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained), it has total\
    \ cover against attacks and other effects outside the behir, and it takes 21 (6d6)\
    \ acid damage at the start of each of the behir's turns. A behir can have only\
    \ one creature swallowed at a time.\n\nAny creature swallowed by a parasite-infested\
    \ behir must succeed on a DC 19 Constitution saving throw at the start of each\
    \ of the behir's turns or be feasted upon by blood parasites, taking 36 (8d8)\
    \ necrotic damage on a failed save, or half as much damage on a successful save.\
    \ This damage is in addition to the damage caused by the behir's digestive acids.\n\
    \nIf the behir takes 30 damage or more on a single turn from the swallowed creature,\
    \ the behir must succeed on a DC 14 Constitution saving throw at the end of that\
    \ turn or regurgitate the creature, which falls [prone](/2-Mechanics/CLI/rules/conditions.md#prone)\
    \ in a space within 10 feet of the behir. If the behir dies, a swallowed creature\
    \ is no longer [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained) by\
    \ it and can escape from the corpse by using 15 feet of movement, exiting [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Swallow"
"source":
- "CM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CM/Parasite-infested%20Behir.webp"
```
^statblock

```encounter-table
name: Parasite-infested Behir
creatures:
 - 1: Parasite-infested Behir
```