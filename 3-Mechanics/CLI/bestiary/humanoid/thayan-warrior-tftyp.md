---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Thayan Warrior"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 246
---
# [Thayan Warrior](2-Mechanics\CLI\bestiary\humanoid/thayan-warrior-tftyp.md)
*Source: Tales from the Yawning Portal p. 246*  

```statblock
"name": "Thayan Warrior (TftYP)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Any Non-Good alignment"
"ac": !!int "16"
"ac_class": "[chain shirt](/2-Mechanics/CLI/items/chain-shirt.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "16"
- !!int "13"
- !!int "14"
- !!int "10"
- !!int "11"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "Common, Thayan"
"cr": "2"
"traits":
- "desc": "Within the Doomvault, the warrior has advantage on saving throws against\
    \ being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed) or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Doomvault Devotion"
- "desc": "The warrior has advantage on an attack roll against a creature if at least\
    \ one of the warrior's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "The warrior makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands."
  "name": "Longsword"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 6 (1d6 + 3) piercing damage."
  "name": "Javelin"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Thayan%20Warrior.webp"
```
^statblock

```encounter-table
name: Thayan Warrior
creatures:
 - 1: Thayan Warrior
```