---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/1
- monster/size/large
- monster/type/beast
aliases: ["Snow Leopard"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 183
---
# [Snow Leopard](2-Mechanics\CLI\bestiary\beast/snow-leopard-tftyp.md)
*Source: Tales from the Yawning Portal p. 183*  

```statblock
"name": "Snow Leopard (TftYP)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "37"
"hit_dice": "5d10 + 10"
"stats":
- !!int "17"
- !!int "15"
- !!int "14"
- !!int "3"
- !!int "12"
- !!int "8"
"speed": "40 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": ""
"cr": "1"
"traits":
- "desc": "The leopard has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "If the leopard moves at least 20 feet straight toward a creature and then\
    \ hits it with a claw attack on the same turn, that target must succeed on a DC\
    \ 13 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone).\
    \ If the target is [prone](/2-Mechanics/CLI/rules/conditions.md#prone), the leopard\
    \ can make one bite attack against it as a bonus action."
  "name": "Pounce"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (1d10\
    \ + 3) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage."
  "name": "Claw"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Snow%20Leopard.webp"
```
^statblock

```encounter-table
name: Snow Leopard
creatures:
 - 1: Snow Leopard
```