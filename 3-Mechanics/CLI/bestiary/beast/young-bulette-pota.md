---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/2
- monster/size/large
- monster/type/beast
aliases: ["Young Bulette"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 139
---
# [Young Bulette](2-Mechanics\CLI\bestiary\beast/young-bulette-pota.md)
*Source: Princes of the Apocalypse p. 139*  

```statblock
"name": "Young Bulette (PotA)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "45"
"hit_dice": "6d10 + 12"
"stats":
- !!int "21"
- !!int "8"
- !!int "15"
- !!int "2"
- !!int "12"
- !!int "6"
"speed": "40 ft."
"senses": "passive Perception 11"
"languages": ""
"cr": "2"
"traits":
- "desc": "If the bulette moves at least 20 feet straight toward a target and then\
    \ hits it with a gore attack on the same turn, the target takes an extra 9 (2d8)\
    \ bludgeoning damage. If the target is a creature, it must succeed on a DC 15\
    \ Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Charge"
"actions":
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 14\
    \ (2d8 + 5) piercing damage."
  "name": "Bite"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Young%20Bulette.webp"
```
^statblock

```encounter-table
name: Young Bulette
creatures:
 - 1: Young Bulette
```