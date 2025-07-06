---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Gondolo"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 34
---
# [Gondolo](2-Mechanics\CLI\bestiary\npc/gondolo-toa.md)
*Source: Tomb of Annihilation p. 34*  

```statblock
"name": "Gondolo (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Good"
"ac": !!int "13"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "13"
"hit_dice": "3d6 + 3"
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
"senses": "passive Perception 15"
"languages": "any one language (usually Common), Halfling"
"cr": "1/2"
"traits":
- "desc": "Gondolo has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or sight."
  "name": "Keen Hearing and Sight"
- "desc": "Gondolo"
  "name": "Halfling Nimbleness"
- "desc": "Gondolo"
  "name": "Brave"
"actions":
- "desc": "Gondolo makes two melee attacks or two ranged attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +4 to hit, ranged 150/600 ft., one target. Hit:\
    \ 6 (1d8 + 2) piercing damage."
  "name": "Longbow"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Gondolo.webp"
```
^statblock

```encounter-table
name: Gondolo
creatures:
 - 1: Gondolo
```