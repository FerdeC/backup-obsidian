---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/1
- monster/size/medium
- monster/type/undead
aliases: ["Lacedon"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 147
---
# [Lacedon](2-Mechanics\CLI\bestiary\undead/lacedon-tftyp.md)
*Source: Tales from the Yawning Portal p. 147*  

```statblock
"name": "Lacedon (TftYP)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "5d8"
"stats":
- !!int "13"
- !!int "15"
- !!int "10"
- !!int "7"
- !!int "10"
- !!int "6"
"speed": "30 ft., swim 30 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common"
"cr": "1"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one creature. Hit: 9\
    \ (2d6 + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (2d4\
    \ + 2) slashing damage. If the target is a creature other than an elf or undead,\
    \ it must succeed on a DC 10 Constitution saving throw or be [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed)\
    \ for 1 minute. The target can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success."
  "name": "Claws"
"source":
- "TftYP"
- "EGW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Lacedon.webp"
```
^statblock

```encounter-table
name: Lacedon
creatures:
 - 1: Lacedon
```