---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/jttrc
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Kusa Xungoon"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Journeys through the Radiant Citadel p. 20
---
# [Kusa Xungoon](2-Mechanics\CLI\bestiary\npc/kusa-xungoon-jttrc.md)
*Source: Journeys through the Radiant Citadel p. 20*  

```statblock
"name": "Kusa Xungoon (JttRC)"
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
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "any two languages, Draconic"
"cr": "1/8"
"traits":
- "desc": "Kusa"
  "name": "Sunlight Sensitivity"
- "desc": "Kusa"
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d8\
    \ + 1) piercing damage."
  "name": "Rapier"
"reactions":
- "desc": "Kusa adds 2 to its AC against one melee attack that would hit it. To do\
    \ so, Kusa must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "JttRC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/JttRC/Kusa%20Xungoon.webp"
```
^statblock

```encounter-table
name: Kusa Xungoon
creatures:
 - 1: Kusa Xungoon
```