---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/15
- monster/size/medium
- monster/type/undead
aliases: ["Lesser Mummy Lord"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 224
---
# [Lesser Mummy Lord](2-Mechanics\CLI\bestiary\undead/lesser-mummy-lord-tftyp.md)
*Source: Tales from the Yawning Portal p. 224*  

```statblock
"name": "Lesser Mummy Lord (TftYP)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "97"
"hit_dice": "13d8 + 39"
"stats":
- !!int "18"
- !!int "10"
- !!int "17"
- !!int "11"
- !!int "18"
- !!int "16"
"speed": "20 ft."
"saves":
  "Charisma": !!int "8"
  "Wisdom": !!int "9"
  "Intelligence": !!int "5"
  "Constitution": !!int "8"
"skillsaves":
  "Religion": !!int "5"
  "History": !!int "5"
"damage_resistances": "fire"
"damage_immunities": "necrotic; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "the languages it knew in life"
"cr": "15"
"traits":
- "desc": "The mummy lord has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
- "desc": "A destroyed mummy lord gains a new body in 24 hours if its heart is intact,\
    \ regaining all its hit points and becoming active again. The new body appears\
    \ within 5 feet of the mummy lord's heart."
  "name": "Rejuvenation"
- "desc": "The mummy wears a [ring of fire resistance](/2-Mechanics/CLI/items/ring-of-fire-resistance.md)."
  "name": "Special Equipment"
"actions":
- "desc": "The mummy can use its Dreadful Glare and makes one attack with its rotting\
    \ fist."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 14\
    \ (3d6 + 4) bludgeoning damage plus 21 (6d6) necrotic damage. If the target\
    \ is a creature, it must succeed on a DC 16 Constitution saving throw or be cursed\
    \ with mummy rot. The cursed target can't regain hit points, and its hit point\
    \ maximum decreases by 10 (3d6) for every 24 hours that elapse. If the curse\
    \ reduces the target's hit point maximum to 0, the target dies, and its body turns\
    \ to dust. The curse lasts until removed by the [remove curse](/2-Mechanics/CLI/spells/remove-curse.md)\
    \ spell or other magic."
  "name": "Rotting Fist"
- "desc": "The mummy lord targets one creature it can see within 60 feet of it. If\
    \ the target can see the mummy lord, it must succeed on a DC 16 Wisdom saving\
    \ throw against this magic or become [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ until the end of the mummy's next turn. If the target fails the saving throw\
    \ by 5 or more, it is also [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed)\
    \ for the same duration. A target that succeeds on the saving throw is immune\
    \ to the Dreadful Glare of all mummies and mummy lords for the next 24 hours."
  "name": "Dreadful Glare"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Lesser%20Mummy%20Lord.webp"
```
^statblock

```encounter-table
name: Lesser Mummy Lord
creatures:
 - 1: Lesser Mummy Lord
```