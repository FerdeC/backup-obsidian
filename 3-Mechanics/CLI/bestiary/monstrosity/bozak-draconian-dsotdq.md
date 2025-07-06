---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/2
- monster/size/medium
- monster/type/monstrosity/sorcerer
aliases: ["Bozak Draconian"]
NoteIcon: monster
BestiaryType: monstrosity (sorcerer)
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 198
---
# [Bozak Draconian](2-Mechanics\CLI\bestiary\monstrosity/bozak-draconian-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 198*  

Bozak draconians are born from bronze dragon eggs and wield magic to aid their allies in battle. Their wings aren't strong enough for full flight, but bozaks can use them to glide during a fall. When bozaks die, their flesh shrivels away before their bones explode, sending a shower of magical splinters in all directions.

## Draconians

Draconians are bipedal monsters born from metallic dragon eggs that have been corrupted by a combination of warped alchemy and the Dragon Queen's foul magic. The Dragon Armies closely guard the secret of the draconians' creation, allowing Krynn's metallic dragons to continue to think their eggs are being held hostage so they don't oppose the Dragon Queen's conquests.

```statblock
"name": "Bozak Draconian (DSotDQ)"
"size": "Medium"
"type": "monstrosity"
"subtype": "sorcerer"
"alignment": "typically  Lawful Evil"
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
    \ [invisibility](/2-Mechanics/CLI/spells/invisibility.md), [stinking cloud](/2-Mechanics/CLI/spells/stinking-cloud.md),\
    \ [web](/2-Mechanics/CLI/spells/web.md)"
  "name": "Spellcasting"
- "desc": "When the draconian is reduced to 0 hit points, its scales and flesh immediately\
    \ shrivel away, and then its bones explode. Each creature within 10 feet of it\
    \ must succeed on a DC 10 Dexterity saving throw or take 9 (2d8) force damage."
  "name": "Death Throes"
- "desc": "When the draconian falls and isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated),\
    \ it subtracts up to 100 feet from the fall when calculating the fall's damage,\
    \ and it can move up to 2 feet horizontally for every 1 foot it descends."
  "name": "Glide"
"actions":
- "desc": "The draconian makes two Trident melee attacks or two Lightning Discharge\
    \ attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Trident"
- "desc": "Ranged Spell Attack: +4 to hit, range 60 ft., one target. Hit: 10\
    \ (3d6) lightning damage."
  "name": "Lightning Discharge"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Bozak%20Draconian.webp"
```
^statblock

```encounter-table
name: Bozak Draconian
creatures:
 - 1: Bozak Draconian
```