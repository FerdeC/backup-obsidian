---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Remallia Haventree"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 214
---
# [Remallia Haventree](2-Mechanics\CLI\bestiary\npc/remallia-haventree-wdh.md)
*Source: Waterdeep: Dragon Heist p. 214*  

Remallia (Remi to her friends) is the lady of House Ulbrinter and a guiding light for the Harpers in Waterdeep

She became an active force for good in the city after assassins killed her husband, Arthagast Ulbrinter, and destroyed his remains. A sun elf, she has two adult children (a half-elf son named Arthius, who is studying music in Silverymoon, and a half-elf daughter named Serenore, who lives on the Moonshae island of Alaron with her husband and daughter). Lady Haventree retains a handful of loyal servants and spies.

Remi holds secret Harper meetings in her villa, which is warded by all manner of spells. She uses a silver raven figurine of wondrous power to deliver messages to Harper spies scattered throughout the city.

```statblock
"name": "Remallia Haventree (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Chaotic Good"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"stats":
- !!int "10"
- !!int "14"
- !!int "13"
- !!int "18"
- !!int "15"
- !!int "17"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Intelligence": !!int "8"
"skillsaves":
  "Deception": !!int "7"
  "History": !!int "8"
  "Arcana": !!int "8"
  "Persuasion": !!int "7"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Draconic, Dwarvish, Elvish, Halfling"
"cr": "9"
"traits":
- "desc": "Remallia is a 13th-level spellcaster. Her spellcasting ability is Intelligence\
    \ (spell save DC 16, +8 to hit with spell attacks). She has the following wizard\
    \ spells prepared:\n\nCantrips (at will): [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [mending](/2-Mechanics/CLI/spells/mending.md),\
    \ [message](/2-Mechanics/CLI/spells/message.md), [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md)\n\
    \n1st level (4 slots): [alarm](/2-Mechanics/CLI/spells/alarm.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md),\
    \ [magic missile](/2-Mechanics/CLI/spells/magic-missile.md), [shield](/2-Mechanics/CLI/spells/shield.md)\n\
    \n2nd level (3 slots): [arcane lock](/2-Mechanics/CLI/spells/arcane-lock.md),\
    \ [invisibility](/2-Mechanics/CLI/spells/invisibility.md)\n\n3rd level (3 slots):\
    \ [counterspell](/2-Mechanics/CLI/spells/counterspell.md), [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md),\
    \ [fireball](/2-Mechanics/CLI/spells/fireball.md)\n\n4th level (3 slots):\
    \ [banishment](/2-Mechanics/CLI/spells/banishment.md), [stoneskin](/2-Mechanics/CLI/spells/stoneskin.md)\n\
    \n5th level (2 slots): [cone of cold](/2-Mechanics/CLI/spells/cone-of-cold.md),\
    \ [wall of force](/2-Mechanics/CLI/spells/wall-of-force.md)\n\n6th level (1\
    \ slots): [flesh to stone](/2-Mechanics/CLI/spells/flesh-to-stone.md), [globe\
    \ of invulnerability](/2-Mechanics/CLI/spells/globe-of-invulnerability.md)\n\n\
    7th level (1 slots): [symbol](/2-Mechanics/CLI/spells/symbol.md), [teleport](/2-Mechanics/CLI/spells/teleport.md)"
  "name": "Spellcasting"
- "desc": "Remallia has a [figurine of wondrous power (silver raven)](/2-Mechanics/CLI/items/figurine-of-wondrous-power-silver-raven.md)."
  "name": "Special Equipment"
- "desc": "Remallia has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put her to sleep."
  "name": "Fey Ancestry"
- "desc": "Remallia has a magical ward that has 30 hit points. Whenever she takes\
    \ damage, the ward takes the damage instead. If the ward is reduced to 0 hit points,\
    \ Remallia takes any remaining damage. When Remallia casts an abjuration spell\
    \ of 1st level or higher, the ward regains a number of hit points equal to twice\
    \ the level of the spell. This applies to any of the following spells she casts:\
    \ [alarm](/2-Mechanics/CLI/spells/alarm.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md),\
    \ [shield](/2-Mechanics/CLI/spells/shield.md), [arcane lock](/2-Mechanics/CLI/spells/arcane-lock.md),\
    \ [counterspell](/2-Mechanics/CLI/spells/counterspell.md), [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md),\
    \ [banishment](/2-Mechanics/CLI/spells/banishment.md), [stoneskin](/2-Mechanics/CLI/spells/stoneskin.md),\
    \ [globe of invulnerability](/2-Mechanics/CLI/spells/globe-of-invulnerability.md)\
    \ and [symbol](/2-Mechanics/CLI/spells/symbol.md)."
  "name": "Arcane Ward"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft., one\
    \ target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "WDH"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDH/Remallia%20Haventree.webp"
```
^statblock

```encounter-table
name: Remallia Haventree
creatures:
 - 1: Remallia Haventree
```