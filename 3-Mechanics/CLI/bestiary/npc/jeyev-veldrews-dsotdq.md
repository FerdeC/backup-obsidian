---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Jeyev Veldrews"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 75
---
# [Jeyev Veldrews](2-Mechanics\CLI\bestiary\npc/jeyev-veldrews-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 75*  

```statblock
"name": "Jeyev Veldrews (DSotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "15"
- !!int "16"
- !!int "14"
- !!int "14"
- !!int "11"
- !!int "14"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "2"
  "Strength": !!int "4"
"skillsaves":
  "Athletics": !!int "4"
  "Deception": !!int "4"
"senses": "passive Perception 10"
"languages": "any two languages"
"cr": "2"
"actions":
- "desc": "Jeyev makes three melee attacks: two with its scimitar and one with its\
    \ dagger. Or Jeyev makes two ranged attacks with its daggers."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Scimitar"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage."
  "name": "Dagger"
"reactions":
- "desc": "Jeyev adds 2 to its AC against one melee attack that would hit it. To do\
    \ so, Jeyev must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Jeyev%20Veldrews.webp"
```
^statblock

```encounter-table
name: Jeyev Veldrews
creatures:
 - 1: Jeyev Veldrews
```