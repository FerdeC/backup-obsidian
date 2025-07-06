---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Battlehammer Dwarf"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 107
---
# [Battlehammer Dwarf](2-Mechanics\CLI\bestiary\humanoid/battlehammer-dwarf-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 107*  

```statblock
"name": "Battlehammer Dwarf (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Good"
"ac": !!int "13"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"stats":
- !!int "11"
- !!int "14"
- !!int "12"
- !!int "11"
- !!int "13"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Nature": !!int "4"
  "Stealth": !!int "6"
  "Perception": !!int "5"
  "Survival": !!int "5"
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "any one language (usually Common), Dwarvish"
"cr": "1/2"
"traits":
- "desc": "The dwarf has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or sight."
  "name": "Keen Hearing and Sight"
- "desc": "The battlehammer dwarf"
  "name": "Dwarven Resilience"
"actions":
- "desc": "The dwarf makes two melee attacks or two ranged attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +2 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 3 (1d6 + 0) slashing damage."
  "name": "Handaxe"
- "desc": "Ranged Weapon Attack: +4 to hit, ranged 80/320 ft., one target. Hit:\
    \ 6 (1d8 + 2) piercing damage."
  "name": "Light Crossbow"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Battlehammer%20Dwarf.webp"
```
^statblock

```encounter-table
name: Battlehammer Dwarf
creatures:
 - 1: Battlehammer Dwarf
```