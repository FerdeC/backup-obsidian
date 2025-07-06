---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/1-4
- monster/size/large
- monster/type/beast
aliases: ["Walrus"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 312
---
# [Walrus](2-Mechanics\CLI\bestiary\beast/walrus-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 312*  

Walruses are bulky marine mammals that favor arctic climates and communicate by grunting and roaring. A typical adult specimen weighs at least 2,000 pounds. Humans hunt them for their meat, fat, skin, bones, and tusks.

```statblock
"name": "Walrus (IDRotF)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "9"
"hp": !!int "22"
"hit_dice": "3d10 + 6"
"stats":
- !!int "15"
- !!int "9"
- !!int "14"
- !!int "3"
- !!int "11"
- !!int "4"
"speed": "20 ft., swim 40 ft."
"senses": "passive Perception 10"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The walrus can hold its breath for 10 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (2d4\
    \ + 2) piercing damage."
  "name": "Tusks"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Walrus.webp"
```
^statblock

```encounter-table
name: Walrus
creatures:
 - 1: Walrus
```