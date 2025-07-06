---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/8
- monster/size/large
- monster/type/fiend/demon
aliases: ["Reduced-Threat Hezrou"]
NoteIcon: monster
BestiaryType: fiend (demon)
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 113
---
# [Reduced-Threat Hezrou](2-Mechanics\CLI\bestiary\fiend/reduced-threat-hezrou-tftyp.md)
*Source: Tales from the Yawning Portal p. 113*  

```statblock
"name": "Reduced-Threat Hezrou (TftYP)"
"size": "Large"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "68"
"hit_dice": "13d10 + 65"
"stats":
- !!int "19"
- !!int "17"
- !!int "20"
- !!int "5"
- !!int "12"
- !!int "13"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "2"
  "Strength": !!int "5"
  "Constitution": !!int "6"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Abyssal, telepathy 120 ft."
"cr": "8"
"traits":
- "desc": "A reduced-threat monster takes a −2 penalty on attack rolls (included in\
    \ the stat block), ability checks (included in the stat block for skill proficiencies),\
    \ saving throws (included in the stat block for saving throw proficiencies), and\
    \ saving throw DCs (included in the stat block)."
  "name": "Reduced Threat"
- "desc": "The hezrou has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Any creature that starts its turn within 10 feet of the hezrou must succeed\
    \ on a DC 12 Constitution saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ until the start of its next turn. On a successful saving throw, the creature\
    \ is immune to the hezrou's stench for 24 hours."
  "name": "Stench"
"actions":
- "desc": "The hezrou makes three attacks: one with its bite and two with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 15\
    \ (2d10 + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) slashing damage."
  "name": "Claws"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Reduced-Threat%20Hezrou.webp"
```
^statblock

```encounter-table
name: Reduced-Threat Hezrou
creatures:
 - 1: Reduced-Threat Hezrou
```