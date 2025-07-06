---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cm
- monster/cr/8
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Jade Tigress"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Candlekeep Mysteries p. 166
---
# [Jade Tigress](2-Mechanics\CLI\bestiary\npc/jade-tigress-cm.md)
*Source: Candlekeep Mysteries p. 166*  

Jade Tigress is a powerfully built woman whose body has been honed by intense physical training. She is rugged in appearance, with jet-black hair, hazel eyes, and a long, thin scar running across her right cheek. She matches the description of one of the thieves who infiltrated Candlekeep.

```statblock
"name": "Jade Tigress (CM)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "15"
"ac_class": "Unarmored Defense"
"hp": !!int "71"
"hit_dice": "11d8 + 21"
"stats":
- !!int "18"
- !!int "14"
- !!int "15"
- !!int "11"
- !!int "16"
- !!int "11"
"speed": "40 ft."
"saves":
  "Strength": !!int "7"
  "Constitution": !!int "5"
"skillsaves":
  "Intimidation": !!int "3"
  "Athletics": !!int "7"
  "Insight": !!int "6"
  "Perception": !!int "6"
"damage_resistances": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "passive Perception 16"
"languages": "Common"
"cr": "8"
"traits":
- "desc": "While Jade Tigress is wearing no armor and wielding no shield, her AC includes\
    \ her Wisdom modifier."
  "name": "Unarmored Defense"
"actions":
- "desc": "Jade Tigress makes three attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) force damage, and if the target is a creature, it must succeed on\
    \ a DC 15 Constitution saving throw or be [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)\
    \ until the end of Jade Tigress's next turn."
  "name": "Force Strike"
- "desc": "Ranged Weapon Attack: +5 to hit, range 20/60 ft., one target. Hit:\
    \ 4 (1d4 + 2) piercing damage plus 7 (3d4) poison damage, and the target must\
    \ succeed on a DC 15 Constitution saving throw or gain 1 level of [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion)."
  "name": "Poisoned Dart"
- "desc": "Jade Tigress regains 2d8 + 2 hit points, and all levels of [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion)\
    \ end on her."
  "name": "Heal Self (Recharges after a Long Rest)"
"bonus_actions":
- "desc": "Jade Tigress takes the Disengage or Hide action."
  "name": "Nimble Escape"
"reactions":
- "desc": "In response to being hit by a ranged weapon attack, Jade Tigress deflects\
    \ the missile. The damage she takes from the attack is reduced by 1d10 + 9.\
    \ If the damage is reduced to 0, Jade Tigress catches the missile if it's small\
    \ enough to hold in one hand and Jade Tigress has a hand free."
  "name": "Deflect Missile"
"source":
- "CM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CM/Jade%20Tigress.webp"
```
^statblock

```encounter-table
name: Jade Tigress
creatures:
 - 1: Jade Tigress
```