---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/0
- monster/size/small
- monster/type/beast
aliases: ["Knucklehead Trout"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 295
---
# [Knucklehead Trout](2-Mechanics\CLI\bestiary\beast/knucklehead-trout-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 295*  

The tasty and tenacious knucklehead trout can't easily be caught in nets. Moreover, using a line to reel in such a strong fish is a significant undertaking. Incautious fishers who get pulled into freezing water can quickly die, particularly if they're weighed down by heavy furs and cloaks.

A male knucklehead trout can weigh 70 pounds or more. The females tend to be smaller, weighing about 50 pounds. Both are prized for their ivory-like bones.

```statblock
"name": "Knucklehead Trout (IDRotF)"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "7"
"hit_dice": "2d6"
"stats":
- !!int "14"
- !!int "14"
- !!int "11"
- !!int "1"
- !!int "6"
- !!int "1"
"speed": "0 ft., swim 30 ft."
"senses": "darkvision 60 ft., passive Perception 8"
"languages": ""
"cr": "0"
"traits":
- "desc": "The trout can breathe only underwater."
  "name": "Water Breathing"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) bludgeoning damage."
  "name": "Tail"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Knucklehead%20Trout.webp"
```
^statblock

```encounter-table
name: Knucklehead Trout
creatures:
 - 1: Knucklehead Trout
```