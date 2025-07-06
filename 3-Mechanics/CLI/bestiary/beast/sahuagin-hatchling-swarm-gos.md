---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/3
- monster/size/large
- monster/type/beast
aliases: ["Sahuagin Hatchling Swarm"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 250
---
# [Sahuagin Hatchling Swarm](2-Mechanics\CLI\bestiary\beast/sahuagin-hatchling-swarm-gos.md)
*Source: Ghosts of Saltmarsh p. 250*  

Roiling through the waters in The Final Enemy, these swarms of sahuagin hatchlings are dangerous to any creatures they encounter. Other sahuagin avoid the swarms, while the individual members devour one another until only the strongest hatchlings are left alive to grow to maturity.

```statblock
"name": "Sahuagin Hatchling Swarm (GoS)"
"size": "Large"
"type": "beast"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"hp": !!int "52"
"hit_dice": "8d10 + 8"
"stats":
- !!int "9"
- !!int "18"
- !!int "12"
- !!int "3"
- !!int "10"
- !!int "3"
"speed": "0 ft., swim 40 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone), [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
  \ [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": ""
"cr": "3"
"traits":
- "desc": "The swarm has advantage on melee attack rolls against any creature that\
    \ doesn't have all its hit points."
  "name": "Blood Frenzy"
- "desc": "Once it enters combat, the swarm deals 10 slashing damage to itself at\
    \ the end of its turn if it did not make an attack on that turn. This damage ignores\
    \ resistance, and it cannot reduce the swarm to 0 hit points."
  "name": "Seething"
- "desc": "The swarm can occupy another creature's space and vice versa, and it can\
    \ move through any opening large enough for a Tiny creature. The swarm can't regain\
    \ hit points or gain temporary hit points."
  "name": "Swarm"
- "desc": "The swarm can breathe only underwater."
  "name": "Water Breathing"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 0 ft., one creature in the swarm's\
    \ space. Hit: 14 (4d6) piercing damage, or 7 (2d6) piercing damage if the\
    \ swarm has half of its hit points or fewer."
  "name": "Bites"
"source":
- "GoS"
- "LR"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Sahuagin%20Hatchling%20Swarm.webp"
```
^statblock

```encounter-table
name: Sahuagin Hatchling Swarm
creatures:
 - 1: Sahuagin Hatchling Swarm
```