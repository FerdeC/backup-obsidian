---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/10
- monster/size/huge
- monster/type/dragon
aliases: ["Ignia"]
NoteIcon: monster
BestiaryType: dragon
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 184
---
# [Ignia](2-Mechanics\CLI\bestiary\npc/ignia-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 184*  

```statblock
"name": "Ignia (DSotDQ)"
"size": "Huge"
"type": "dragon"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "178"
"hit_dice": "17d10 + 85"
"stats":
- !!int "23"
- !!int "10"
- !!int "21"
- !!int "14"
- !!int "11"
- !!int "19"
"speed": "40 ft., climb 40 ft., fly 80 ft."
"saves":
  "Charisma": !!int "8"
  "Dexterity": !!int "4"
  "Wisdom": !!int "4"
  "Constitution": !!int "9"
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "8"
"damage_immunities": "fire"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 18"
"languages": "Common, Draconic"
"cr": "10"
"actions":
- "desc": "Ignia makes three attacks: one with its bite and two with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 17\
    \ (2d10 + 6) piercing damage plus 3 (1d6) fire damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d6 + 6) slashing damage."
  "name": "Claw"
- "desc": "Ignia exhales fire in a 30-foot cone. Each creature in that area must make\
    \ a DC 17 Dexterity saving throw, taking 56 (16d6) fire damage on a failed save,\
    \ or half as much damage on a successful one."
  "name": "Fire Breath (Recharge 5-6)"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Ignia.webp"
```
^statblock

```encounter-table
name: Ignia
creatures:
 - 1: Ignia
```