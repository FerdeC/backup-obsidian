---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/ftd
- monster/cr/2
- monster/size/medium
- monster/type/monstrosity
aliases: ["Draconian Mage"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Fizban's Treasury of Dragons p. 179
---
# [Draconian Mage](2-Mechanics\CLI\bestiary\monstrosity/draconian-mage-ftd.md)
*Source: Fizban's Treasury of Dragons p. 179*  

Draconians born from the eggs of bronze, green, and emerald dragons have some ability to wield magic. They often lead small groups of draconian foot soldiers, using their magic to snipe across the battlefield or aid their allies' incursions and attacks. They have wings that allow them to glide during a fall.

When draconian mages die, their flesh shrivels away before their bones explode, sending a shower of magical splinters in all directions.

On the world of Krynn, draconian mages formed from bronze dragon eggs are called bozak draconians.

## Draconians

Draconians are bipedal monsters born from dragon eggs that have been corrupted or warped by powerful magic. Most often, this corruption is a deliberate act, the work of an aspiring tyrant seeking to transform stolen eggs into a draconian army. A single corrupted egg yields several draconians of the same kind. A draconian might be taken for a dragonborn at first glance, though most kinds of draconians have wings.

When draconians die, they do not go quietly. Instead, their lifeless bodies unleash a last act of magical violence.

```statblock
"name": "Draconian Mage (FTD)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "40"
"hit_dice": "9d8"
"stats":
- !!int "14"
- !!int "10"
- !!int "11"
- !!int "11"
- !!int "10"
- !!int "14"
"speed": "30 ft."
"saves":
  "Charisma": !!int "4"
  "Wisdom": !!int "2"
  "Intelligence": !!int "2"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Draconic"
"cr": "2"
"traits":
- "desc": "The draconian casts one of the following spells, requiring no material\
    \ components and using Charisma as the spellcasting ability (spell save DC 12):\n\
    \n1/day each: [enlarge/reduce](/2-Mechanics/CLI/spells/enlarge-reduce.md),\
    \ [invisibility](/2-Mechanics/CLI/spells/invisibility.md), [stinking cloud](/2-Mechanics/CLI/spells/stinking-cloud.md)"
  "name": "Spellcasting"
- "desc": "When the draconian is reduced to 0 hit points, its scales and flesh immediately\
    \ shrivel away and its bones explode. Each creature within 10 feet of it must\
    \ succeed on a DC 10 Dexterity saving throw or take 9 (2d8) force damage."
  "name": "Death Throes"
- "desc": "When the draconian falls and isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated),\
    \ it subtracts up to 100 feet from the fall when calculating the fall's damage,\
    \ and it can move up to 2 feet horizontally for every 1 foot it descends."
  "name": "Glide"
"actions":
- "desc": "The draconian makes two Trident or Necrotic Ray attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Trident"
- "desc": "Ranged Spell Attack: +4 to hit, range 60 ft., one target. Hit: 10\
    \ (3d6) necrotic damage."
  "name": "Necrotic Ray"
"source":
- "FTD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/FTD/Draconian%20Mage.webp"
```
^statblock

```encounter-table
name: Draconian Mage
creatures:
 - 1: Draconian Mage
```