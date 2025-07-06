---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/jttrc
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Vi Aroon"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Journeys through the Radiant Citadel p. 28
---
# [Vi Aroon](2-Mechanics\CLI\bestiary\npc/vi-aroon-jttrc.md)
*Source: Journeys through the Radiant Citadel p. 28*  

```statblock
"name": "Vi Aroon (JttRC)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Good"
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
    \ + 1) piercing damage."
  "name": "Rapier"
"reactions":
- "desc": "Vi adds 2 to its AC against one melee attack that would hit it. To do so,\
    \ Vi must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "JttRC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/JttRC/Vi%20Aroon.webp"
```
^statblock

```encounter-table
name: Vi Aroon
creatures:
 - 1: Vi Aroon
```