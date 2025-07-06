---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/1-4
- monster/size/medium
- monster/type/humanoid/troglodyte
aliases: ["Gorzil's Gang Troglodyte"]
NoteIcon: monster
BestiaryType: humanoid (troglodyte)
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 150
---
# [Gorzil's Gang Troglodyte](2-Mechanics\CLI\bestiary\humanoid/gorzils-gang-troglodyte-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 150*  

```statblock
"name": "Gorzil's Gang Troglodyte (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "troglodyte"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "[breastplate](/2-Mechanics/CLI/items/breastplate.md)"
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
"languages": "understands Undercommon but can't speak"
"cr": "1/4"
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
- "desc": "The troglodyte makes three attacks: one with its bite and two with its\
    \ longsword."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with two hands."
  "name": "Longsword"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Gorzil%27s%20Gang%20Troglodyte.webp"
```
^statblock

```encounter-table
name: Gorzil's Gang Troglodyte
creatures:
 - 1: Gorzil's Gang Troglodyte
```