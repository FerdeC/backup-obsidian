---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/sahuagin
aliases: ["Sahuagin High Priestess"]
NoteIcon: monster
BestiaryType: humanoid (sahuagin)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 251
---
# [Sahuagin High Priestess](2-Mechanics\CLI\bestiary\humanoid/sahuagin-high-priestess-gos.md)
*Source: Ghosts of Saltmarsh p. 251*  

A sahuagin high priestess is the most devout and ferocious of all Sekolah's worshipers. Armed with a staff studded with jagged shark's teeth, she can be seen leading dark rituals in The Final Enemy.

```statblock
"name": "Sahuagin High Priestess (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "sahuagin"
"alignment": "Lawful Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "71"
"hit_dice": "11d8 + 22"
"stats":
- !!int "14"
- !!int "12"
- !!int "14"
- !!int "12"
- !!int "16"
- !!int "10"
"speed": "30 ft., swim 40 ft."
"saves":
  "Wisdom": !!int "6"
"skillsaves":
  "Insight": !!int "6"
  "Perception": !!int "6"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Sahuagin"
"cr": "5"
"traits":
- "desc": "The high priestess is a 7th-level spellcaster. Her spellcasting ability\
    \ is Wisdom (spell save DC 14, +6 to hit with spell attacks). She has the following\
    \ cleric spells prepared:\n\nCantrips (at will): [guidance](/2-Mechanics/CLI/spells/guidance.md),\
    \ [mending](/2-Mechanics/CLI/spells/mending.md), [resistance](/2-Mechanics/CLI/spells/resistance.md),\
    \ [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\n1st level (4 slots):\
    \ [bless](/2-Mechanics/CLI/spells/bless.md), [detect magic](/2-Mechanics/CLI/spells/detect-magic.md),\
    \ [guiding bolt](/2-Mechanics/CLI/spells/guiding-bolt.md)\n\n2nd level (3 slots):\
    \ [hold person](/2-Mechanics/CLI/spells/hold-person.md), [spiritual weapon](/2-Mechanics/CLI/spells/spiritual-weapon.md)\
    \ (trident)\n\n3rd level (3 slots): [bestow curse](/2-Mechanics/CLI/spells/bestow-curse.md),\
    \ [fear](/2-Mechanics/CLI/spells/fear.md), [mass healing word](/2-Mechanics/CLI/spells/mass-healing-word.md),\
    \ [tongues](/2-Mechanics/CLI/spells/tongues.md)\n\n4th level (1 slots): [banishment](/2-Mechanics/CLI/spells/banishment.md)"
  "name": "Spellcasting"
- "desc": "The high priestess has advantage on melee attack rolls against any creature\
    \ that doesn't have all its hit points."
  "name": "Blood Frenzy"
- "desc": "The high priestess can breathe air and water, but she needs to be submerged\
    \ at least once every 4 hours to avoid suffocating."
  "name": "Limited Amphibiousness"
- "desc": "The high priestess can magically command any shark within 120 feet of her,\
    \ using a limited telepathy."
  "name": "Shark Telepathy"
"actions":
- "desc": "The high priestess makes two attacks with her toothsome staff, or one attack\
    \ with her bite and one with her claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d8 + 2) piercing damage."
  "name": "Toothsome Staff"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) slashing damage."
  "name": "Claws"
"source":
- "GoS"
- "SDW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Sahuagin%20High%20Priestess.webp"
```
^statblock

```encounter-table
name: Sahuagin High Priestess
creatures:
 - 1: Sahuagin High Priestess
```