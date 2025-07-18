---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/6
- monster/size/medium
- monster/type/humanoid/sahuagin
aliases: ["Sahuagin Blademaster"]
NoteIcon: monster
BestiaryType: humanoid (sahuagin)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 249
---
# [Sahuagin Blademaster](2-Mechanics\CLI\bestiary\humanoid/sahuagin-blademaster-gos.md)
*Source: Ghosts of Saltmarsh p. 249*  

A cunning veteran of countless campaigns, the sahuagin blademaster decorates its armor with the bones of its defeated foes. As demonstrated in The Final Enemy, sahuagin blademasters often serve as officers in the sa huagin army.

```statblock
"name": "Sahuagin Blademaster (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "sahuagin"
"alignment": "Lawful Evil"
"ac": !!int "20"
"ac_class": "[plate armor](/2-Mechanics/CLI/items/plate-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "97"
"hit_dice": "15d8 + 30"
"stats":
- !!int "16"
- !!int "12"
- !!int "14"
- !!int "12"
- !!int "11"
- !!int "12"
"speed": "30 ft., swim 40 ft."
"saves":
  "Strength": !!int "6"
  "Constitution": !!int "5"
"skillsaves":
  "Intimidation": !!int "4"
  "Athletics": !!int "6"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "Sahuagin"
"cr": "6"
"traits":
- "desc": "The blademaster has advantage on melee attack rolls against any creature\
    \ that doesn't have all its hit points."
  "name": "Blood Frenzy"
- "desc": "The blademaster can breathe air and water, but it needs to be submerged\
    \ at least once every 4 hours to avoid suffocating."
  "name": "Limited Amphibiousness"
- "desc": "The blademaster can magically command any shark within 120 feet of it,\
    \ using a limited telepathy."
  "name": "Shark Telepathy"
"actions":
- "desc": "The blademaster makes three attacks with its wavecutter blade, or one attack\
    \ with its bite and two with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d8 + 3) slashing damage."
  "name": "Wavecutter Blade"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d10\
    \ + 3) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage."
  "name": "Claws"
"source":
- "GoS"
- "SDW"
- "LR"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Sahuagin%20Blademaster.webp"
```
^statblock

```encounter-table
name: Sahuagin Blademaster
creatures:
 - 1: Sahuagin Blademaster
```