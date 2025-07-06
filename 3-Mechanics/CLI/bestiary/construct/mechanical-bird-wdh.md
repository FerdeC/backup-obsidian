---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/unknown
- monster/size/tiny
- monster/type/construct
aliases: ["Mechanical Bird"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 46
---
# [Mechanical Bird](2-Mechanics\CLI\bestiary\construct/mechanical-bird-wdh.md)
*Source: Waterdeep: Dragon Heist p. 46*  

```statblock
"name": "Mechanical Bird (WDH)"
"size": "Tiny"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "15"
"hp": !!int "1"
"stats":
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
"speed": "fly 60 ft."
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "passive Perception 10"
"languages": ""
"cr": "Unknown"
"actions":
- "desc": "Melee Weapon Attack: +0 to hit, reach 5 ft., one target. Hit: 2 (1d3)\
    \ piercing damage, and the bird is destroyed by the impact."
  "name": "Slam"
"source":
- "WDH"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDH/Mechanical%20Bird.webp"
```
^statblock

```encounter-table
name: Mechanical Bird
creatures:
 - 1: Mechanical Bird
```