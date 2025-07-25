---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/3
- monster/size/huge
- monster/type/undead
aliases: ["Thunderbeast Skeleton"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Storm King's Thunder p. 99
---
# [Thunderbeast Skeleton](2-Mechanics\CLI\bestiary\undead/thunderbeast-skeleton-skt.md)
*Source: Storm King's Thunder p. 99*  

```statblock
"name": "Thunderbeast Skeleton (SKT)"
"size": "Huge"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "68"
"hit_dice": "8d12 + 16"
"stats":
- !!int "19"
- !!int "11"
- !!int "15"
- !!int "2"
- !!int "12"
- !!int "5"
"speed": "30 ft."
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": ""
"cr": "3"
"actions":
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., Hit: 18 (4d6 + 4)\
    \ piercing damage."
  "name": "Bite"
- "desc": "+7 to hit, reach 10 ft., one target. Hit: 18 (4d6 + 4) bludgeoning\
    \ damage. Succeed on a DC14 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Tail"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Thunderbeast%20Skeleton.webp"
```
^statblock

```encounter-table
name: Thunderbeast Skeleton
creatures:
 - 1: Thunderbeast Skeleton
```