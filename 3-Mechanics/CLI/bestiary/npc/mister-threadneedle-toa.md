---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/1
- monster/size/medium
- monster/type/construct
aliases: ["Mister Threadneedle"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 183
---
# [Mister Threadneedle](2-Mechanics\CLI\bestiary\npc/mister-threadneedle-toa.md)
*Source: Tomb of Annihilation p. 183*  

```statblock
"name": "Mister Threadneedle (ToA)"
"size": "Medium"
"type": "construct"
"alignment": "Chaotic Evil"
"ac": !!int "11"
"hp": !!int "36"
"hit_dice": "8d8"
"stats":
- !!int "11"
- !!int "13"
- !!int "11"
- !!int "10"
- !!int "10"
- !!int "13"
"speed": "30 ft."
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned),\
  \ [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "1"
"traits":
- "desc": "While Mister Threadneedle remains motionless, it is indistinguishable from\
    \ an ordinary, inanimate scarecrow."
  "name": "False Appearance"
"actions":
- "desc": "Mister Threadneedle makes two claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 6 (2d4\
    \ + 1) slashing damage. If the target is a creature, it must succeed on a DC\
    \ 11 Wisdom saving throw or be [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ until the end of Mister Threadneedle's next turn."
  "name": "Claw"
- "desc": "Mister Threadneedle targets one creature it can see within 30 feet of it.\
    \ If the target can see Mister Threadneedle, the target must succeed on a DC 11\
    \ Wisdom saving throw or be magically [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ until the end of Mister Threadneedle's next turn. The [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ target is [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed)."
  "name": "Terrifying Glare"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Mister%20Threadneedle.webp"
```
^statblock

```encounter-table
name: Mister Threadneedle
creatures:
 - 1: Mister Threadneedle
```