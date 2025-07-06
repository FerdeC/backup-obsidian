---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/1-4
- monster/size/medium
- monster/type/humanoid/dwarf
aliases: ["Panopticus Wizard"]
NoteIcon: monster
BestiaryType: humanoid (dwarf)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 106
---
# [Panopticus Wizard](2-Mechanics\CLI\bestiary\humanoid/panopticus-wizard-wdh.md)
*Source: Waterdeep: Dragon Heist p. 106*  

This bald-headed and tattooed dwarf operates Xanathar's "panopticus" magical surveillance system.

Apprentice wizards are novice arcane spellcasters who serve more experienced wizards or attend school. They perform menial work, such as cooking and cleaning, in exchange for education in the ways of magic.

```statblock
"name": "Panopticus Wizard (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Neutral"
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
"speed": "25 ft."
"skillsaves":
  "History": !!int "4"
  "Arcana": !!int "4"
"damage_resistances": "poison"
"senses": "passive Perception 10"
"languages": "Common, Dwarvish"
"cr": "1/4"
"traits":
- "desc": "The Dwarf is a 1st-level spellcaster. Its spellcasting ability is Intelligence.\
    \ It has the following wizard spells prepared:\n\nCantrips (at will): [fire\
    \ bolt](/2-Mechanics/CLI/spells/fire-bolt.md), [mending](/2-Mechanics/CLI/spells/mending.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\n1st level\
    \ (2 slots): [burning hands](/2-Mechanics/CLI/spells/burning-hands.md), [disguise\
    \ self](/2-Mechanics/CLI/spells/disguise-self.md), [shield](/2-Mechanics/CLI/spells/shield.md)"
  "name": "Spellcasting"
- "desc": "The dwarf has advantage on saving throws against poison and resistance\
    \ to poison damage."
  "name": "Dwarven Resilience"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d4)\
    \ piercing damage. Or Ranged Weapon Attack: +2 to hit, range 20/60 ft., one\
    \ target. Hit: 2 (1d4) piercing damage."
  "name": "Dagger"
"source":
- "WDH"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDH/Panopticus%20Wizard.webp"
```
^statblock

```encounter-table
name: Panopticus Wizard
creatures:
 - 1: Panopticus Wizard
```