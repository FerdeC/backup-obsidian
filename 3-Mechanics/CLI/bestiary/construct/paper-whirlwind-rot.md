---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/rot
- monster/cr/1-4
- monster/size/medium
- monster/type/construct
aliases: ["Paper Whirlwind"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: The Rise of Tiamat p. 72
---
# [Paper Whirlwind](2-Mechanics\CLI\bestiary\construct/paper-whirlwind-rot.md)
*Source: The Rise of Tiamat p. 72*  

```statblock
"name": "Paper Whirlwind (RoT)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "24"
"hit_dice": "7d8 - 7"
"stats":
- !!int "6"
- !!int "14"
- !!int "8"
- !!int "3"
- !!int "12"
- !!int "6"
"speed": "10 ft., fly 50 ft."
"skillsaves":
  "Perception": !!int "5"
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone), [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
  \ [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)"
"senses": "passive Perception 15"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The swarm can occupy another creature's space and vice versa, and the swarm\
    \ can move through any opening large enough for a Tiny raven. The swarm can't\
    \ regain hit points or gain temporary hit points."
  "name": "Swarm"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target in the swarm's\
    \ space. Hit: 7 (2d6) piercing damage, or 3 (1d6) piercing damage if the\
    \ swarm has half of its hit points or fewer."
  "name": "Beaks"
"source":
- "RoT"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/RoT/Paper%20Whirlwind.webp"
```
^statblock

```encounter-table
name: Paper Whirlwind
creatures:
 - 1: Paper Whirlwind
```