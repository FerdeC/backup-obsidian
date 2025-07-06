---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/1-4
- monster/size/medium
- monster/type/humanoid/dwarf
aliases: ["Albino Dwarf Warrior"]
NoteIcon: monster
BestiaryType: humanoid (dwarf)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 210
---
# [Albino Dwarf Warrior](2-Mechanics\CLI\bestiary\humanoid/albino-dwarf-warrior-toa.md)
*Source: Tomb of Annihilation p. 210*  

The albino dwarves of Chult were driven from their subterranean homes by volcanic activity, and those who didn't seek refuge in Port Nyanzaru adapted to living in the jungle. They make armor out of dinosaur hide; shape weapons out of dinosaur bones, flint, and wood; and craft ornate jewelry out of bones, feathers, tusks, and stone beads. Albino dwarves haven't forgotten how to forge metal, but they seldom have the means to do so.

```statblock
"name": "Albino Dwarf Warrior (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "30"
"hit_dice": "4d8 + 12"
"stats":
- !!int "13"
- !!int "13"
- !!int "17"
- !!int "12"
- !!int "14"
- !!int "11"
"speed": "25 ft."
"skillsaves":
  "Stealth": !!int "3"
  "Perception": !!int "4"
  "Survival": !!int "4"
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Dwarvish"
"cr": "1/4"
"traits":
- "desc": "The dwarf has advantage on saving throws against poison."
  "name": "Dwarven Resilience"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d6 + 1) slashing damage."
  "name": "Handaxe"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Albino%20Dwarf%20Warrior.webp"
```
^statblock

```encounter-table
name: Albino Dwarf Warrior
creatures:
 - 1: Albino Dwarf Warrior
```