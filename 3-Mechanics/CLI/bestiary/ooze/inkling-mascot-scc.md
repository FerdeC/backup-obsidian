---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/scc
- monster/cr/1-4
- monster/size/tiny
- monster/type/ooze
aliases: ["Inkling Mascot"]
NoteIcon: monster
BestiaryType: ooze
SourceType: Bestiary
BookSource: Strixhaven: A Curriculum of Chaos p. 195
---
# [Inkling Mascot](2-Mechanics\CLI\bestiary\ooze/inkling-mascot-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 195*  

Squelching slightly as they wriggle through the air, inklings serve as the mascots for Silverquill College. These living blobs of shadowy ink are often summoned by professors who require assistance in their writing workshops—the inklings provide endless ink—or by lonely students hoping for company as they study. However, inklings can just as readily support mages in combat, disrupting opponents' sight.

```statblock
"name": "Inkling Mascot (SCC)"
"size": "Tiny"
"type": "ooze"
"alignment": "typically  Neutral"
"ac": !!int "13"
"hp": !!int "18"
"hit_dice": "4d4 + 8"
"stats":
- !!int "10"
- !!int "16"
- !!int "14"
- !!int "6"
- !!int "7"
- !!int "11"
"speed": "10 ft., fly 30 ft. (hover)"
"skillsaves":
  "Stealth": !!int "5"
"damage_immunities": "psychic"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [prone](/2-Mechanics/CLI/rules/conditions.md#prone)"
"senses": "blindsight 60 ft., passive Perception 8"
"languages": "understands the languages of its creator but can't speak"
"cr": "1/4"
"traits":
- "desc": "The inkling can move through a space as narrow as 1 inch wide without squeezing."
  "name": "Amorphous"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
    \ + 3) psychic damage."
  "name": "Blot"
- "desc": "The inkling sprays viscous ink at one creature within 15 feet of itself.\
    \ The target must succeed on a DC 12 Constitution saving throw or be [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded)\
    \ until the end of the inkling's next turn."
  "name": "Ink Spray (1/Day)"
"bonus_actions":
- "desc": "While in dim light or darkness, the inkling takes the Hide action."
  "name": "Shadow Stealth"
"source":
- "SCC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SCC/Inkling%20Mascot.webp"
```
^statblock

```encounter-table
name: Inkling Mascot
creatures:
 - 1: Inkling Mascot
```