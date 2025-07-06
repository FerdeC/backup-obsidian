---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/dwarf
aliases: ["Musharib"]
NoteIcon: monster
BestiaryType: humanoid (dwarf)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 34
---
# [Musharib](2-Mechanics\CLI\bestiary\npc/musharib-toa.md)
*Source: Tomb of Annihilation p. 34*  

```statblock
"name": "Musharib (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Lawful Good"
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
"cr": "1"
"traits":
- "desc": "Musharib's innate spellcasting ability is Wisdom. It can innately cast\
    \ the following spells, requiring no material components:\n\n1/day each: [hunter's\
    \ mark](/2-Mechanics/CLI/spells/hunters-mark.md), [jump](/2-Mechanics/CLI/spells/jump.md),\
    \ [pass without trace](/2-Mechanics/CLI/spells/pass-without-trace.md), [speak\
    \ with animals](/2-Mechanics/CLI/spells/speak-with-animals.md), [speak with plants](/2-Mechanics/CLI/spells/speak-with-plants.md)"
  "name": "Innate Spellcasting"
- "desc": "Musharib has advantage on saving throws against poison."
  "name": "Dwarven Resilience"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d6 + 1) slashing damage."
  "name": "Handaxe"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Musharib.webp"
```
^statblock

```encounter-table
name: Musharib
creatures:
 - 1: Musharib
```