---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Axe of Mirabar Soldier"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 98
---
# [Axe of Mirabar Soldier](2-Mechanics\CLI\bestiary\humanoid/axe-of-mirabar-soldier-skt.md)
*Source: Storm King's Thunder p. 98*  

```statblock
"name": "Axe of Mirabar Soldier (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[plate armor](/2-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"stats":
- !!int "16"
- !!int "13"
- !!int "16"
- !!int "10"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "5"
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "Common, Dwarvish"
"cr": "3"
"actions":
- "desc": "The soldier makes two battleaxe attacks. If it has a handaxe drawn, it\
    \ can also make a handaxe attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands."
  "name": "Battleaxe"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 6 (1d6 + 3) slashing damage."
  "name": "Handaxe"
- "desc": "Ranged Weapon Attack: +3 to hit, range 100/400 ft., one target. Hit:\
    \ 6 (1d10 + 1) piercing damage."
  "name": "Heavy Crossbow"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Axe%20of%20Mirabar%20Soldier.webp"
```
^statblock

```encounter-table
name: Axe of Mirabar Soldier
creatures:
 - 1: Axe of Mirabar Soldier
```