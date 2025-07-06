---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mot
- monster/cr/4
- monster/size/large
- monster/type/celestial
aliases: ["Winged Bull"]
NoteIcon: monster
BestiaryType: celestial
SourceType: Bestiary
BookSource: Mythic Odysseys of Theros p. 214
---
# [Winged Bull](2-Mechanics\CLI\bestiary\celestial/winged-bull-mot.md)
*Source: Mythic Odysseys of Theros p. 214*  

Archons always ride into battle on fearsome winged mounts. Some legends suggest that the mount is actually a physical manifestation of the archon's will, allowing the pair to act with a single mind. The two most common archon mounts are winged bulls and winged lions.

```statblock
"name": "Winged Bull (MOT)"
"size": "Large"
"type": "celestial"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "95"
"hit_dice": "10d10 + 40"
"stats":
- !!int "20"
- !!int "14"
- !!int "18"
- !!int "6"
- !!int "10"
- !!int "5"
"speed": "60 ft., fly 60 ft."
"senses": "passive Perception 10"
"languages": "understands Celestial but can't speak"
"cr": "4"
"traits":
- "desc": "If the bull moves at least 20 feet straight toward a creature and then\
    \ hits it with a gore attack on the same turn, the target takes an extra 19 (3d12)\
    \ piercing damage."
  "name": "Charge"
"actions":
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 18\
    \ (2d12 + 5) piercing damage."
  "name": "Gore"
"source":
- "MOT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MOT/Winged%20Bull.webp"
```
^statblock

```encounter-table
name: Winged Bull
creatures:
 - 1: Winged Bull
```