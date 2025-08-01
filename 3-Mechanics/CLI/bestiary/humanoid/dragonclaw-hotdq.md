---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/hotdq
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Dragonclaw"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Hoard of the Dragon Queen p. 89, The Rise of Tiamat p. 89
---
# [Dragonclaw](2-Mechanics\CLI\bestiary\humanoid/dragonclaw-hotdq.md)
*Source: Hoard of the Dragon Queen p. 89, The Rise of Tiamat p. 89*  

```statblock
"name": "Dragonclaw (HotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "14"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"stats":
- !!int "9"
- !!int "16"
- !!int "13"
- !!int "11"
- !!int "10"
- !!int "12"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "2"
"skillsaves":
  "Deception": !!int "3"
  "Stealth": !!int "5"
"senses": "passive Perception 10"
"languages": "Common, Draconic"
"cr": "1"
"traits":
- "desc": "The dragonclaw has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened). While the\
    \ dragonclaw can see a dragon or higher-ranking Cult of the Dragon cultist friendly\
    \ to it, the dragonclaw ignores the effects of being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Dragon Fanatic"
- "desc": "Once per turn, if the dragonclaw makes a weapon attack with advantage on\
    \ the attack roll and hits, it deals an extra 7 (2d6) damage."
  "name": "Fanatic Advantage"
- "desc": "The dragonclaw has advantage on an attack roll against a creature if at\
    \ least one of the dragonclaw's allies is within 5 feet of the creature and the\
    \ ally isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "The dragonclaw attacks twice with its scimitar."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Scimitar"
"source":
- "HotDQ"
- "RoT"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/HotDQ/Dragonclaw.webp"
```
^statblock

```encounter-table
name: Dragonclaw
creatures:
 - 1: Dragonclaw
```