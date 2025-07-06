---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wbtw
- monster/cr/1-2
- monster/size/large
- monster/type/beast
aliases: ["Giant Dragonfly"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: The Wild Beyond the Witchlight p. 234
---
# [Giant Dragonfly](2-Mechanics\CLI\bestiary\beast/giant-dragonfly-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 234*  

A giant dragonfly has a 20-foot wingspan. It drones loudly as it hovers and darts through the air, searching for smaller insects to consume.

```statblock
"name": "Giant Dragonfly (WBtW)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "22"
"hit_dice": "4d10"
"stats":
- !!int "15"
- !!int "18"
- !!int "11"
- !!int "3"
- !!int "10"
- !!int "3"
"speed": "10 ft., fly 60 ft."
"senses": "passive Perception 10"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "When it beats its wings, the dragonfly emits a loud droning sound that\
    \ can be heard out to a range of 120 feet."
  "name": "Drone"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d4\
    \ + 4) piercing damage."
  "name": "Bite"
"reactions":
- "desc": "The dragonfly halves the damage it takes from an attack made against it,\
    \ provided it can see the attacker."
  "name": "Uncanny Dodge"
"source":
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WBtW/Giant%20Dragonfly.webp"
```
^statblock

```encounter-table
name: Giant Dragonfly
creatures:
 - 1: Giant Dragonfly
```