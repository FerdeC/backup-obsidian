---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wbtw
- monster/cr/1
- monster/size/large
- monster/type/beast
aliases: ["Giant Swan"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: The Wild Beyond the Witchlight p. 38
---
# [Giant Swan](2-Mechanics\CLI\bestiary\beast/giant-swan-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 38*  

```statblock
"name": "Giant Swan (WBtW)"
"size": "Large"
"type": "beast"
"alignment": "Neutral Good"
"ac": !!int "13"
"hp": !!int "26"
"hit_dice": "4d10 + 4"
"stats":
- !!int "16"
- !!int "17"
- !!int "13"
- !!int "8"
- !!int "14"
- !!int "10"
"speed": "10 ft., fly 80 ft."
"skillsaves":
  "Perception": !!int "4"
"senses": "passive Perception 14"
"languages": "Auran, Common"
"cr": "1"
"traits":
- "desc": "The swan has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on sight."
  "name": "Keen Sight"
"actions":
- "desc": "The swan makes two attacks with its beak."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Beak"
"source":
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WBtW/Giant%20Swan.webp"
```
^statblock

```encounter-table
name: Giant Swan
creatures:
 - 1: Giant Swan
```