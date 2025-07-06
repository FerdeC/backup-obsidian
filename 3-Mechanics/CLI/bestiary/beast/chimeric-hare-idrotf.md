---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/0
- monster/size/tiny
- monster/type/beast
aliases: ["Chimeric Hare"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 246
---
# [Chimeric Hare](2-Mechanics\CLI\bestiary\beast/chimeric-hare-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 246*  

Snowshoe hares are gentle herbivores that live in burrows throughout Icewind Dale. They have shorter ears than other hares and are acclimated to cold weather. Chimeric hares have feathered wings.

```statblock
"name": "Chimeric Hare (IDRotF)"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"stats":
- !!int "1"
- !!int "17"
- !!int "9"
- !!int "2"
- !!int "11"
- !!int "4"
"speed": "20 ft., burrow 5 ft., fly 30 ft."
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": ""
"cr": "0"
"traits":
- "desc": "The hare can take the Dash, Disengage, or Hide action as a bonus action\
    \ on each of its turns."
  "name": "Escape"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Chimeric%20Hare.webp"
```
^statblock

```encounter-table
name: Chimeric Hare
creatures:
 - 1: Chimeric Hare
```