---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Narbeck Horn"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 114
---
# [Narbeck Horn](2-Mechanics\CLI\bestiary\npc/narbeck-horn-skt.md)
*Source: Storm King's Thunder p. 114*  

```statblock
"name": "Narbeck Horn (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
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
- "desc": "Narbeck has advantage on saving throws against being [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Brave"
"actions":
- "desc": "Narbeck makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 9 (1d12\
    \ + 3) slashing damage."
  "name": "Greataxe"
- "desc": "Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. Hit:\
    \ 5 (1d10) piercing damage."
  "name": "Heavy Crossbow"
- "desc": "For 1 minute, Narbeck can utter a special command or warning whenever a\
    \ nonhostile creature that it can see within 30 feet of it makes an attack roll\
    \ or a saving throw. The creature can add a d4 to its roll provided it can hear\
    \ and understand Narbeck. A creature can benefit from only one Leadership die\
    \ at a time. This effect ends if Narbeck is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Leadership (Recharges after a Short or Long Rest)"
"reactions":
- "desc": "Narbeck adds 2 to its AC against one melee attack that would hit it. To\
    \ do so, Narbeck must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Narbeck%20Horn.webp"
```
^statblock

```encounter-table
name: Narbeck Horn
creatures:
 - 1: Narbeck Horn
```