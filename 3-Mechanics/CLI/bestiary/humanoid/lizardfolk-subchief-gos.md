---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/lizardfolk
aliases: ["Lizardfolk Subchief"]
NoteIcon: monster
BestiaryType: humanoid (lizardfolk)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 242
---
# [Lizardfolk Subchief](2-Mechanics\CLI\bestiary\humanoid/lizardfolk-subchief-gos.md)
*Source: Ghosts of Saltmarsh p. 242*  

The lizardfolk subchief (seen in Danger at Dunwater) is a devout priest of Semuanya, pursuing the worship of its god in a manner similar to a cleric. It wields a dagger crafted of a massive crocodile tooth blessed by Semuanya, representing the subchief's prowess in both battle and piety.

```statblock
"name": "Lizardfolk Subchief (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "lizardfolk"
"alignment": "Neutral"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "14"
- !!int "12"
- !!int "14"
- !!int "10"
- !!int "16"
- !!int "12"
"speed": "30 ft., swim 30 ft."
"saves":
  "Wisdom": !!int "5"
"skillsaves":
  "Athletics": !!int "4"
  "Perception": !!int "5"
  "Survival": !!int "5"
"senses": "passive Perception 15"
"languages": "Draconic"
"cr": "3"
"traits":
- "desc": "The subchief is a 5th-level spellcaster. Its spellcasting ability is Wisdom\
    \ (spell save DC 13, +5 to hit with spell attacks). It has the following cleric\
    \ spells prepared:\n\nCantrips (at will): [light](/2-Mechanics/CLI/spells/light.md),\
    \ [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md), [spare the dying](/2-Mechanics/CLI/spells/spare-the-dying.md),\
    \ [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\n1st level (4 slots):\
    \ [command](/2-Mechanics/CLI/spells/command.md), [guiding bolt](/2-Mechanics/CLI/spells/guiding-bolt.md),\
    \ [purify food and drink](/2-Mechanics/CLI/spells/purify-food-and-drink.md)\n\n\
    2nd level (3 slots): [hold person](/2-Mechanics/CLI/spells/hold-person.md),\
    \ [lesser restoration](/2-Mechanics/CLI/spells/lesser-restoration.md), [silence](/2-Mechanics/CLI/spells/silence.md)\n\
    \n3rd level (2 slots): [bestow curse](/2-Mechanics/CLI/spells/bestow-curse.md),\
    \ [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md)"
  "name": "Spellcasting"
- "desc": "The subchief can hold its breath for 15 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage."
  "name": "Tooth Dagger"
- "desc": "The subchief invokes the primal magic of Semuanya, summoning a spectral\
    \ maw around a target it can see within 60 feet of it. The target must make a\
    \ DC 13 Dexterity saving throw, taking 22 (5d8) piercing damage on a failed\
    \ save, or half as much damage on a successful one. A creature that fails this\
    \ saving throw is also [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ until the end of its next turn."
  "name": "Jaws of Semuanya (Recharge 5-6)"
"source":
- "GoS"
- "SLW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Lizardfolk%20Subchief.webp"
```
^statblock

```encounter-table
name: Lizardfolk Subchief
creatures:
 - 1: Lizardfolk Subchief
```