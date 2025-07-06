---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/jttrc
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Farmer"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Journeys through the Radiant Citadel p. 36
---
# [Farmer](2-Mechanics\CLI\bestiary\npc/farmer-jttrc.md)
*Source: Journeys through the Radiant Citadel p. 36*  

```statblock
"name": "Farmer (JttRC)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Good alignment"
"ac": !!int "12"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "11"
- !!int "12"
- !!int "10"
- !!int "10"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "2"
  "Religion": !!int "2"
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "1/8"
"traits":
- "desc": "The farmer has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Dark Devotion"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one creature. Hit: 4\
    \ (1d6 + 1) slashing damage."
  "name": "Scimitar"
"source":
- "JttRC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/JttRC/Farmer.webp"
```
^statblock

```encounter-table
name: Farmer
creatures:
 - 1: Farmer
```