---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/1-8
- monster/size/small
- monster/type/humanoid/kobold
aliases: ["Kobold Elite"]
NoteIcon: monster
BestiaryType: humanoid (kobold)
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 18
---
# [Kobold Elite](2-Mechanics\CLI\bestiary\humanoid/kobold-elite-tftyp.md)
*Source: Tales from the Yawning Portal p. 18*  

```statblock
"name": "Kobold Elite (TftYP)"
"size": "Small"
"type": "humanoid"
"subtype": "kobold"
"alignment": "Lawful Evil"
"ac": !!int "12"
"hp": !!int "7"
"hit_dice": "2d6 - 2"
"stats":
- !!int "7"
- !!int "15"
- !!int "9"
- !!int "8"
- !!int "7"
- !!int "8"
"speed": "30 ft."
"senses": "darkvision 60 ft., passive Perception 8"
"languages": "Common, Draconic"
"cr": "1/8"
"traits":
- "desc": "While in sunlight, the kobold has disadvantage on attack rolls, as well\
    \ as on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
- "desc": "The kobold has advantage on an attack roll against a creature if at least\
    \ one of the kobold's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage."
  "name": "Dagger"
- "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit:\
    \ 4 (1d4 + 2) bludgeoning damage."
  "name": "Sling"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Kobold%20Elite.webp"
```
^statblock

```encounter-table
name: Kobold Elite
creatures:
 - 1: Kobold Elite
```