---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wbtw
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Alagarthas"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: The Wild Beyond the Witchlight p. 144
---
# [Alagarthas](2-Mechanics\CLI\bestiary\npc/alagarthas-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 144*  

This prince made a bargain with Endelyn Moongrave and is paying the price. He longs to return to his home in the Misty Forest and deal with the threat of an evil green dragon that nests there.

```statblock
"name": "Alagarthas (WBtW)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Chaotic Good"
"ac": !!int "10"
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
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Elvish"
"cr": "3"
"traits":
- "desc": "Alagarthas has advantage on saving throws against being [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Brave"
- "desc": "Alagarthas has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put him to sleep."
  "name": "Fey Ancestry"
"actions":
- "desc": "Alagarthas makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 4 bludgeoning\
    \ damage."
  "name": "Unarmed Strike"
- "desc": "For 1 minute, Alagarthas can utter a special command or warning whenever\
    \ a nonhostile creature that it can see within 30 feet of it makes an attack roll\
    \ or a saving throw. The creature can add a d4 to its roll provided it can hear\
    \ and understand him. A creature can benefit from only one Leadership die at a\
    \ time. This effect ends if Alagarthas is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Leadership (Recharges after a Short or Long Rest)"
"source":
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WBtW/Alagarthas.webp"
```
^statblock

```encounter-table
name: Alagarthas
creatures:
 - 1: Alagarthas
```