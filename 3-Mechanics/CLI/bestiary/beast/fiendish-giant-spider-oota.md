---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1-2
- monster/size/medium
- monster/type/beast
aliases: ["Fiendish Giant Spider"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Out of the Abyss p. 97
---
# [Fiendish Giant Spider](2-Mechanics\CLI\bestiary\beast/fiendish-giant-spider-oota.md)
*Source: Out of the Abyss p. 97*  

```statblock
"name": "Fiendish Giant Spider (OotA)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "12"
- !!int "16"
- !!int "13"
- !!int "3"
- !!int "12"
- !!int "4"
"speed": "40 ft., climb 40 ft."
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "3"
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 10 ft., darkvision 60 ft., passive Perception 13"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "The spider can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
- "desc": "While in contact with a web, the spider knows the exact location of any\
    \ other creature in contact with the same web."
  "name": "Web Sense"
- "desc": "The spider ignores movement restrictions caused by webbing."
  "name": "Web Walker"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one creature. Hit: 4\
    \ (1d6 + 1) piercing damage, and the target must make a DC 11 Constitution saving\
    \ throw, taking 7 (2d6) poison damage on a failed save, or half as much damage\
    \ on a successful one. If the poison damage reduces the target to 0 hit points,\
    \ the target is stable but [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 hour, even after regaining hit points, and is [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed)\
    \ while [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) in this way."
  "name": "Bite"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Fiendish%20Giant%20Spider.webp"
```
^statblock

```encounter-table
name: Fiendish Giant Spider
creatures:
 - 1: Fiendish Giant Spider
```