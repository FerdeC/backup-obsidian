---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/jttrc
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Dragon Hunter"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Journeys through the Radiant Citadel p. 138
---
# [Dragon Hunter](2-Mechanics\CLI\bestiary\humanoid/dragon-hunter-jttrc.md)
*Source: Journeys through the Radiant Citadel p. 138*  

They were raised together and share conviction that they must slay the bakunawa as vengeance for wrongs done to their clan.

```statblock
"name": "Dragon Hunter (JttRC)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md)"
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
"actions":
- "desc": "The dragon hunter makes two longsword attacks. If it has a shortsword drawn,\
    \ it can also make a shortsword attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands."
  "name": "Longsword"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +3 to hit, ranged 150/600 ft., one target. Hit:\
    \ 5 (1d8 + 1) piercing damage."
  "name": "Longbow"
"source":
- "JttRC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/JttRC/Dragon%20Hunter.webp"
```
^statblock

```encounter-table
name: Dragon Hunter
creatures:
 - 1: Dragon Hunter
```