---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/jttrc
- monster/cr/1-2
- monster/size/large
- monster/type/beast
aliases: ["Koi Prawn"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Journeys through the Radiant Citadel p. 26
---
# [Koi Prawn](2-Mechanics\CLI\bestiary\beast/koi-prawn-jttrc.md)
*Source: Journeys through the Radiant Citadel p. 26*  

```statblock
"name": "Koi Prawn (JttRC)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "16"
"hit_dice": "3d10"
"stats":
- !!int "12"
- !!int "15"
- !!int "11"
- !!int "2"
- !!int "12"
- !!int "5"
"speed": "0 ft., swim 40 ft."
"senses": "passive Perception 11"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "If the prawn moves at least 20 feet straight toward a target and then hits\
    \ it with a ram attack on the same turn, the target takes an extra 7 (2d6) bludgeoning\
    \ damage. If the target is a creature, it must succeed on a DC 11 Strength saving\
    \ throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Charge"
- "desc": "The prawn can breathe only underwater."
  "name": "Water Breathing"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) bludgeoning damage."
  "name": "Ram"
"source":
- "JttRC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/JttRC/Koi%20Prawn.webp"
```
^statblock

```encounter-table
name: Koi Prawn
creatures:
 - 1: Koi Prawn
```