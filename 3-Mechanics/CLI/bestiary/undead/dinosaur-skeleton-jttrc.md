---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/jttrc
- monster/cr/2
- monster/size/large
- monster/type/undead
aliases: ["Dinosaur Skeleton"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Journeys through the Radiant Citadel p. 57
---
# [Dinosaur Skeleton](2-Mechanics\CLI\bestiary\undead/dinosaur-skeleton-jttrc.md)
*Source: Journeys through the Radiant Citadel p. 57*  

These giant skeletons were unearthed shortly before the silver in the mine ran out, inspiring talk that the mine was cursed. When Teocín first joined Itzmin here, she drew on the power of Pazuzu to turn these skeletons into guardians.

```statblock
"name": "Dinosaur Skeleton (JttRC)"
"size": "Large"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "51"
"hit_dice": "6d10 + 18"
"stats":
- !!int "19"
- !!int "13"
- !!int "17"
- !!int "2"
- !!int "12"
- !!int "5"
"speed": "60 ft."
"skillsaves":
  "Perception": !!int "5"
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": ""
"cr": "2"
"traits":
- "desc": "If the skeleton moves at least 30 feet straight toward a creature and then\
    \ hits it with a claw attack on the same turn, that target must succeed on a DC\
    \ 13 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone).\
    \ If the target is [prone](/2-Mechanics/CLI/rules/conditions.md#prone), the skeleton\
    \ can make one bite attack against it as a bonus action."
  "name": "Pounce"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 15\
    \ (2d10 + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) slashing damage."
  "name": "Claw"
"source":
- "JttRC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/JttRC/Dinosaur%20Skeleton.webp"
```
^statblock

```encounter-table
name: Dinosaur Skeleton
creatures:
 - 1: Dinosaur Skeleton
```