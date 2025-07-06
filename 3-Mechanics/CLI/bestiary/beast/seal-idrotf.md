---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/0
- monster/size/medium
- monster/type/beast
aliases: ["Seal"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 308
---
# [Seal](2-Mechanics\CLI\bestiary\beast/seal-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 308*  

The seals native to the Sea of Moving Ice often beach themselves on ice floes and rocky shores. They are acclimated to the cold weather and feed primarily on small fish, squid, and clams. Seal pups have yellowish-white fur, which turns silvery gray as they enter adulthood.

```statblock
"name": "Seal (IDRotF)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "10"
- !!int "12"
- !!int "11"
- !!int "3"
- !!int "12"
- !!int "5"
"speed": "20 ft., swim 40 ft."
"senses": "darkvision 60 ft., passive Perception 11"
"languages": ""
"cr": "0"
"traits":
- "desc": "The seal can hold its breath for 15 minutes."
  "name": "Hold Breath"
- "desc": "The seal has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 1 piercing\
    \ damage."
  "name": "Bite"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Seal.webp"
```
^statblock

```encounter-table
name: Seal
creatures:
 - 1: Seal
```