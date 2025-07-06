---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/9
- monster/size/huge
- monster/type/giant
aliases: ["Duchess Brimskarda"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Storm King's Thunder p. 185
---
# [Duchess Brimskarda](2-Mechanics\CLI\bestiary\npc/duchess-brimskarda-skt.md)
*Source: Storm King's Thunder p. 185*  

```statblock
"name": "Duchess Brimskarda (SKT)"
"size": "Huge"
"type": "giant"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "dragon-scale dress"
"hp": !!int "162"
"hit_dice": "13d12 + 78"
"stats":
- !!int "25"
- !!int "9"
- !!int "23"
- !!int "14"
- !!int "14"
- !!int "13"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Dexterity": !!int "3"
  "Constitution": !!int "10"
"skillsaves":
  "Athletics": !!int "11"
  "Perception": !!int "6"
"damage_immunities": "fire"
"senses": "passive Perception 16"
"languages": "Common, Giant, Goblin"
"cr": "9"
"traits":
- "desc": "Brimskarda carries a [potion of invisibility](/2-Mechanics/CLI/items/potion-of-invisibility.md),\
    \ which she quaffs on her first turn in combat."
  "name": "Special Equipment"
"actions":
- "desc": "The giant makes two greatsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 28\
    \ (6d6 + 7) slashing damage."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +11 to hit, range 60/240 ft., one target. Hit:\
    \ 29 (4d10 + 7) bludgeoning damage."
  "name": "Iron Cauldron"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Duchess%20Brimskarda.webp"
```
^statblock

```encounter-table
name: Duchess Brimskarda
creatures:
 - 1: Duchess Brimskarda
```