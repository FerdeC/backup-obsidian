---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cm
- monster/cr/5
- monster/size/medium
- monster/type/humanoid
aliases: ["Immortal Lotus Monk"]
NoteIcon: monster
BestiaryType: humanoid
SourceType: Bestiary
BookSource: Candlekeep Mysteries p. 165
---
# [Immortal Lotus Monk](2-Mechanics\CLI\bestiary\humanoid/immortal-lotus-monk-cm.md)
*Source: Candlekeep Mysteries p. 165*  

```statblock
"name": "Immortal Lotus Monk (CM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "Unarmored Defense"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "12"
- !!int "16"
- !!int "14"
- !!int "11"
- !!int "14"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "5"
  "Acrobatics": !!int "6"
"senses": "passive Perception 15"
"languages": "Common"
"cr": "5"
"traits":
- "desc": "While the monk is wearing no armor and wielding no shield, its AC includes\
    \ its Wisdom modifier."
  "name": "Unarmored Defense"
"actions":
- "desc": "The monk makes two attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) force damage, and if the target is a creature, it must succeed on a DC\
    \ 14 Dexterity saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Force Strike"
- "desc": "Ranged Weapon Attack: +6 to hit, range 20/60 ft., one target. Hit:\
    \ 5 (1d4 + 3) piercing damage."
  "name": "Dart"
"source":
- "CM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CM/Immortal%20Lotus%20Monk.webp"
```
^statblock

```encounter-table
name: Immortal Lotus Monk
creatures:
 - 1: Immortal Lotus Monk
```