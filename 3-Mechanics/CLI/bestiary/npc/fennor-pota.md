---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Fennor"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 170
---
# [Fennor](2-Mechanics\CLI\bestiary\npc/fennor-pota.md)
*Source: Princes of the Apocalypse p. 170*  

```statblock
"name": "Fennor (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Any Chaotic alignment"
"ac": !!int "14"
"ac_class": "[chain shirt](/2-Mechanics/CLI/items/chain-shirt.md)"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"stats":
- !!int "16"
- !!int "12"
- !!int "17"
- !!int "9"
- !!int "11"
- !!int "9"
"speed": "30 ft."
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "3"
"traits":
- "desc": "At the start of its turn, Fennor can gain advantage on all melee weapon\
    \ attack rolls during that turn, but attack rolls against it have advantage until\
    \ the start of its next turn."
  "name": "Reckless"
"actions":
- "desc": "Fennor makes two attacks with her greatsword"
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) slashing damage."
  "name": "Greatsword"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Fennor.webp"
```
^statblock

```encounter-table
name: Fennor
creatures:
 - 1: Fennor
```