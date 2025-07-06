---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/3
- monster/size/large
- monster/type/monstrosity
aliases: ["Giant Ice Toad"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 235
---
# [Giant Ice Toad](2-Mechanics\CLI\bestiary\monstrosity/giant-ice-toad-tftyp.md)
*Source: Tales from the Yawning Portal p. 235*  

In a cavern within the glacial rift (Against the Giants), a group of ice toads vigorously guard their territory. Waves of cold radiate from the creature, afflicting those that try to approach it, and anyone unfortunate enough to be swallowed suffers injury from cold as well as from the toad's digestive juices.

```statblock
"name": "Giant Ice Toad (TftYP)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "52"
"hit_dice": "7d10 + 14"
"stats":
- !!int "16"
- !!int "13"
- !!int "14"
- !!int "8"
- !!int "10"
- !!int "6"
"speed": "30 ft."
"damage_immunities": "cold"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Ice Toad"
"cr": "3"
"traits":
- "desc": "The toad can breathe air and water."
  "name": "Amphibious"
- "desc": "Any creature that starts its turn within 10 feet of the toad takes 5 (1d10)\
    \ cold damage."
  "name": "Cold Aura"
- "desc": "The toad's long jump is up to 20 feet and its high jump is up to 10 feet,\
    \ with or without a running start."
  "name": "Standing Leap"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) piercing damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 13). Until this grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and the toad can't bite another target."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one Medium or smaller\
    \ creature the toad is grappling. Hit: 10 (2d6 + 3) piercing damage, the target\
    \ is swallowed, and the grapple ends. The swallowed target is [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded)\
    \ and [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained), it has total\
    \ cover against attacks and other effects outside the toad, and it takes 10 (3d6)\
    \ acid damage and 11 (2d10) cold damage at the start of each of the toad's turns.\
    \ The toad can have only one target swallowed at a time.\n\nIf the toad dies,\
    \ a swallowed creature is no longer [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ by it and can escape from the corpse using 5 feet of movement, exiting [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Swallow"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Giant%20Ice%20Toad.webp"
```
^statblock

```encounter-table
name: Giant Ice Toad
creatures:
 - 1: Giant Ice Toad
```