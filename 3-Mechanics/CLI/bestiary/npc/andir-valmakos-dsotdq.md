---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Andir Valmakos"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 210
---
# [Andir Valmakos](2-Mechanics\CLI\bestiary\npc/andir-valmakos-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 210*  

Despite his aptitude for magic and his parents' being wizards themselves, [Andir](/2-Mechanics/CLI/bestiary/npc/andir-valmakos-dsotdq.md) completed his apprenticeship and chose not to immediately seek out other Mages of High Sorcery. Instead, he took to the life of an adventuring wizard, seeking to see the world and what magic exists beyond dusty tomes. Although his travels have only just begun, Andir knows that one day his road will lead him to the Tower of High Sorcery at Wayreth, where he hopes to be tested and learn what his future holds.

```statblock
"name": "Andir Valmakos (DSotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Good"
"ac": !!int "12"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "10"
- !!int "12"
- !!int "12"
- !!int "14"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "2"
"skillsaves":
  "Investigation": !!int "4"
  "Religion": !!int "4"
  "History": !!int "4"
  "Arcana": !!int "4"
"senses": "passive Perception 10"
"languages": "Common, Draconic"
"traits":
- "desc": "Andir's spellcasting ability is Intelligence (spell save DC 12, +4 to\
    \ hit with spell attacks). He has the following wizard spells prepared:\n\nAt\
    \ will: [light](/2-Mechanics/CLI/spells/light.md), [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md)\n\
    \n1st level (2 slots): [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md)"
  "name": "Spellcasting"
- "desc": "Andir is proficient with simple weapons and light armor."
  "name": "Bonus Proficiencies"
"actions":
- "desc": "Melee or Ranged Spell Attack: +4 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 7 (1d10 + 2) force damage."
  "name": "Arcane Burst"
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 3 (1d6)\
    \ bludgeoning damage, or 4 (1d8) bludgeoning damage if used with two hands."
  "name": "Quarterstaff"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Andir%20Valmakos.webp"
```
^statblock

```encounter-table
name: Andir Valmakos
creatures:
 - 1: Andir Valmakos
```