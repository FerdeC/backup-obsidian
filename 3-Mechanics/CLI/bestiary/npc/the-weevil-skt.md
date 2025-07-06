---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["The Weevil"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 114
---
# [The Weevil](2-Mechanics\CLI\bestiary\npc/the-weevil-skt.md)
*Source: Storm King's Thunder p. 114*  

```statblock
"name": "The Weevil (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
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
- "desc": "The Weevil makes three melee attacks with his handaxes. Or the Weevil makes\
    \ two ranged attacks with his handaxes."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 4) slashing damage."
  "name": "Handaxe +1"
"reactions":
- "desc": "The Weevil adds 2 to its AC against one melee attack that would hit it.\
    \ To do so, the Weevil must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/The%20Weevil.webp"
```
^statblock

```encounter-table
name: The Weevil
creatures:
 - 1: The Weevil
```