---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Eldeth Feldrun"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Out of the Abyss p. 6
---
# [Eldeth Feldrun](2-Mechanics\CLI\bestiary\npc/eldeth-feldrun-oota.md)
*Source: Out of the Abyss p. 6*  

```statblock
"name": "Eldeth Feldrun (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
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
- "desc": "Eldeth has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or sight."
  "name": "Keen Hearing and Sight"
- "desc": "Eldeth"
  "name": "Dwarven Resilience"
"actions":
- "desc": "Eldeth makes two melee attacks or two ranged attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +4 to hit, ranged 150/600 ft., one target. Hit:\
    \ 6 (1d8 + 2) piercing damage."
  "name": "Longbow"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Eldeth%20Feldrun.webp"
```
^statblock

```encounter-table
name: Eldeth Feldrun
creatures:
 - 1: Eldeth Feldrun
```