---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/8
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Rool"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 221
---
# [Rool](2-Mechanics\CLI\bestiary\npc/rool-skt.md)
*Source: Storm King's Thunder p. 221*  

```statblock
"name": "Rool (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"stats":
- !!int "11"
- !!int "16"
- !!int "14"
- !!int "13"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "6"
  "Intelligence": !!int "4"
"skillsaves":
  "Deception": !!int "3"
  "Stealth": !!int "9"
  "Perception": !!int "3"
  "Acrobatics": !!int "6"
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Thieves' cant plus any two languages, Orc"
"cr": "8"
"traits":
- "desc": "During its first turn, Rool has advantage on attack rolls against any creature\
    \ that hasn't taken a turn. Any hit Rool scores against a [surprised](/2-Mechanics/CLI/rules/conditions.md#surprised)\
    \ creature is a critical hit."
  "name": "Assassinate"
- "desc": "If Rool is subjected to an effect that allows it to make a Dexterity saving\
    \ throw to take only half damage, Rool instead takes no damage if it succeeds\
    \ on the saving throw, and only half damage if it fails."
  "name": "Evasion"
- "desc": "Rool deals an extra 14 (4d6) damage when it hits a target with a weapon\
    \ attack and has advantage on the attack roll, or when the target is within 5\
    \ feet of an ally of Rool that isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ and Rool doesn't have disadvantage on the attack roll."
  "name": "Sneak Attack (1/Turn)"
- "desc": "Rool"
  "name": "Relentless Endurance"
"actions":
- "desc": "Rool makes two shortsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage, and the target must make a DC 15 Constitution saving\
    \ throw, taking 24 (7d6) poison damage on a failed save, or half as much damage\
    \ on a successful one."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +6 to hit, range 80/320 ft., one target. Hit:\
    \ 7 (1d8 + 3) piercing damage, and the target must make a DC 15 Constitution\
    \ saving throw, taking 24 (7d6) poison damage on a failed save, or half as much\
    \ damage on a successful one."
  "name": "Light Crossbow"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Rool.webp"
```
^statblock

```encounter-table
name: Rool
creatures:
 - 1: Rool
```