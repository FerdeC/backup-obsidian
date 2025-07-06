---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/1-4
- monster/size/medium
- monster/type/construct
aliases: ["Animated Jade Serpent"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 92
---
# [Animated Jade Serpent](2-Mechanics\CLI\bestiary\construct/animated-jade-serpent-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 92*  

```statblock
"name": "Animated Jade Serpent (WDMM)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "14"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "10"
- !!int "18"
- !!int "13"
- !!int "2"
- !!int "10"
- !!int "3"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Perception": !!int "2"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 10 ft., passive Perception 12"
"languages": ""
"cr": "1/4"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 6\
    \ (1d4 + 4) piercing damage, and the target must make a DC 11 Constitution saving\
    \ throw, taking 10 (3d6) poison damage on a failed save, or half as much damage\
    \ on a successful one."
  "name": "Bite"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Animated%20Jade%20Serpent.webp"
```
^statblock

```encounter-table
name: Animated Jade Serpent
creatures:
 - 1: Animated Jade Serpent
```