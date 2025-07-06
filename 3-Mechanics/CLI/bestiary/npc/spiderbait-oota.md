---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1-4
- monster/size/small
- monster/type/humanoid/goblinoid
aliases: ["Spiderbait"]
NoteIcon: monster
BestiaryType: humanoid (goblinoid)
SourceType: Bestiary
BookSource: Out of the Abyss p. 31
---
# [Spiderbait](2-Mechanics\CLI\bestiary\npc/spiderbait-oota.md)
*Source: Out of the Abyss p. 31*  

```statblock
"name": "Spiderbait (OotA)"
"size": "Small"
"type": "humanoid"
"subtype": "goblinoid"
"alignment": "Neutral"
"ac": !!int "15"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "7"
"hit_dice": "2d6"
"stats":
- !!int "8"
- !!int "14"
- !!int "10"
- !!int "10"
- !!int "8"
- !!int "8"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "3"
  "Stealth": !!int "6"
  "Acrobatics": !!int "6"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Goblin"
"cr": "1/4"
"traits":
- "desc": "Spiderbait can take the Disengage or Hide action as a bonus action on each\
    \ of its turns."
  "name": "Nimble Escape"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) slashing damage."
  "name": "Scimitar"
- "desc": "Ranged Weapon Attack: +4 to hit, range 80/320 ft., one target. Hit:\
    \ 5 (1d6 + 2) piercing damage."
  "name": "Shortbow"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Spiderbait.webp"
```
^statblock

```encounter-table
name: Spiderbait
creatures:
 - 1: Spiderbait
```