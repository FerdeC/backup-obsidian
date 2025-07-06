---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/hotdq
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Dragonwing"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Hoard of the Dragon Queen p. 90, The Rise of Tiamat p. 89
---
# [Dragonwing](2-Mechanics\CLI\bestiary\humanoid/dragonwing-hotdq.md)
*Source: Hoard of the Dragon Queen p. 90, The Rise of Tiamat p. 89*  

```statblock
"name": "Dragonwing (HotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "14"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "11"
- !!int "16"
- !!int "13"
- !!int "11"
- !!int "11"
- !!int "13"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "2"
"skillsaves":
  "Deception": !!int "3"
  "Stealth": !!int "5"
"damage_resistances": "one of the following: acid, cold, fire, lightning, poison"
"senses": "passive Perception 10"
"languages": "Common, Draconic"
"cr": "2"
"traits":
- "desc": "The dragonwing has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened). While the\
    \ dragonwing can see a dragon or higher-ranking Cult of the Dragon cultist friendly\
    \ to it, the dragonwing ignores the effects of being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Dragon Fanatic"
- "desc": "Once per turn, if the dragonwing makes a weapon attack with advantage on\
    \ the attack roll and hits, the target takes an extra 7 (2d6) damage."
  "name": "Fanatic Advantage"
- "desc": "The dragonwing can use a bonus action to gain a flying speed of 30 feet\
    \ until the end of its turn."
  "name": "Limited Flight"
- "desc": "The dragonwing has advantage on an attack roll against a creature if at\
    \ least one of the dragonwing's allies is within 5 feet of the creature and the\
    \ ally isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "The dragonwing attacks twice with its scimitar."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage plus 3 (1d6) damage of the type to which the cultist\
    \ has resistance."
  "name": "Scimitar"
"source":
- "HotDQ"
- "RoT"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/HotDQ/Dragonwing.webp"
```
^statblock

```encounter-table
name: Dragonwing
creatures:
 - 1: Dragonwing
```