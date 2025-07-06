---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Sea Elf Scout"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 114
---
# [Sea Elf Scout](2-Mechanics\CLI\bestiary\humanoid/sea-elf-scout-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 114*  

```statblock
"name": "Sea Elf Scout (DSotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"stats":
- !!int "11"
- !!int "14"
- !!int "12"
- !!int "11"
- !!int "13"
- !!int "11"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Nature": !!int "4"
  "Stealth": !!int "6"
  "Perception": !!int "5"
  "Survival": !!int "5"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Any one language (usually Common)"
"cr": "1/2"
"traits":
- "desc": "The scout has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or sight."
  "name": "Keen Hearing and Sight"
- "desc": "The scout has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put it to sleep."
  "name": "Fey Ancestry"
- "desc": "The scout can breathe air and water."
  "name": "Child of the Sea"
"actions":
- "desc": "The scout makes two melee attacks or two ranged attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +4 to hit, ranged 150/600 ft., one target. Hit:\
    \ 6 (1d8 + 2) piercing damage."
  "name": "Longbow"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Sea%20Elf%20Scout.webp"
```
^statblock

```encounter-table
name: Sea Elf Scout
creatures:
 - 1: Sea Elf Scout
```