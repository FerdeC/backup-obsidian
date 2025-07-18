---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mot
- monster/cr/3
- monster/size/medium
- monster/type/humanoid
aliases: ["Meletian Hoplite"]
NoteIcon: monster
BestiaryType: humanoid
SourceType: Bestiary
BookSource: Mythic Odysseys of Theros p. 229
---
# [Meletian Hoplite](2-Mechanics\CLI\bestiary\humanoid/meletian-hoplite-mot.md)
*Source: Mythic Odysseys of Theros p. 229*  

Meletian hoplites use a combination of cunning, faith, and magic to defend their coastal home. Most of these skilled soldiers serve in the Reverent Army, the defenders of Meletis, which uses an array of proven strategies and flexible troop formations to gain the advantage over foes. Bolstered by trained griffon and pegasus steeds, they strike foes where they least expect.

Hoplites are highly trained warriors, versed not only in strategy and tactics but in the glorification of the warrior's spirit, the basis of an ethos that forges an unbreakable bond between members of a military unit. In combat, hoplites typically work in groups and use coordinated tactics to win victories.

The three Hoplite Unit Names tables present the sorts of titles used by hoplite contingents hailing from Theros's great poleis. Consider using these names for military forces characters encounter during their adventures or that they were once a part of.

**Akroan Hoplite Unit Names**

| D8 | Name |
|----|------|
| 1 | Spears of Iroas |
| 2 | Iron Fangs |
| 3 | Arrows of Anax |
| 4 | The Unbroken |
| 5 | Anvil of Purphoros |
| 6 | Skewering Squad |
| 7 | Shield of Akros |
| 8 | Cymede's Heart |
^akroan-hoplite-unit-names

**Meletian Hoplite Unit Names**

| D8 | Name |
|----|------|
| 1 | Kraken's Claw |
| 2 | Hands of Justice |
| 3 | Thassa's Spear |
| 4 | Ephara's Shield |
| 5 | Kindred of the Deep |
| 6 | Riders of Heliod |
| 7 | Keepers of Pyrgnos |
| 8 | The Skysworn |
^meletian-hoplite-unit-names

**Setessan Hoplite Unit Names**

`dice: [](meletian-hoplite-mot.md#^setessan-hoplite-unit-names)`

| dice: d8 | Name |
|----------|------|
| 1 | Nylea's Arrows |
| 2 | The Watchers |
| 3 | Fangs of Ophis |
| 4 | The Swiftswords |
| 5 | Karametra's Wolves |
| 6 | Defenders of the Grove |
| 7 | Bronze Blades |
| 8 | The Jackals |
^setessan-hoplite-unit-names

```statblock
"name": "Meletian Hoplite (MOT)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[breastplate](/2-Mechanics/CLI/items/breastplate.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "49"
"hit_dice": "9d8 + 9"
"stats":
- !!int "16"
- !!int "14"
- !!int "12"
- !!int "16"
- !!int "13"
- !!int "11"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "4"
  "Intelligence": !!int "5"
"skillsaves":
  "Perception": !!int "3"
  "History": !!int "5"
  "Arcana": !!int "5"
"senses": "passive Perception 13"
"languages": "Common"
"cr": "3"
"traits":
- "desc": "The hoplite is a 3rd-level spellcaster. Its spellcasting ability is Intelligence\
    \ (spell save DC 13, +5 to hit with spell attacks). It has the following wizard\
    \ spells prepared:\n\nCantrips (at will): [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md), [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md)\
    \ (see \"Actions\" below)\n\n1st level (4 slots): [color spray](/2-Mechanics/CLI/spells/color-spray.md),\
    \ [expeditious retreat](/2-Mechanics/CLI/spells/expeditious-retreat.md), [sleep](/2-Mechanics/CLI/spells/sleep.md)\n\
    \n2nd level (2 slots): [blur](/2-Mechanics/CLI/spells/blur.md), [cloud of\
    \ daggers](/2-Mechanics/CLI/spells/cloud-of-daggers.md), [invisibility](/2-Mechanics/CLI/spells/invisibility.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The hoplite makes three weapon attacks. It can replace one weapon attack\
    \ with ray of frost."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft., one target.\
    \ Hit: 6 (1d6 + 3) piercing damage, or 7 (1d8 + 3) piercing damage if used\
    \ with two hands to make a melee attack."
  "name": "Spear"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 5\
    \ (1d4 + 3) bludgeoning damage. If the target is a Medium or smaller creature,\
    \ it must succeed on a DC 13 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Shield Bash"
- "desc": "Ranged Spell Attack: +5 to hit, range 60 ft., one creature. Hit:\
    \ 4 (1d8) cold damage, and the target's speed is reduced by 10 feet until the\
    \ start of the hoplite's next turn."
  "name": "Ray of Frost (Cantrip)"
"source":
- "MOT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MOT/Meletian%20Hoplite.webp"
```
^statblock

```encounter-table
name: Meletian Hoplite
creatures:
 - 1: Meletian Hoplite
```