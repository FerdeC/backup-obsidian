---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/rot
- monster/cr/5
- monster/size/large
- monster/type/giant
aliases: ["Ice Troll"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: The Rise of Tiamat p. 30
---
# [Ice Troll](2-Mechanics\CLI\bestiary\giant/ice-troll-rot.md)
*Source: The Rise of Tiamat p. 30*  

```statblock
"name": "Ice Troll (RoT)"
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
"damage_resistances": "cold"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Giant"
"cr": "5"
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
- "desc": "The troll makes three attacks: one with its bite and two with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) slashing damage."
  "name": "Claw"
"source":
- "RoT"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/RoT/Ice%20Troll.webp"
```
^statblock

```encounter-table
name: Ice Troll
creatures:
 - 1: Ice Troll
```