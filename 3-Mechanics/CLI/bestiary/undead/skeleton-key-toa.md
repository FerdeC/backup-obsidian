---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/1-4
- monster/size/medium
- monster/type/undead
aliases: ["Skeleton Key"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 126
---
# [Skeleton Key](2-Mechanics\CLI\bestiary\undead/skeleton-key-toa.md)
*Source: Tomb of Annihilation p. 126*  

```statblock
"name": "Skeleton Key (ToA)"
"size": "Medium"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "armor scraps"
"hp": !!int "13"
"hit_dice": "2d8 + 4"
"stats":
- !!int "10"
- !!int "14"
- !!int "15"
- !!int "6"
- !!int "8"
- !!int "5"
"speed": "30 ft., climb 30 ft."
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "understands all languages it spoke in life but can't speak"
"cr": "1/4"
"traits":
- "desc": "The skeleton can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "The skeleton makes two dagger attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage."
  "name": "Dagger"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Skeleton%20Key.webp"
```
^statblock

```encounter-table
name: Skeleton Key
creatures:
 - 1: Skeleton Key
```