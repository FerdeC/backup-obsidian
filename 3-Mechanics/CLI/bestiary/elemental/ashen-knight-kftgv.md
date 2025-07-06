---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/3
- monster/size/medium
- monster/type/elemental/any-race
aliases: ["Ashen Knight"]
NoteIcon: monster
BestiaryType: elemental (any race)
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 158
---
# [Ashen Knight](2-Mechanics\CLI\bestiary\elemental/ashen-knight-kftgv.md)
*Source: Keys from the Golden Vault p. 158*  

Knights are warriors who pledge service to rulers, religious orders, and noble causes. A knight's alignment determines the extent to which a pledge is honored. Whether undertaking a quest or patrolling a realm, a knight often travels with an entourage that includes squires and hirelings who are commoners.

```statblock
"name": "Ashen Knight (KftGV)"
"size": "Medium"
"type": "elemental"
"subtype": "any race"
"alignment": "Lawful Evil"
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
"damage_immunities": "fire"
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "3"
"traits":
- "desc": "The ashen knight has advantage on saving throws against being [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Brave"
- "desc": "When the knight drops to 0 hit points, it is reduced to a pile of ash,\
    \ and any equipment it was wearing or carrying falls to the ground."
  "name": "Ashen Creature"
"actions":
- "desc": "The ashen knight makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) slashing damage."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. Hit:\
    \ 5 (1d10) piercing damage."
  "name": "Heavy Crossbow"
- "desc": "For 1 minute, the ashen knight can utter a special command or warning whenever\
    \ a nonhostile creature that it can see within 30 feet of it makes an attack roll\
    \ or a saving throw. The creature can add a d4 to its roll provided it can hear\
    \ and understand the ashen knight. A creature can benefit from only one Leadership\
    \ die at a time. This effect ends if the ashen knight is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Leadership (Recharges after a Short or Long Rest)"
"reactions":
- "desc": "The ashen knight adds 2 to its AC against one melee attack that would hit\
    \ it. To do so, the ashen knight must see the attacker and be wielding a melee\
    \ weapon."
  "name": "Parry"
"source":
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/KftGV/Ashen%20Knight.webp"
```
^statblock

```encounter-table
name: Ashen Knight
creatures:
 - 1: Ashen Knight
```