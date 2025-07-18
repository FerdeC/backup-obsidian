---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mot
- monster/cr/4
- monster/size/large
- monster/type/celestial
aliases: ["Winged Lion"]
NoteIcon: monster
BestiaryType: celestial
SourceType: Bestiary
BookSource: Mythic Odysseys of Theros p. 214
---
# [Winged Lion](2-Mechanics\CLI\bestiary\celestial/winged-lion-mot.md)
*Source: Mythic Odysseys of Theros p. 214*  

Archons always ride into battle on fearsome winged mounts. Some legends suggest that the mount is actually a physical manifestation of the archon's will, allowing the pair to act with a single mind. The two most common archon mounts are winged bulls and winged lions.

```statblock
"name": "Winged Lion (MOT)"
"size": "Large"
"type": "celestial"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "114"
"hit_dice": "12d10 + 48"
"stats":
- !!int "20"
- !!int "16"
- !!int "18"
- !!int "6"
- !!int "14"
- !!int "5"
"speed": "60 ft., fly 60 ft."
"senses": "passive Perception 12"
"languages": "understands Celestial but can't speak"
"cr": "4"
"traits":
- "desc": "If the lion moves at least 20 feet straight toward a creature and then\
    \ hits it with a claw attack on the same turn, that target must succeed on a DC\
    \ 15 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone).\
    \ If the target is [prone](/2-Mechanics/CLI/rules/conditions.md#prone), the lion\
    \ can make one bite attack against it as a bonus action."
  "name": "Pounce"
"actions":
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 16\
    \ (2d10 + 5) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 14\
    \ (2d8 + 5) slashing damage."
  "name": "Claw"
"source":
- "MOT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MOT/Winged%20Lion.webp"
```
^statblock

```encounter-table
name: Winged Lion
creatures:
 - 1: Winged Lion
```