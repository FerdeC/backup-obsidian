---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/jttrc
- monster/cr/1-4
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Tungsten Ward"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Journeys through the Radiant Citadel p. 38
---
# [Tungsten Ward](2-Mechanics\CLI\bestiary\npc/tungsten-ward-jttrc.md)
*Source: Journeys through the Radiant Citadel p. 38*  

```statblock
"name": "Tungsten Ward (JttRC)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Good"
"ac": !!int "10"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "14"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Medicine": !!int "4"
  "Religion": !!int "2"
"senses": "passive Perception 12"
"languages": "any one language (usually Common)"
"cr": "1/4"
"traits":
- "desc": "Tungsten is a 1st-level spellcaster. Its spellcasting ability is Wisdom\
    \ (spell save DC 12, +4 to hit with spell attacks). Tungsten has following cleric\
    \ spells prepared:\n\nCantrips (at will): [light](/2-Mechanics/CLI/spells/light.md),\
    \ [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1st level (3 slots): [bless](/2-Mechanics/CLI/spells/bless.md), [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md),\
    \ [sanctuary](/2-Mechanics/CLI/spells/sanctuary.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d4)\
    \ bludgeoning damage."
  "name": "Club"
"source":
- "JttRC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/JttRC/Tungsten%20Ward.webp"
```
^statblock

```encounter-table
name: Tungsten Ward
creatures:
 - 1: Tungsten Ward
```