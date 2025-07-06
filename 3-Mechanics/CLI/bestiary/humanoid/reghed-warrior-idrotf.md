---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Reghed Warrior"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 152
---
# [Reghed Warrior](2-Mechanics\CLI\bestiary\humanoid/reghed-warrior-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 152*  

Tribal warriors live beyond civilization, most often subsisting on fishing and hunting. Each tribe acts in accordance with the wishes of its chief, who is the greatest or oldest warrior of the tribe or a tribe member blessed by the gods.

```statblock
"name": "Reghed Warrior (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "13"
- !!int "11"
- !!int "12"
- !!int "8"
- !!int "11"
- !!int "8"
"speed": "30 ft."
"skillsaves":
  "Survival": !!int "4"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "1/8"
"traits":
- "desc": "The warrior has advantage on an attack roll against a creature if at least\
    \ one of the warrior's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d6 + 1) piercing damage, or 5 (1d8 + 1) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Spear"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Reghed%20Warrior.webp"
```
^statblock

```encounter-table
name: Reghed Warrior
creatures:
 - 1: Reghed Warrior
```