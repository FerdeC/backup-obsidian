---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/2
- monster/size/large
- monster/type/undead
aliases: ["Skeletal Swarm"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 254
---
# [Skeletal Swarm](2-Mechanics\CLI\bestiary\undead/skeletal-swarm-gos.md)
*Source: Ghosts of Saltmarsh p. 254*  

This swarm of bones found rising out of the sand in Isle of the Abbey is made from the remains of several animated skeletons. A skeletal swarm alternates its appearance between partially formed humanoid shapes and a chaotic, swirling mass.

```statblock
"name": "Skeletal Swarm (GoS)"
"size": "Large"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "13"
"ac_class": "armor scraps"
"hp": !!int "60"
"hit_dice": "8d10 + 16"
"stats":
- !!int "12"
- !!int "14"
- !!int "15"
- !!int "6"
- !!int "8"
- !!int "5"
"speed": "30 ft."
"damage_vulnerabilities": "bludgeoning"
"damage_resistances": "slashing, piercing"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned), [prone](/2-Mechanics/CLI/rules/conditions.md#prone),\
  \ [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained), [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": ""
"cr": "2"
"traits":
- "desc": "Creatures are [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened)\
    \ while in the swarm's space."
  "name": "Deafening Clatter"
- "desc": "The swarm can occupy another creature's space and vice versa, and the swarm\
    \ can move through any opening large enough for a Small humanoid. The swarm can't\
    \ regain hit points or gain temporary hit points."
  "name": "Swarm"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 0 ft., one target in the swarm's\
    \ space. Hit: 11 (2d8 + 2) slashing damage, or 6 (1d8 + 2) slashing damage\
    \ if the swarm has half of its hit points or fewer."
  "name": "Slash"
"source":
- "GoS"
- "DC"
- "IMR"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Skeletal%20Swarm.webp"
```
^statblock

```encounter-table
name: Skeletal Swarm
creatures:
 - 1: Skeletal Swarm
```