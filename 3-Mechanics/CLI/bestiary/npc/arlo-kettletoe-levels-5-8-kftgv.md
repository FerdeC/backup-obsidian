---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/halfling
aliases: ["Arlo Kettletoe (Levels 5-8)"]
NoteIcon: monster
BestiaryType: humanoid (halfling)
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 8
---
# [Arlo Kettletoe (Levels 5-8)](2-Mechanics\CLI\bestiary\npc/arlo-kettletoe-levels-5-8-kftgv.md)
*Source: Keys from the Golden Vault p. 8*  

```statblock
"name": "Arlo Kettletoe (Levels 5-8) (KftGV)"
"size": "Medium"
"type": "humanoid"
"subtype": "halfling"
"alignment": "Neutral"
"ac": !!int "18"
"ac_class": "[plate armor](/2-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "16"
- !!int "11"
- !!int "14"
- !!int "11"
- !!int "11"
- !!int "15"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "2"
  "Constitution": !!int "4"
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "3"
"traits":
- "desc": "Arlo Kettletoe has advantage on saving throws against being [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Brave"
"actions":
- "desc": "Arlo Kettletoe makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) slashing damage."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. Hit:\
    \ 5 (1d10) piercing damage."
  "name": "Heavy Crossbow"
- "desc": "For 1 minute, Arlo Kettletoe can utter a special command or warning whenever\
    \ a nonhostile creature that it can see within 30 feet of it makes an attack roll\
    \ or a saving throw. The creature can add a d4 to its roll provided it can hear\
    \ and understand Arlo Kettletoe. A creature can benefit from only one Leadership\
    \ die at a time. This effect ends if Arlo Kettletoe is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Leadership (Recharges after a Short or Long Rest)"
"reactions":
- "desc": "Arlo Kettletoe adds 2 to its AC against one melee attack that would hit\
    \ it. To do so, Arlo Kettletoe must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/KftGV/Arlo%20Kettletoe%20%28Levels%205-8%29.webp"
```
^statblock

```encounter-table
name: Arlo Kettletoe (Levels 5-8)
creatures:
 - 1: Arlo Kettletoe (Levels 5-8)
```