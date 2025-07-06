---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/1-2
- monster/size/medium
- monster/type/monstrosity
aliases: ["Amphisbaena"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 230, Mythic Odysseys of Theros
---
# [Amphisbaena](2-Mechanics\CLI\bestiary\monstrosity/amphisbaena-gos.md)
*Source: Ghosts of Saltmarsh p. 230, Mythic Odysseys of Theros*  

Found in Danger at Dunwater, these strange reptiles have a head at either end of their serpentine bodies, each one equipped with venomous fangs. To move, an amphisbaena uses one head to grip the neck of its other head, forming a hoop that rolls over the ground.

```statblock
"name": "Amphisbaena (GoS)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "14"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "14"
- !!int "18"
- !!int "12"
- !!int "3"
- !!int "10"
- !!int "3"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "blindsight 10 ft., passive Perception 12"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "The amphisbaena has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks and on saving throws against being [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
    \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
    \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned),\
    \ and knocked [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)."
  "name": "Two Heads"
"actions":
- "desc": "The amphisbaena makes two bite attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d4\
    \ + 4) piercing damage, and the target must make a DC 11 Constitution saving\
    \ throw, taking 3 (1d6) poison damage on a failed save, or half as much damage\
    \ on a successful one."
  "name": "Bite"
"source":
- "GoS"
- "MOT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Amphisbaena.webp"
```
^statblock

```encounter-table
name: Amphisbaena
creatures:
 - 1: Amphisbaena
```