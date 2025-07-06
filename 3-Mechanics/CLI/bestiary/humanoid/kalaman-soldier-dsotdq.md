---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/1-2
- monster/size/small-or-medium
- monster/type/humanoid
aliases: ["Kalaman Soldier"]
NoteIcon: monster
BestiaryType: humanoid
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 202
---
# [Kalaman Soldier](2-Mechanics\CLI\bestiary\humanoid/kalaman-soldier-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 202*  

Kalaman soldiers are the rank-and-file troops of the army of Kalaman. They are trained to fight defensively, bolstering one another in battle.

```statblock
"name": "Kalaman Soldier (DSotDQ)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[chain mail](/2-Mechanics/CLI/items/chain-mail.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"stats":
- !!int "13"
- !!int "12"
- !!int "12"
- !!int "10"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "3"
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "1/2"
"actions":
- "desc": "The soldier makes two Longsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with two hands."
  "name": "Longsword"
"reactions":
- "desc": "If an ally within 5 feet of the soldier must make a saving throw, the soldier\
    \ encourages the ally, granting advantage on the roll."
  "name": "Hold the Line"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Kalaman%20Soldier.webp"
```
^statblock

```encounter-table
name: Kalaman Soldier
creatures:
 - 1: Kalaman Soldier
```