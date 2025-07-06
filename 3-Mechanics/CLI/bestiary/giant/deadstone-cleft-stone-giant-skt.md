---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/7
- monster/size/huge
- monster/type/giant
aliases: ["Deadstone Cleft Stone Giant"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Storm King's Thunder p. 146
---
# [Deadstone Cleft Stone Giant](2-Mechanics\CLI\bestiary\giant/deadstone-cleft-stone-giant-skt.md)
*Source: Storm King's Thunder p. 146*  

```statblock
"name": "Deadstone Cleft Stone Giant (SKT)"
"size": "Huge"
"type": "giant"
"alignment": "Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "11d12 + 55"
"stats":
- !!int "23"
- !!int "15"
- !!int "20"
- !!int "10"
- !!int "12"
- !!int "9"
"speed": "40 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "4"
  "Constitution": !!int "8"
"skillsaves":
  "Athletics": !!int "12"
  "Perception": !!int "4"
"senses": "darkvision 60 ft., tremorsense 30 ft., passive Perception 14"
"languages": "Giant"
"cr": "7"
"traits":
- "desc": "The giant's innate spellcasting ability is Wisdom. It can innately cast\
    \ the following spells, requiring no material components:\n\n1/day each: [stoneskin](/2-Mechanics/CLI/spells/stoneskin.md),\
    \ [time stop](/2-Mechanics/CLI/spells/time-stop.md)\n\n3/day each: [meld into\
    \ stone](/2-Mechanics/CLI/spells/meld-into-stone.md), [stone shape](/2-Mechanics/CLI/spells/stone-shape.md)"
  "name": "Innate Spellcasting"
- "desc": "The giant meditates for 1 hour, during which time it can do nothing else.\
    \ At the end of the hour, provided the giant's meditation has been uninterrupted,\
    \ it becomes [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified) for 8\
    \ hours. At the end of this time, the giant is no longer petrified and gains tremorsense\
    \ out to a range of 30 feet, as well as a measure of innate spellcasting ability\
    \ for the next 24 hours."
  "name": "Olach Morrah"
- "desc": "The giant has advantage on Dexterity ([Stealth](/2-Mechanics/CLI/rules/skills.md#Stealth))\
    \ checks made to hide in rocky terrain."
  "name": "Stone Camouflage"
"actions":
- "desc": "The giant makes two greatclub attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 15 ft., one target. Hit: 19\
    \ (3d8 + 6) bludgeoning damage."
  "name": "Greatclub"
- "desc": "Ranged Weapon Attack: +9 to hit, range 60/240 ft., one target. Hit:\
    \ 28 (4d10 + 6) bludgeoning damage. If the target is a creature, it must succeed\
    \ on a DC 17 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Rock"
"reactions":
- "desc": "If a rock or similar object is hurled at the giant, the giant can, with\
    \ a successful DC 10 Dexterity saving throw, catch the missile and take no bludgeoning\
    \ damage from it."
  "name": "Rock Catching"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Deadstone%20Cleft%20Stone%20Giant.webp"
```
^statblock

```encounter-table
name: Deadstone Cleft Stone Giant
creatures:
 - 1: Deadstone Cleft Stone Giant
```