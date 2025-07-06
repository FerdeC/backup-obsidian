---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Padraich"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 170
---
# [Padraich](2-Mechanics\CLI\bestiary\npc/padraich-pota.md)
*Source: Princes of the Apocalypse p. 170*  

```statblock
"name": "Padraich (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Any Chaotic alignment"
"ac": !!int "13"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md)"
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
"cr": "2"
"traits":
- "desc": "At the start of its turn, Padraich can gain advantage on all melee weapon\
    \ attack rolls during that turn, but attack rolls against it have advantage until\
    \ the start of its next turn."
  "name": "Reckless"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) bludgeoning damage."
  "name": "Maul"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Padraich.webp"
```
^statblock

```encounter-table
name: Padraich
creatures:
 - 1: Padraich
```