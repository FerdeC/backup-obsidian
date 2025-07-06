---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/1-2
- monster/size/medium
- monster/type/undead
aliases: ["Skeletal Alchemist"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 253
---
# [Skeletal Alchemist](2-Mechanics\CLI\bestiary\undead/skeletal-alchemist-gos.md)
*Source: Ghosts of Saltmarsh p. 253*  

This undead retains enough of its former self to continue its alchemical work, often on behalf of necromancers or other sinister patrons. It toils in a dark laboratory (such as the one found in The Sinister Secret of Saltmarsh), often falling dormant for long periods of time.

```statblock
"name": "Skeletal Alchemist (GoS)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "11"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"stats":
- !!int "9"
- !!int "13"
- !!int "15"
- !!int "14"
- !!int "10"
- !!int "9"
"speed": "30 ft."
"skillsaves":
  "Arcana": !!int "4"
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands all languages it knew in life but can't speak"
"cr": "1/2"
"traits":
- "desc": "The skeletal alchemist has advantage on saving throws against spells and\
    \ other magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The skeletal alchemist makes two Lob Acid attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft. one target. Hit: 4 (1d6\
    \ + 1) slashing damage."
  "name": "Claws"
- "desc": "Ranged Weapon Attack: +3 to hit, range 30/120 ft., one target. Hit:\
    \ 5 (1d8 + 1) acid damage."
  "name": "Lob Acid"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Skeletal%20Alchemist.webp"
```
^statblock

```encounter-table
name: Skeletal Alchemist
creatures:
 - 1: Skeletal Alchemist
```