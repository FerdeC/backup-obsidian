---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cos
- monster/cr/3
- monster/size/large
- monster/type/beast
aliases: ["Armored Saber-Toothed Tiger"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Curse of Strahd p. 115
---
# [Armored Saber-Toothed Tiger](2-Mechanics\CLI\bestiary\beast/armored-saber-toothed-tiger-cos.md)
*Source: Curse of Strahd p. 115*  

```statblock
"name": "Armored Saber-Toothed Tiger (CoS)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "[half plate armor](/2-Mechanics/CLI/items/half-plate-armor.md)"
"hp": !!int "84"
"hit_dice": "7d10 + 14"
"stats":
- !!int "18"
- !!int "14"
- !!int "15"
- !!int "3"
- !!int "12"
- !!int "8"
"speed": "40 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "3"
"traits":
- "desc": "The tiger has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "If the tiger moves at least 20 feet straight toward a creature and then\
    \ hits it with a claw attack on the same turn, that target must succeed on a DC\
    \ 14 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone).\
    \ If the target is [prone](/2-Mechanics/CLI/rules/conditions.md#prone), the tiger\
    \ can make one bite attack against it as a bonus action."
  "name": "Pounce"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
    \ (1d10 + 5) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) slashing damage."
  "name": "Claw"
"source":
- "CoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CoS/Armored%20Saber-Toothed%20Tiger.webp"
```
^statblock

```encounter-table
name: Armored Saber-Toothed Tiger
creatures:
 - 1: Armored Saber-Toothed Tiger
```