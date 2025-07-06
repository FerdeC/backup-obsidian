---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Zress Orlezziir"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 136
---
# [Zress Orlezziir](2-Mechanics\CLI\bestiary\npc/zress-orlezziir-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 136*  

```statblock
"name": "Zress Orlezziir (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "[chain mail](/2-Mechanics/CLI/items/chain-mail.md)"
"hp": !!int "162"
"hit_dice": "25d8 + 50"
"stats":
- !!int "14"
- !!int "19"
- !!int "15"
- !!int "12"
- !!int "14"
- !!int "13"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "8"
  "Wisdom": !!int "6"
  "Constitution": !!int "6"
"skillsaves":
  "Stealth": !!int "8"
  "Perception": !!int "6"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Elvish, Undercommon"
"cr": "9"
"traits":
- "desc": "Zress's innate spellcasting ability is Charisma (spell save DC 13). He\
    \ can innately cast the following spells, requiring no material components:\n\n\
    At will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\n1/day\
    \ each: [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md) (self only)"
  "name": "Innate Spellcasting"
- "desc": "As a bonus action, Zress targets one ally he can see within 30 feet of\
    \ him. If the target can see or hear Zress, the target can use its reaction to\
    \ make one melee attack or to take the Dodge or Hide action."
  "name": "Battle Command"
- "desc": "Zress has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put Zress to sleep."
  "name": "Fey Ancestry"
- "desc": "While in sunlight, Zress has disadvantage on attack rolls, as well as on\
    \ Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks that\
    \ rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Zress makes three attacks: two with his scimitar and one with his whip\
    \ or his hand crossbow."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) slashing damage plus 14 (4d6) poison damage."
  "name": "Scimitar"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 6\
    \ (1d4 + 4) slashing damage. If the target is an ally, it has advantage on attack\
    \ rolls until the end of its next turn."
  "name": "Whip"
- "desc": "Ranged Weapon Attack: +8 to hit, range 30/120 ft., one target. Hit:\
    \ 7 (1d6 + 4) piercing damage, and the target must succeed on a DC 13 Constitution\
    \ saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 hour. If the saving throw fails by 5 or more, the target is also [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)\
    \ while [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) in this way.\
    \ The target regains consciousness if it takes damage or if another creature takes\
    \ an action to shake it."
  "name": "Hand Crossbow"
"reactions":
- "desc": "Zress adds 3 to his AC against one melee attack that would hit him. To\
    \ do so, Zress must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Zress%20Orlezziir.webp"
```
^statblock

```encounter-table
name: Zress Orlezziir
creatures:
 - 1: Zress Orlezziir
```