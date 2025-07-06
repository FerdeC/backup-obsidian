---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Ifan Talro'a"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 25
---
# [Ifan Talro'a](2-Mechanics\CLI\bestiary\npc/ifan-talroa-toa.md)
*Source: Tomb of Annihilation p. 25*  

```statblock
"name": "Ifan Talro'a (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
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
- "desc": "Ifan adds 2 to its AC against one melee attack that would hit it. To do\
    \ so, Ifan must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Ifan%20Talro%27a.webp"
```
^statblock

```encounter-table
name: Ifan Talro'a
creatures:
 - 1: Ifan Talro'a
```