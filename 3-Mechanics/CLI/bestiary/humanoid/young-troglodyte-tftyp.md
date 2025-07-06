---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/1-8
- monster/size/small
- monster/type/humanoid/troglodyte
aliases: ["Young Troglodyte"]
NoteIcon: monster
BestiaryType: humanoid (troglodyte)
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 176
---
# [Young Troglodyte](2-Mechanics\CLI\bestiary\humanoid/young-troglodyte-tftyp.md)
*Source: Tales from the Yawning Portal p. 176*  

```statblock
"name": "Young Troglodyte (TftYP)"
"size": "Small"
"type": "humanoid"
"subtype": "troglodyte"
"alignment": "Lawful Evil"
"ac": !!int "12"
"hp": !!int "5"
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
- "desc": "While in sunlight, the troglodyte has disadvantage on attack rolls, as\
    \ well as on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on sight."
  "name": "Sunlight Sensitivity"
- "desc": "The troglodyte has advantage on an attack roll against a creature if at\
    \ least one of the troglodyte's allies is within 5 feet of the creature and the\
    \ ally isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
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
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Young%20Troglodyte.webp"
```
^statblock

```encounter-table
name: Young Troglodyte
creatures:
 - 1: Young Troglodyte
```