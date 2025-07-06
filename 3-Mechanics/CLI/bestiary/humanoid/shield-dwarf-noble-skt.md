---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Shield Dwarf Noble"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 78
---
# [Shield Dwarf Noble](2-Mechanics\CLI\bestiary\humanoid/shield-dwarf-noble-skt.md)
*Source: Storm King's Thunder p. 78*  

```statblock
"name": "Shield Dwarf Noble (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Good"
"ac": !!int "15"
"ac_class": "[breastplate](/2-Mechanics/CLI/items/breastplate.md)"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "11"
- !!int "12"
- !!int "11"
- !!int "12"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Insight": !!int "4"
  "Persuasion": !!int "5"
"senses": "passive Perception 12"
"languages": "any two languages"
"cr": "1/8"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d8\
    \ + 1) bludgeoning damage, or 6 (1d10 + 1) bludgeoning damage if used with\
    \ two hands."
  "name": "Warhammer"
"reactions":
- "desc": "The noble adds 2 to its AC against one melee attack that would hit it.\
    \ To do so, the noble must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Shield%20Dwarf%20Noble.webp"
```
^statblock

```encounter-table
name: Shield Dwarf Noble
creatures:
 - 1: Shield Dwarf Noble
```