---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/1-4
- monster/size/medium
- monster/type/humanoid/troglodyte
aliases: ["Kol'daan"]
NoteIcon: monster
BestiaryType: humanoid (troglodyte)
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 155
---
# [Kol'daan](2-Mechanics\CLI\bestiary\npc/koldaan-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 155*  

```statblock
"name": "Kol'daan (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "troglodyte"
"alignment": "Chaotic Evil"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "20"
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
"cr": "1/4"
"traits":
- "desc": "Kol'daan has advantage on Dexterity ([Stealth](/2-Mechanics/CLI/rules/skills.md#Stealth))\
    \ checks made to hide."
  "name": "Chameleon Skin"
- "desc": "Any creature other than a troglodyte that starts its turn within 5 feet\
    \ of Kol'daan must succeed on a DC 12 Constitution saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ until the start of the creature's next turn. On a successful saving throw, the\
    \ creature is immune to the stench of all troglodytes for 1 hour."
  "name": "Stench"
- "desc": "While in sunlight, Kol'daan has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Kol'daan makes three attacks: one with its bite and two with its claws\
    \ or sparring sword."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) slashing damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d4\
    \ + 2) bludgeoning damage."
  "name": "Sparring Sword"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Kol%27daan.webp"
```
^statblock

```encounter-table
name: Kol'daan
creatures:
 - 1: Kol'daan
```