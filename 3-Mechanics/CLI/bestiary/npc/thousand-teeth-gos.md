---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/6
- monster/size/large
- monster/type/monstrosity
aliases: ["Thousand Teeth"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 256
---
# [Thousand Teeth](2-Mechanics\CLI\bestiary\npc/thousand-teeth-gos.md)
*Source: Ghosts of Saltmarsh p. 256*  

Thousand Teeth is an ancient crocodilian nightmare that has served as the apex predator in the swamps near Saltmarsh for as long as anyone can remember. This monster recently fought a number of lizardfolk and lost one of its teeth. Angered and hungry, it sulks in its lair, lost in primal dreams of rending and tearing. It is found in the deep marshes in Danger at Dunwater.

```statblock
"name": "Thousand Teeth (GoS)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "93"
"hit_dice": "11d10 + 33"
"stats":
- !!int "19"
- !!int "10"
- !!int "17"
- !!int "2"
- !!int "10"
- !!int "7"
"speed": "30 ft., swim 50 ft."
"saves":
  "Strength": !!int "7"
  "Constitution": !!int "6"
"skillsaves":
  "Athletics": !!int "7"
  "Stealth": !!int "3"
"senses": "passive Perception 10"
"languages": ""
"cr": "6"
"traits":
- "desc": "Thousand Teeth can hold its breath for 30 minutes."
  "name": "Hold Breath"
- "desc": "If Thousand Teeth fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (2/Day)"
"actions":
- "desc": "Thousand Teeth makes two attacks: one with its bite and one with its tail."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 15\
    \ (2d10 + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 8\
    \ (1d8 + 4) bludgeoning damage. If the target is a creature, it must succeed\
    \ on a DC 15 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Tail"
"legendary_actions":
- "desc": "Thousand Teeth makes a Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ check."
  "name": "Detect"
- "desc": "Thousand Teeth moves up to half its speed."
  "name": "Lunge"
- "desc": "Thousand Teeth makes a bite attack."
  "name": "Bite (Costs 2 Actions)"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Thousand%20Teeth.webp"
```
^statblock

```encounter-table
name: Thousand Teeth
creatures:
 - 1: Thousand Teeth
```