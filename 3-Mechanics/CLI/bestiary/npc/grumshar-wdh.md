---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/1-4
- monster/size/medium
- monster/type/humanoid/half-orc
aliases: ["Grum'shar"]
NoteIcon: monster
BestiaryType: humanoid (half-orc)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 29
---
# [Grum'shar](2-Mechanics\CLI\bestiary\npc/grumshar-wdh.md)
*Source: Waterdeep: Dragon Heist p. 29*  

Apprentice wizards are novice arcane spellcasters who serve more experienced wizards or attend school. They perform menial work, such as cooking and cleaning, in exchange for education in the ways of magic.

```statblock
"name": "Grum'shar (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-orc"
"alignment": "Chaotic Evil"
"ac": !!int "10"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "14"
- !!int "10"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "History": !!int "4"
  "Arcana": !!int "4"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Orc"
"cr": "1/4"
"traits":
- "desc": "Grum'shar is a 1st-level spellcaster. His spellcasting ability is Intelligence.\
    \ He has the following wizard spells prepared:\n\nCantrips (at will): [fire\
    \ bolt](/2-Mechanics/CLI/spells/fire-bolt.md), [mending](/2-Mechanics/CLI/spells/mending.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\n1st level\
    \ (2 slots): [burning hands](/2-Mechanics/CLI/spells/burning-hands.md), [disguise\
    \ self](/2-Mechanics/CLI/spells/disguise-self.md), [shield](/2-Mechanics/CLI/spells/shield.md)"
  "name": "Spellcasting"
- "desc": "When reduced to 0 hit points, Grum'shar drops to 1 hit point instead. He\
    \ can only do this once per long rest."
  "name": "Relentless Endurance"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d4)\
    \ piercing damage. Or Ranged Weapon Attack: +2 to hit, range 20/60 ft., one\
    \ target. Hit: 2 (1d4) piercing damage."
  "name": "Dagger"
"source":
- "WDH"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDH/Grum%27shar.webp"
```
^statblock

```encounter-table
name: Grum'shar
creatures:
 - 1: Grum'shar
```