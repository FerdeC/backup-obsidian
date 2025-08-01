---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/8
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Enna Galakiir (Levels 9-11)"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 8
---
# [Enna Galakiir (Levels 9-11)](2-Mechanics\CLI\bestiary\npc/enna-galakiir-levels-9-11-kftgv.md)
*Source: Keys from the Golden Vault p. 8*  

```statblock
"name": "Enna Galakiir (Levels 9-11) (KftGV)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral"
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
"senses": "passive Perception 13"
"languages": "Thieves' cant plus any two languages"
"cr": "8"
"traits":
- "desc": "During its first turn, Enna Galakiir has advantage on attack rolls against\
    \ any creature that hasn't taken a turn. Any hit Enna Galakiir scores against\
    \ a [surprised](/2-Mechanics/CLI/rules/conditions.md#surprised) creature is a\
    \ critical hit."
  "name": "Assassinate"
- "desc": "If Enna Galakiir is subjected to an effect that allows it to make a Dexterity\
    \ saving throw to take only half damage, Enna Galakiir instead takes no damage\
    \ if it succeeds on the saving throw, and only half damage if it fails."
  "name": "Evasion"
- "desc": "Enna Galakiir deals an extra 14 (4d6) damage when it hits a target with\
    \ a weapon attack and has advantage on the attack roll, or when the target is\
    \ within 5 feet of an ally of Enna Galakiir that isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ and Enna Galakiir doesn't have disadvantage on the attack roll."
  "name": "Sneak Attack (1/Turn)"
"actions":
- "desc": "Enna Galakiir makes two shortsword attacks."
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
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/KftGV/Enna%20Galakiir%20%28Levels%209-11%29.webp"
```
^statblock

```encounter-table
name: Enna Galakiir (Levels 9-11)
creatures:
 - 1: Enna Galakiir (Levels 9-11)
```