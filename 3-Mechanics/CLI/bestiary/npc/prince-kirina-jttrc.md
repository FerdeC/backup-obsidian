---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/jttrc
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Prince Kirina"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Journeys through the Radiant Citadel p. 94
---
# [Prince Kirina](2-Mechanics\CLI\bestiary\npc/prince-kirina-jttrc.md)
*Source: Journeys through the Radiant Citadel p. 94*  

```statblock
"name": "Prince Kirina (JttRC)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "11"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"stats":
- !!int "16"
- !!int "13"
- !!int "14"
- !!int "10"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "5"
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "any one language (usually Common)"
"cr": "3"
"traits":
- "desc": "If Kirina is reduced to half of his hit points or fewer, he uses the [Dodge](/2-Mechanics/CLI/rules/actions.md#Dodge)\
    \ action to avoid taking further damage."
  "name": "Royal Blood"
"actions":
- "desc": "Kirina makes two longsword attacks. If it has a shortsword drawn, it can\
    \ also make a shortsword attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands."
  "name": "Longsword"
"source":
- "JttRC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/JttRC/Prince%20Kirina.webp"
```
^statblock

```encounter-table
name: Prince Kirina
creatures:
 - 1: Prince Kirina
```