---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dosi
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Varnoth"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Dragons of Stormwreck Isle p. 47
---
# [Varnoth](2-Mechanics\CLI\bestiary\npc/varnoth-dosi.md)
*Source: Dragons of Stormwreck Isle p. 47*  

A hardened mercenary captain, Varnoth Wender is an experienced professional fighter. She is usually unarmed, but she keeps her old sword beneath the mattress in her cell (in area A1 in Dragon's Rest).

```statblock
"name": "Varnoth (DoSI)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Good"
"ac": !!int "11"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"stats":
- !!int "16"
- !!int "13"
- !!int "14"
- !!int "10"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "5"
  "Religion": !!int "2"
  "Perception": !!int "2"
  "History": !!int "2"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "2"
"actions":
- "desc": "Varnoth makes three Shortsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Shortsword"
"source":
- "DoSI"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DoSI/Varnoth.webp"
```
^statblock

```encounter-table
name: Varnoth
creatures:
 - 1: Varnoth
```