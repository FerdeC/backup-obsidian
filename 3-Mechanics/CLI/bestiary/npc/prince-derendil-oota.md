---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/quaggoth
aliases: ["Prince Derendil"]
NoteIcon: monster
BestiaryType: humanoid (quaggoth)
SourceType: Bestiary
BookSource: Out of the Abyss p. 6
---
# [Prince Derendil](2-Mechanics\CLI\bestiary\npc/prince-derendil-oota.md)
*Source: Out of the Abyss p. 6*  

```statblock
"name": "Prince Derendil (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "quaggoth"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"stats":
- !!int "17"
- !!int "12"
- !!int "16"
- !!int "6"
- !!int "12"
- !!int "7"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Athletics": !!int "5"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Elvish, Undercommon"
"cr": "2"
"traits":
- "desc": "While it has 10 hit points or fewer, Prince Derendil has advantage on attack\
    \ rolls. In addition, it deals an extra 7 (2d6) damage to any target it hits\
    \ with a melee attack."
  "name": "Wounded Fury"
"actions":
- "desc": "Prince Derendil makes two claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Claw"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Prince%20Derendil.webp"
```
^statblock

```encounter-table
name: Prince Derendil
creatures:
 - 1: Prince Derendil
```