---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/8
- monster/size/large
- monster/type/giant
aliases: ["Five-Armed Troll"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 154
---
# [Five-Armed Troll](2-Mechanics\CLI\bestiary\giant/five-armed-troll-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 154*  

```statblock
"name": "Five-Armed Troll (WDMM)"
"size": "Large"
"type": "giant"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "84"
"hit_dice": "8d10 + 40"
"stats":
- !!int "18"
- !!int "13"
- !!int "20"
- !!int "7"
- !!int "9"
- !!int "7"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Giant"
"cr": "8"
"traits":
- "desc": "The troll has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "The troll regains 10 hit points at the start of its turn. If the troll\
    \ takes acid or fire damage, this trait doesn't function at the start of the troll's\
    \ next turn. The troll dies only if it starts its turn with 0 hit points and doesn't\
    \ regenerate."
  "name": "Regeneration"
"actions":
- "desc": "The troll makes six attacks: one with its bite and five with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) slashing damage."
  "name": "Claw"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Five-Armed%20Troll.webp"
```
^statblock

```encounter-table
name: Five-Armed Troll
creatures:
 - 1: Five-Armed Troll
```