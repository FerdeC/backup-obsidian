---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cm
- monster/cr/13
- monster/size/large
- monster/type/construct
aliases: ["Canopic Golem"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Candlekeep Mysteries p. 179
---
# [Canopic Golem](2-Mechanics\CLI\bestiary\construct/canopic-golem-cm.md)
*Source: Candlekeep Mysteries p. 179*  

A mummy lord's organs, normally stored in sacred canopic jars during mummification, can be magically preserved and transplanted into living humanoids. The transplant recipients come under the control of the mummy lord, either as living supplicants or mindless golems through which the mummy lord can see and speak.

```statblock
"name": "Canopic Golem (CM)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "252"
"hit_dice": "24d10 + 120"
"stats":
- !!int "20"
- !!int "10"
- !!int "20"
- !!int "7"
- !!int "11"
- !!int "1"
"speed": "30 ft."
"saves":
  "Charisma": !!int "0"
  "Wisdom": !!int "5"
  "Intelligence": !!int "3"
"damage_immunities": "poison"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": ""
"cr": "13"
"traits":
- "desc": "The golem automatically succeeds on saving throws against spells of 7th\
    \ level or lower, and the attack rolls of such spells always miss it."
  "name": "Limited Spell Immunity"
- "desc": "The golem doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The golem makes two attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 27\
    \ (4d10 + 5) force damage."
  "name": "Slam"
- "desc": "Ranged Weapon Attack: +10 to hit, range 120 ft., one target. Hit:\
    \ 14 (2d8 + 5) force damage."
  "name": "Crystal Dart"
"reactions":
- "desc": "In response to a spell attack missing the golem, it causes that spell to\
    \ hit another creature within 120 feet of it that it can see."
  "name": "Spell Deflection"
"source":
- "CM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CM/Canopic%20Golem.webp"
```
^statblock

```encounter-table
name: Canopic Golem
creatures:
 - 1: Canopic Golem
```