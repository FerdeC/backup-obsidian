---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/troglodyte
aliases: ["Old Troglodyte"]
NoteIcon: monster
BestiaryType: humanoid (troglodyte)
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 155
---
# [Old Troglodyte](2-Mechanics\CLI\bestiary\humanoid/old-troglodyte-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 155*  

```statblock
"name": "Old Troglodyte (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "troglodyte"
"alignment": "Chaotic Evil"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "13"
"hit_dice": "2d8 + 4"
"stats":
- !!int "14"
- !!int "10"
- !!int "14"
- !!int "6"
- !!int "10"
- !!int "6"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "2"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Troglodyte"
"cr": "1/8"
"traits":
- "desc": "The troglodyte has advantage on Dexterity ([Stealth](/2-Mechanics/CLI/rules/skills.md#Stealth))\
    \ checks made to hide."
  "name": "Chameleon Skin"
- "desc": "Any creature other than a troglodyte that starts its turn within 5 feet\
    \ of the troglodyte must succeed on a DC 12 Constitution saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ until the start of the creature's next turn. On a successful saving throw, the\
    \ creature is immune to the stench of all troglodytes for 1 hour."
  "name": "Stench"
- "desc": "While in sunlight, the troglodyte has disadvantage on attack rolls, as\
    \ well as on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "The troglodyte makes two claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) slashing damage."
  "name": "Claw"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Old%20Troglodyte.webp"
```
^statblock

```encounter-table
name: Old Troglodyte
creatures:
 - 1: Old Troglodyte
```