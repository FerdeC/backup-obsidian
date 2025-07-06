---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/3
- monster/size/large
- monster/type/dragon
aliases: ["Wasteland Dragonnel"]
NoteIcon: monster
BestiaryType: dragon
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 201
---
# [Wasteland Dragonnel](2-Mechanics\CLI\bestiary\dragon/wasteland-dragonnel-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 201*  

The Northern Wastes of Ansalon are home to wasteland dragonnels, draconic creatures closely related to copper dragons. Wasteland dragonnels are lithe and quick, with scales the color of dull copper. These playful creatures defend their territory by flying out of a foe's reach and spitting potent acid, in an approximation of their copper dragon relatives.

## Dragonnels

Dragonnels are distantly related to chromatic and metallic dragons and resemble them in basic form. Intelligent enough to understand speech but incapable of speaking themselves, they are willful creatures largely motivated by the desire for food.

```statblock
"name": "Wasteland Dragonnel (DSotDQ)"
"size": "Large"
"type": "dragon"
"alignment": "typically  Chaotic Good"
"ac": !!int "13"
"hp": !!int "65"
"hit_dice": "10d10 + 10"
"stats":
- !!int "16"
- !!int "16"
- !!int "12"
- !!int "8"
- !!int "13"
- !!int "10"
"speed": "30 ft., fly 60 ft."
"skillsaves":
  "Perception": !!int "3"
"damage_resistances": "acid"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 13"
"languages": "understands Common and Draconic but can't speak"
"cr": "3"
"traits":
- "desc": "The dragonnel doesn't provoke opportunity attacks when it flies out of\
    \ an enemy's reach."
  "name": "Flyby"
"actions":
- "desc": "The dragonnel makes two Rend attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) slashing damage."
  "name": "Rend"
- "desc": "Ranged Weapon Attack: +5 to hit, range 60 ft., one target. Hit: 20\
    \ (5d6 + 3) acid damage."
  "name": "Acid Spit"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Wasteland%20Dragonnel.webp"
```
^statblock

```encounter-table
name: Wasteland Dragonnel
creatures:
 - 1: Wasteland Dragonnel
```