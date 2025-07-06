---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/1-4
- monster/size/medium
- monster/type/undead
aliases: ["Skeletal Rats"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 23
---
# [Skeletal Rats](2-Mechanics\CLI\bestiary\undead/skeletal-rats-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 23*  

```statblock
"name": "Skeletal Rats (BGDIA)"
"size": "Medium"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "24"
"hit_dice": "7d8 - 7"
"stats":
- !!int "9"
- !!int "11"
- !!int "9"
- !!int "2"
- !!int "10"
- !!int "3"
"speed": "30 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone), [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
  \ [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)"
"senses": "darkvision 30 ft., passive Perception 10"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The swarm has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "The swarm can occupy another creature's space and vice versa, and the swarm\
    \ can move through any opening large enough for a Tiny rat. The swarm can't regain\
    \ hit points or gain temporary hit points."
  "name": "Swarm"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 0 ft., one target in the swarm's\
    \ space. Hit: 7 (2d6) piercing damage, or 3 (1d6) piercing damage if the\
    \ swarm has half of its hit points or fewer."
  "name": "Bites"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Skeletal%20Rats.webp"
```
^statblock

```encounter-table
name: Skeletal Rats
creatures:
 - 1: Skeletal Rats
```