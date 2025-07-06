---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Wood Elf"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 28
---
# [Wood Elf](2-Mechanics\CLI\bestiary\humanoid/wood-elf-skt.md)
*Source: Storm King's Thunder p. 28*  

```statblock
"name": "Wood Elf (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Good"
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
"speed": "30 ft."
"skillsaves":
  "Nature": !!int "4"
  "Stealth": !!int "6"
  "Perception": !!int "5"
  "Survival": !!int "5"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common, Elvish"
"cr": "1/2"
"traits":
- "desc": "The wood elf has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or sight."
  "name": "Keen Hearing and Sight"
- "desc": "The wood elf"
  "name": "Fey Ancestry"
- "desc": "The wood elf"
  "name": "Mask of the Wild"
"actions":
- "desc": "The wood elf makes two melee attacks or two ranged attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +4 to hit, ranged 150/600 ft., one target. Hit:\
    \ 6 (1d8 + 2) piercing damage."
  "name": "Longbow"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Wood%20Elf.webp"
```
^statblock

```encounter-table
name: Wood Elf
creatures:
 - 1: Wood Elf
```