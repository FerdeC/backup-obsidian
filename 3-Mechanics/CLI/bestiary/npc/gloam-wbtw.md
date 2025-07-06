---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wbtw
- monster/cr/0
- monster/size/tiny
- monster/type/undead
aliases: ["Gloam"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: The Wild Beyond the Witchlight p. 93
---
# [Gloam](2-Mechanics\CLI\bestiary\npc/gloam-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 93*  

```statblock
"name": "Gloam (WBtW)"
"size": "Tiny"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "2"
"hit_dice": "1d4"
"stats":
- !!int "3"
- !!int "15"
- !!int "10"
- !!int "3"
- !!int "12"
- !!int "7"
"speed": "40 ft., climb 30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "3"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "passive Perception 13"
"languages": ""
"cr": "0"
"traits":
- "desc": "The cat has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
"actions":
- "desc": "Melee Weapon Attack: +0 to hit, reach 5 ft., one target. Hit: 1 slashing\
    \ damage."
  "name": "Claws"
- "desc": "On its first turn in combat or when it is reduced to 0 hit points, the\
    \ cat expels a cloud of dust that acts as dust of sneezing and choking"
  "name": "Cloud of Dust"
"source":
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WBtW/Gloam.webp"
```
^statblock

```encounter-table
name: Gloam
creatures:
 - 1: Gloam
```