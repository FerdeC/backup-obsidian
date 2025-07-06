---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/1-4
- monster/size/medium
- monster/type/undead
aliases: ["Frody Dartwild"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 105
---
# [Frody Dartwild](2-Mechanics\CLI\bestiary\npc/frody-dartwild-kftgv.md)
*Source: Keys from the Golden Vault p. 105*  

```statblock
"name": "Frody Dartwild (KftGV)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Good"
"ac": !!int "8"
"hp": !!int "22"
"hit_dice": "3d8 + 9"
"stats":
- !!int "13"
- !!int "6"
- !!int "16"
- !!int "10"
- !!int "6"
- !!int "5"
"speed": "20 ft."
"saves":
  "Wisdom": !!int "0"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 8"
"languages": "Common"
"cr": "1/4"
"traits":
- "desc": "If damage reduces Frody to 0 hit points, it must make a Constitution saving\
    \ throw with a DC of 5 + the damage taken, unless the damage is radiant or from\
    \ a critical hit. On a success, Frody drops to 1 hit point instead."
  "name": "Undead Fortitude"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) bludgeoning damage."
  "name": "Slam"
"source":
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/KftGV/Frody%20Dartwild.webp"
```
^statblock

```encounter-table
name: Frody Dartwild
creatures:
 - 1: Frody Dartwild
```