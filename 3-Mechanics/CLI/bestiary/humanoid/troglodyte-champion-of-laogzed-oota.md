---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/troglodyte
aliases: ["Troglodyte Champion of Laogzed"]
NoteIcon: monster
BestiaryType: humanoid (troglodyte)
SourceType: Bestiary
BookSource: Out of the Abyss p. 229
---
# [Troglodyte Champion of Laogzed](2-Mechanics\CLI\bestiary\humanoid/troglodyte-champion-of-laogzed-oota.md)
*Source: Out of the Abyss p. 229*  

The Monster Manual provides statistics for the typical troglodyte. Once in a while, a troglodyte tribe produces an unusually smart and strong specimen that can spew acid-what many troglodytes consider blessings from Laogzed, their demonic god. These hulking troglodyte champions make excellent chieftains.

```statblock
"name": "Troglodyte Champion of Laogzed (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "troglodyte"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "59"
"hit_dice": "7d8 + 28"
"stats":
- !!int "18"
- !!int "12"
- !!int "18"
- !!int "8"
- !!int "12"
- !!int "12"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "3"
  "Athletics": !!int "6"
  "Stealth": !!int "3"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Troglodyte"
"cr": "3"
"traits":
- "desc": "The troglodyte has advantage on Dexterity ([Stealth](/2-Mechanics/CLI/rules/skills.md#Stealth))\
    \ checks made to hide."
  "name": "Chameleon Skin"
- "desc": "Any creature other than a troglodyte that starts its turn within 5 feet\
    \ of the troglodyte must succeed on a DC 14 Constitution saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ until the start of the creature's next turn. On a successful saving throw, the\
    \ creature is immune to the stench of all troglodytes for 1 hour."
  "name": "Stench"
- "desc": "While in sunlight, the troglodyte has disadvantage on attack rolls, as\
    \ well as on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "The troglodyte makes three attacks: one with its bite and two with either\
    \ its claws or its greatclub."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d4\
    \ + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d4\
    \ + 4) slashing damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) bludgeoning damage."
  "name": "Greatclub"
- "desc": "The troglodyte spits acid in a line 15 feet long and 5 feet wide. Each\
    \ creature in that line must make a DC 14 Dexterity saving throw, taking 10 (3d6)\
    \ acid damage on a failed save, or half as much damage on a successful one."
  "name": "Acid Spray (Recharge 6)"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Troglodyte%20Champion%20of%20Laogzed.webp"
```
^statblock

```encounter-table
name: Troglodyte Champion of Laogzed
creatures:
 - 1: Troglodyte Champion of Laogzed
```