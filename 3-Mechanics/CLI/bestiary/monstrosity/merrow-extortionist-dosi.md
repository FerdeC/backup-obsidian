---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dosi
- monster/cr/1
- monster/size/large
- monster/type/monstrosity
aliases: ["Merrow Extortionist"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Dragons of Stormwreck Isle p. 0
---
# [Merrow Extortionist](2-Mechanics\CLI\bestiary\monstrosity/merrow-extortionist-dosi.md)
*Source: Dragons of Stormwreck Isle p. 0*  

```statblock
"name": "Merrow Extortionist (DoSI)"
"size": "Large"
"type": "monstrosity"
"alignment": "typically  Chaotic Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "30"
"hit_dice": "4d10 + 8"
"stats":
- !!int "16"
- !!int "10"
- !!int "15"
- !!int "8"
- !!int "10"
- !!int "9"
"speed": "10 ft., swim 40 ft."
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Abyssal, Aquan, Common"
"cr": "1"
"traits":
- "desc": "The merrow can breathe air and water."
  "name": "Amphibious"
"actions":
- "desc": "The merrow makes two Rend attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 10 ft., one target. Hit: 8\
    \ (2d4 + 3) piercing damage."
  "name": "Rend"
"source":
- "DoSI"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DoSI/Merrow%20Extortionist.webp"
```
^statblock

```encounter-table
name: Merrow Extortionist
creatures:
 - 1: Merrow Extortionist
```