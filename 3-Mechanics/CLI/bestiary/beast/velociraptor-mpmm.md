---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/1-4
- monster/environment/forest
- monster/environment/grassland
- monster/size/tiny
- monster/type/beast/dinosaur
aliases: ["Velociraptor"]
NoteIcon: monster
BestiaryType: beast (dinosaur)
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 96, Volo's Guide to Monsters p. 140
---
# [Velociraptor](2-Mechanics\CLI\bestiary\beast/velociraptor-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 96, Volo's Guide to Monsters p. 140*  

This feathered dinosaur is about the size of a large turkey. It is an aggressive predator and often hunts in packs to bring down larger prey.

```statblock
"name": "Velociraptor (MPMM)"
"size": "Tiny"
"type": "beast"
"subtype": "dinosaur"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "10"
"hit_dice": "3d4 + 3"
"stats":
- !!int "6"
- !!int "14"
- !!int "13"
- !!int "4"
- !!int "12"
- !!int "6"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The velociraptor has advantage on an attack roll against a creature if\
    \ at least one of the velociraptor's allies is within 5 feet of the creature and\
    \ the ally isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "The velociraptor makes one Bite attack and one Claw attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 5\
    \ (1d6 + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) slashing damage."
  "name": "Claw"
"source":
- "MPMM"
- "VGM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPMM/Velociraptor.webp"
```
^statblock

```encounter-table
name: Velociraptor
creatures:
 - 1: Velociraptor
```

## Environment

forest, grassland