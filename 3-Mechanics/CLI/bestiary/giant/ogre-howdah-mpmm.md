---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/2
- monster/environment/grassland
- monster/environment/hill
- monster/environment/mountain
- monster/size/large
- monster/type/giant
aliases: ["Ogre Howdah"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 201, Mordenkainen's Tome of Foes p. 221
---
# [Ogre Howdah](2-Mechanics\CLI\bestiary\giant/ogre-howdah-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 201, Mordenkainen's Tome of Foes p. 221*  

The most unusual of the specialized ogres, the howdah carries a palisaded wooden fort on its back. The fort serves as a fighting platform for up to four Small people. Ogre howdahs are most often seen bearing bow- and spear-wielding [goblins](/2-Mechanics/CLI/bestiary/humanoid/goblin.md) into battle, or perhaps [kobolds](/2-Mechanics/CLI/bestiary/humanoid/kobold.md) or [deep gnomes](/2-Mechanics/CLI/bestiary/humanoid/deep-gnome-svirfneblin.md), but they might also transport other Small folk.

## Ogres of War

Ogres love to rush headlong into battle, but with enough time and patience, some of them learn to carry out specialized missions. The names they are given—the battering ram, the bolt launcher, the chain brute, and the howdah—reflect their particular functions. These jobs are tailored to take advantage of an ogre's strengths.

```statblock
"name": "Ogre Howdah (MPMM)"
"size": "Large"
"type": "giant"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "15"
"ac_class": "[breastplate](/2-Mechanics/CLI/items/breastplate.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "59"
"hit_dice": "7d10 + 21"
"stats":
- !!int "19"
- !!int "8"
- !!int "16"
- !!int "5"
- !!int "7"
- !!int "7"
"speed": "40 ft."
"senses": "darkvision 60 ft., passive Perception 8"
"languages": "Common, Giant"
"cr": "2"
"traits":
- "desc": "The ogre carries a compact fort on its back. Up to four Small creatures\
    \ can ride in the fort without squeezing. To make a melee attack against a target\
    \ within 5 feet of the ogre, they must use spears or weapons with reach. Creatures\
    \ in the fort have three-quarters cover against attacks and effects from outside\
    \ it. If the ogre dies, creatures in the fort are placed in unoccupied spaces\
    \ within 5 feet of the ogre."
  "name": "Howdah"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) bludgeoning damage."
  "name": "Mace"
"source":
- "MPMM"
- "MTF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPMM/Ogre%20Howdah.webp"
```
^statblock

```encounter-table
name: Ogre Howdah
creatures:
 - 1: Ogre Howdah
```

## Environment

grassland, hill, mountain