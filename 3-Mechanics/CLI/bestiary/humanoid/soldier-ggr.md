---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/ggr
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Soldier"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 226, Mythic Odysseys of Theros
---
# [Soldier](2-Mechanics\CLI\bestiary\humanoid/soldier-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 226, Mythic Odysseys of Theros*  

```statblock
"name": "Soldier (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[chain mail](/2-Mechanics/CLI/items/chain-mail.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"stats":
- !!int "13"
- !!int "12"
- !!int "12"
- !!int "10"
- !!int "11"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "3"
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "any one language (usually Common)"
"cr": "1/2"
"traits":
- "desc": "The soldier has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled),\
    \ or [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained) while it is\
    \ within 5 feet of at least one ally."
  "name": "Formation Tactics"
"actions":
- "desc": "The soldier makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with two hands."
  "name": "Longsword"
"source":
- "GGR"
- "MOT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GGR/Soldier.webp"
```
^statblock

```encounter-table
name: Soldier
creatures:
 - 1: Soldier
```