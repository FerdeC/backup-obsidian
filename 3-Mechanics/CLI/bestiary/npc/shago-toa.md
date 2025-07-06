---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Shago"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 35
---
# [Shago](2-Mechanics\CLI\bestiary\npc/shago-toa.md)
*Source: Tomb of Annihilation p. 35*  

```statblock
"name": "Shago (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Good"
"ac": !!int "16"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"stats":
- !!int "18"
- !!int "15"
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "15"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
  "Strength": !!int "7"
  "Constitution": !!int "6"
"skillsaves":
  "Intimidation": !!int "5"
  "Athletics": !!int "10"
  "Survival": !!int "7"
"senses": "passive Perception 11"
"languages": "any one language (usually Common)"
"cr": "5"
"traits":
- "desc": "Shago has advantage on saving throws against being [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Brave"
- "desc": "A melee weapon deals one extra die of its damage when Shago hits with it\
    \ (included in the attack)."
  "name": "Brute"
"actions":
- "desc": "Shago makes three melee attacks or two ranged attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. and range 20/60\
    \ ft., one target. Hit: 11 (2d6 + 4) piercing damage, or 13 (2d8 + 4) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Spear"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. Hit: 9\
    \ (2d4 + 4) bludgeoning damage. If the target is a Medium or smaller creature,\
    \ it must succeed on a DC 15 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Shield Bash"
"reactions":
- "desc": "Shago adds 3 to its AC against one melee attack that would hit it. To do\
    \ so, Shago must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Shago.webp"
```
^statblock

```encounter-table
name: Shago
creatures:
 - 1: Shago
```