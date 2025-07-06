---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/1
- monster/size/large
- monster/type/monstrosity
aliases: ["Eblis"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 219
---
# [Eblis](2-Mechanics\CLI\bestiary\monstrosity/eblis-toa.md)
*Source: Tomb of Annihilation p. 219*  

Eblis (pronounced EH-blee) are thought to be reincarnations of evil humans who were punished by gods for acts of larceny and kidnapping. These intelligent, evil cranes loom 8 feet tall and lay eggs as mundane birds do. They can manipulate objects with their beaks and feet.

Eblis try to sway other creatures into doing their bidding, and their plots are self-serving. They live to destroy creatures that offend them and delight in luring humanoids to an unexpected death. Eblis also like to collect treasure, which they sometimes use to reward those who serve them. They build crude huts and nests out of grass and reeds, wherein they hide their treasure.

```statblock
"name": "Eblis (ToA)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "26"
"hit_dice": "4d10 + 4"
"stats":
- !!int "11"
- !!int "16"
- !!int "12"
- !!int "12"
- !!int "14"
- !!int "11"
"speed": "30 ft., fly 40 ft."
"skillsaves":
  "Perception": !!int "4"
"senses": "passive Perception 14"
"languages": "Auran, Common"
"cr": "1"
"traits":
- "desc": "The eblis's innate spellcasting ability is Intelligence (spell save DC\
    \ 11). It can innately cast the following spells, requiring no material components:\n\
    \n1/day each: [blur](/2-Mechanics/CLI/spells/blur.md), [hypnotic pattern](/2-Mechanics/CLI/spells/hypnotic-pattern.md),\
    \ [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md)"
  "name": "Innate Spellcasting"
"actions":
- "desc": "The eblis attacks twice with its beak."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target Hit: 5 (1d4\
    \ + 3) piercing damage."
  "name": "Beak"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Eblis.webp"
```
^statblock

```encounter-table
name: Eblis
creatures:
 - 1: Eblis
```