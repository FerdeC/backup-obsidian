---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/half-elf
aliases: ["Xolkin Alassandar"]
NoteIcon: monster
BestiaryType: humanoid (half-elf)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 27
---
# [Xolkin Alassandar](2-Mechanics\CLI\bestiary\npc/xolkin-alassandar-skt.md)
*Source: Storm King's Thunder p. 27*  

```statblock
"name": "Xolkin Alassandar (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-elf"
"alignment": "Lawful Evil"
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
- "desc": "Xolkin makes three melee attacks: two with its scimitar and one with its\
    \ dagger. Or Xolkin makes two ranged attacks with its daggers."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Scimitar"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage."
  "name": "Dagger"
"reactions":
- "desc": "Xolkin adds 2 to its AC against one melee attack that would hit it. To\
    \ do so, Xolkin must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Xolkin%20Alassandar.webp"
```
^statblock

```encounter-table
name: Xolkin Alassandar
creatures:
 - 1: Xolkin Alassandar
```