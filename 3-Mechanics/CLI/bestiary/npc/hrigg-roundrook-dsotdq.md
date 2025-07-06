---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/
- monster/size/medium
- monster/type/humanoid/dwarf
aliases: ["Hrigg Roundrook"]
NoteIcon: monster
BestiaryType: humanoid (dwarf)
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 211
---
# [Hrigg Roundrook](2-Mechanics\CLI\bestiary\npc/hrigg-roundrook-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 211*  

[Hrigg](/2-Mechanics/CLI/bestiary/npc/hrigg-roundrook-dsotdq.md) is a gregarious dwarf who laughs heartily and lives to feast on the finest food and fight the vilest evil. He is one of five siblings, each of whom were chosen by Kiri-Jolith, the god of war, to receive his divine power. From their homeland of Kayolin, the five siblings each set out on their own path to bring Kiri-Jolith's message directly to the Dragon Armies. Hrigg's path brought him to Kalaman, where he happily finds himself on the front line of an invasion.

```statblock
"name": "Hrigg Roundrook (DSotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Lawful Good"
"ac": !!int "16"
"ac_class": "[half plate](/2-Mechanics/CLI/items/half-plate-armor.md)"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "14"
- !!int "12"
- !!int "12"
- !!int "10"
- !!int "14"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
"skillsaves":
  "Medicine": !!int "4"
  "Athletics": !!int "4"
  "Perception": !!int "4"
  "History": !!int "2"
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Dwarvish"
"traits":
- "desc": "Hrigg's spellcasting ability is Wisdom (spell save DC 12, +4 to hit with\
    \ spell attacks). He has the following cleric spells prepared:\n\nAt will:\
    \ [guidance](/2-Mechanics/CLI/spells/guidance.md), [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md)\n\
    \n1st level (2 slots): [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md)"
  "name": "Spellcasting"
- "desc": "Hrigg is proficient with simple and martial weapons and light and medium\
    \ armor."
  "name": "Bonus Proficiencies"
- "desc": "Hrigg has advantage on saving throws made to avoid or end the [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ condition on himself."
  "name": "Dwarven Resilience"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 9 (2d6\
    \ + 2) bludgeoning damage."
  "name": "Maul"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Hrigg%20Roundrook.webp"
```
^statblock

```encounter-table
name: Hrigg Roundrook
creatures:
 - 1: Hrigg Roundrook
```