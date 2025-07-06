---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dosi
- monster/cr/1-4
- monster/size/small
- monster/type/humanoid
aliases: ["Kobold Tinkerer"]
NoteIcon: monster
BestiaryType: humanoid
SourceType: Bestiary
BookSource: Dragons of Stormwreck Isle p. 43
---
# [Kobold Tinkerer](2-Mechanics\CLI\bestiary\humanoid/kobold-tinkerer-dosi.md)
*Source: Dragons of Stormwreck Isle p. 43*  

Kobolds are reptilian Humanoids that often revere dragons. Physically weak, they find strength in numbers.

A few kobolds are born with leathery wings and can fly, which is often seen as a gift from dragon gods.

```statblock
"name": "Kobold Tinkerer (DoSI)"
"size": "Small"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "10"
"hit_dice": "3d6"
"stats":
- !!int "7"
- !!int "14"
- !!int "10"
- !!int "15"
- !!int "7"
- !!int "9"
"speed": "30 ft., fly 10 ft."
"skillsaves":
  "Perception": !!int "0"
  "Arcana": !!int "4"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Draconic"
"cr": "1/4"
"traits":
- "desc": "The kobold can cast [detect magic](/2-Mechanics/CLI/spells/detect-magic.md),\
    \ requiring no spell components and using Intelligence as the spellcasting ability."
  "name": "Inquiring Mind (1/Day)"
- "desc": "The kobold has advantage on an attack roll against a creature if at least\
    \ one of its allies is within 5 feet of the creature and the ally isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
- "desc": "While in sunlight, the kobold has disadvantage on attack rolls, as well\
    \ as on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
- "desc": "The kobold unleashes fire in a 15-foot cone. Each creature in that area\
    \ must make a DC 12 Dexterity saving throw, taking 10 (3d6) fire damage on a\
    \ failed saving throw, or half as much damage on a successful one."
  "name": "Alchemical Flame (Recharge 6)"
"source":
- "DoSI"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DoSI/Kobold%20Tinkerer.webp"
```
^statblock

```encounter-table
name: Kobold Tinkerer
creatures:
 - 1: Kobold Tinkerer
```