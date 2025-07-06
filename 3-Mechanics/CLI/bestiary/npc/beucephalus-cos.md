---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cos
- monster/cr/3
- monster/size/large
- monster/type/fiend
aliases: ["Beucephalus"]
NoteIcon: monster
BestiaryType: fiend
SourceType: Bestiary
BookSource: Curse of Strahd p. 93
---
# [Beucephalus](2-Mechanics\CLI\bestiary\npc/beucephalus-cos.md)
*Source: Curse of Strahd p. 93*  

```statblock
"name": "Beucephalus (CoS)"
"size": "Large"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "104"
"hit_dice": "8d10 + 24"
"stats":
- !!int "18"
- !!int "15"
- !!int "16"
- !!int "10"
- !!int "13"
- !!int "15"
"speed": "60 ft., fly 90 ft."
"damage_immunities": "fire"
"senses": "passive Perception 11"
"languages": "understands Abyssal, Common, and Infernal but can't speak "
"cr": "3"
"traits":
- "desc": "Beucephalus can grant resistance to fire damage to anyone riding it."
  "name": "Confer Fire Resistance"
- "desc": "Beucephalus sheds bright light in a 10-foot radius and dim light for an\
    \ additional 10 feet."
  "name": "Illumination"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) bludgeoning damage plus 7 (2d6) fire damage."
  "name": "Hooves"
- "desc": "Beucephalus and up to three willing creatures within 5 feet of it magically\
    \ enter the Ethereal Plane from the Material Plane, or vice versa."
  "name": "Ethereal Stride"
"source":
- "CoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CoS/Beucephalus.webp"
```
^statblock

```encounter-table
name: Beucephalus
creatures:
 - 1: Beucephalus
```