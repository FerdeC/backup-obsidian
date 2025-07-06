---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Noori"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 127
---
# [Noori](2-Mechanics\CLI\bestiary\npc/noori-skt.md)
*Source: Storm King's Thunder p. 127*  

```statblock
"name": "Noori (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
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
"skillsaves":
  "Stealth": !!int "3"
  "Survival": !!int "2"
"senses": "passive Perception 10"
"languages": "Bothii, Common"
"cr": "2"
"traits":
- "desc": "At the start of its turn, Noori can gain advantage on all melee weapon\
    \ attack rolls during that turn, but attack rolls against it have advantage until\
    \ the start of its next turn."
  "name": "Reckless"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 9 (1d12\
    \ + 3) slashing damage."
  "name": "Greataxe"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Noori.webp"
```
^statblock

```encounter-table
name: Noori
creatures:
 - 1: Noori
```