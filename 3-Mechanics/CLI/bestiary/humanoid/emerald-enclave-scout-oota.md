---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/dwarf
aliases: ["Emerald Enclave Scout"]
NoteIcon: monster
BestiaryType: humanoid (dwarf)
SourceType: Bestiary
BookSource: Out of the Abyss p. 130
---
# [Emerald Enclave Scout](2-Mechanics\CLI\bestiary\humanoid/emerald-enclave-scout-oota.md)
*Source: Out of the Abyss p. 130*  

```statblock
"name": "Emerald Enclave Scout (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Lawful Neutral"
"ac": !!int "16"
"ac_class": "[breastplate](/2-Mechanics/CLI/items/breastplate.md)"
"hp": !!int "19"
"hit_dice": "3d8 + 6"
"stats":
- !!int "11"
- !!int "14"
- !!int "14"
- !!int "11"
- !!int "13"
- !!int "11"
"speed": "25 ft."
"skillsaves":
  "Nature": !!int "4"
  "Stealth": !!int "6"
  "Perception": !!int "5"
  "Survival": !!int "5"
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common, Dwarvish"
"cr": "1/2"
"traits":
- "desc": "The scout has advantage on saving throws against poison."
  "name": "Dwarven Resilience"
- "desc": "The scout has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or sight."
  "name": "Keen Hearing and Sight"
"actions":
- "desc": "The scout makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) piercing damage."
  "name": "War Pick"
- "desc": "Ranged Weapon Attack: +3 to hit, range 100/400 ft., one target. Hit:\
    \ 5 (1d10) piercing damage."
  "name": "Heavy Crossbow"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Emerald%20Enclave%20Scout.webp"
```
^statblock

```encounter-table
name: Emerald Enclave Scout
creatures:
 - 1: Emerald Enclave Scout
```