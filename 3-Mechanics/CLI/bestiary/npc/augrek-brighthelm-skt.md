---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/
- monster/size/medium
- monster/type/humanoid/shield-dwarf
aliases: ["Augrek Brighthelm"]
NoteIcon: monster
BestiaryType: humanoid (Shield dwarf)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 247
---
# [Augrek Brighthelm](2-Mechanics\CLI\bestiary\npc/augrek-brighthelm-skt.md)
*Source: Storm King's Thunder p. 247*  

Sheriff's deputy Augrek guards the southwest gate of Bryn Shander and welcomes visitors to town. She has a good heart.

Ideal:"You'll get farther in life with a kind word than an axe."

Bond:"Bryn Shander is my home. It's my job to protect her."

Flaw:"I'm head over heels in love with Sheriff Southwell. One day I hope to marry him."

```statblock
"name": "Augrek Brighthelm (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Shield dwarf"
"alignment": "Lawful Good"
"ac": !!int "15"
"ac_class": "[chain shirt](/2-Mechanics/CLI/items/chain-shirt.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "13"
"hit_dice": "2d8 + 4"
"stats":
- !!int "14"
- !!int "11"
- !!int "15"
- !!int "10"
- !!int "11"
- !!int "11"
"speed": "25 ft."
"skillsaves":
  "Athletics": !!int "4"
  "Perception": !!int "2"
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Dwarvish"
"traits":
- "desc": "Augrek has advantage on saving throws against poison."
  "name": "Dwarven Resilience"
- "desc": "Sheriff's deputy Augrek guards the southwest gate of Bryn Shander and welcomes\
    \ visitors to town. She has a good heart.\n\nIdeal: \"You'll get farther in life\
    \ with a kind word than an axe.\"\n\nBond: \"Bryn Shander is my home. It's my\
    \ job to protect her.\"\n\nFlaw: \"I'm head over heels in love with Sheriff Southwell.\
    \ One day I hope to marry him.\""
  "name": "Roleplaying Information"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) bludgeoning damage, or 7 (1d10 + 2) bludgeoning damage if used with\
    \ two hands."
  "name": "Warhammer"
- "desc": "Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. Hit:\
    \ 5 (1d10) piercing damage. Augrek carries ten crossbow bolts."
  "name": "Heavy Crossbow"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Augrek%20Brighthelm.webp"
```
^statblock

```encounter-table
name: Augrek Brighthelm
creatures:
 - 1: Augrek Brighthelm
```