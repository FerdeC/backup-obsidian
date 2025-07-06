---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/4
- monster/size/huge
- monster/type/beast
aliases: ["Giant Walrus"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 312
---
# [Giant Walrus](2-Mechanics\CLI\bestiary\beast/giant-walrus-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 312*  

Giant walruses are enormous, ill-tempered creatures as big as elephants. A typical adult specimen weighs at least 12,000 pounds.

```statblock
"name": "Giant Walrus (IDRotF)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "9"
"hp": !!int "85"
"hit_dice": "9d12 + 27"
"stats":
- !!int "22"
- !!int "9"
- !!int "16"
- !!int "3"
- !!int "11"
- !!int "4"
"speed": "20 ft., swim 40 ft."
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "4"
"traits":
- "desc": "The walrus can hold its breath for 30 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "The walrus makes two attacks: one with its body flop and one with its tusks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 15\
    \ (2d8 + 6) bludgeoning damage."
  "name": "Body Flop"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 16\
    \ (3d6 + 6) piercing damage."
  "name": "Tusks"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Giant%20Walrus.webp"
```
^statblock

```encounter-table
name: Giant Walrus
creatures:
 - 1: Giant Walrus
```