---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/rot
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Half-Red Dragon Gladiator"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: The Rise of Tiamat p. 56
---
# [Half-Red Dragon Gladiator](2-Mechanics\CLI\bestiary\humanoid/half-red-dragon-gladiator-rot.md)
*Source: The Rise of Tiamat p. 56*  

```statblock
"name": "Half-Red Dragon Gladiator (RoT)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"stats":
- !!int "18"
- !!int "15"
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "15"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
  "Strength": !!int "7"
  "Constitution": !!int "6"
"skillsaves":
  "Intimidation": !!int "5"
  "Athletics": !!int "10"
"damage_resistances": "fire"
"senses": "blindsight 10 ft., darkvision 60 ft., passive Perception 11"
"languages": "any one language (usually Common), Draconic"
"cr": "5"
"traits":
- "desc": "The half-dragon has advantage on saving throws against being [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Brave"
- "desc": "A melee weapon deals one extra die of its damage when the half-dragon hits\
    \ with it (included in the attack)."
  "name": "Brute"
"actions":
- "desc": "The half-dragon makes three melee attacks or two ranged attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. and range 20/60\
    \ ft., one target. Hit: 11 (2d6 + 4) piercing damage, or 13 (2d8 + 4) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Spear"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. Hit: 9\
    \ (2d4 + 4) bludgeoning damage. If the target is a Medium or smaller creature,\
    \ it must succeed on a DC 15 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Shield Bash"
- "desc": "The half-dragon exhales fire in a 15-foot cone. Each creature in that area\
    \ must make a DC 13 Dexterity saving throw, taking 24 (7d6) fire damage on a\
    \ failed save, or half as much damage on a successful one."
  "name": "Fire Breath (Recharge 5-6)"
"reactions":
- "desc": "The half-dragon adds 3 to its AC against one melee attack that would hit\
    \ it. To do so, the half-dragon must see the attacker and be wielding a melee\
    \ weapon."
  "name": "Parry"
"source":
- "RoT"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/RoT/Half-Red%20Dragon%20Gladiator.webp"
```
^statblock

```encounter-table
name: Half-Red Dragon Gladiator
creatures:
 - 1: Half-Red Dragon Gladiator
```