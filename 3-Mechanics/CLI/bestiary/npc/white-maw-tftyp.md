---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/10
- monster/size/gargantuan
- monster/type/ooze
aliases: ["White Maw"]
NoteIcon: monster
BestiaryType: ooze
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 248
---
# [White Maw](2-Mechanics\CLI\bestiary\npc/white-maw-tftyp.md)
*Source: Tales from the Yawning Portal p. 248*  

```statblock
"name": "White Maw (TftYP)"
"size": "Gargantuan"
"type": "ooze"
"alignment": "Chaotic Neutral"
"ac": !!int "5"
"hp": !!int "217"
"hit_dice": "14d20 + 70"
"stats":
- !!int "18"
- !!int "1"
- !!int "20"
- !!int "12"
- !!int "10"
- !!int "3"
"speed": "10 ft."
"damage_resistances": "acid, cold, fire"
"damage_immunities": "poison"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned), [prone](/2-Mechanics/CLI/rules/conditions.md#prone)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 10"
"languages": "telepathy 50 ft."
"cr": "10"
"traits":
- "desc": "White Maw can occupy another creature's space and vice versa."
  "name": "Amorphous Form"
- "desc": "Any nonmagical weapon made of metal that hits White Maw corrodes. After\
    \ dealing damage, the weapon takes a permanent and cumulative −1 penalty to damage\
    \ rolls. if its penalty drops to −5, the weapon is destroyed. Nonmagical ammunition\
    \ made of metal that hits White Maw is destroyed after dealing damage.\n\nWhite\
    \ Maw can eat through 2-inch-thick, nonmagical metal in 1 round."
  "name": "Corrode Metal"
- "desc": "While White Maw remains motionless, it is indistinguishable from white\
    \ stone."
  "name": "False Appearance"
- "desc": "Any creature that starts its turn in White Maw's space is targeted by a\
    \ pseudopod attack if White Maw isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Killer Response"
"actions":
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 22\
    \ (4d8 + 4) bludgeoning damage plus 9 (2d8) acid damage. If the target is\
    \ wearing nonmagical metal armor, its armor is partly corroded and takes a permanent\
    \ and cumulative −1 penalty to the AC it offers. The armor is destroyed if the\
    \ penalty reduces its AC to 10."
  "name": "Pseudopod"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/White%20Maw.webp"
```
^statblock

```encounter-table
name: White Maw
creatures:
 - 1: White Maw
```