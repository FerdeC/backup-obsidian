---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Reghed Chieftain"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 152
---
# [Reghed Chieftain](2-Mechanics\CLI\bestiary\humanoid/reghed-chieftain-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 152*  

## Reghed Nomads

Reghed nomads are the children of the Reghed Glacier, as suggested by their name. They are people of the wild, as revealed by their tribal names—the Elk, the Tiger, the Wolf, the Bear. They are the tribes of Icewind Dale, proud and strong, bound to ancient traditions that have kept them alive through countless harsh winters. The Reghed wear heavy furs as well as gloves, boots, and masks made of animal hide, to protect themselves from the bitter cold.

Although they originally descended from humans who were predominantly blue-eyed and fair-haired, the Reghed tribes have assimilated other folk, adding new blood to their dwindling ranks. There used to be more than four Reghed tribes, but the others have all disbanded over the past century, with many of their former members settling in Ten-Towns and abandoning their traditional ways.

The Reghed tribes rely on a nomadic lifestyle to survive, as they follow herds of reindeer along the route of the animals' annual migration. When they make camp, the tribesfolk live in large, round tents made of deerskin and supported by wooden shafts.

Reghed tribe camps are scattered throughout Icewind Dale. None of them appear on maps because they don't stay in one place for long.

Each Reghed tribe is made up of smaller clans, each with its own chieftain (the most powerful of whom often carries the title of king or queen). A clan might set up its camp for a tenday or two, then dismantle it and go back on the move, allowing the clan to stay close to a migrating herd of reindeer as it travels across the tundra.

```statblock
"name": "Reghed Chieftain (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"stats":
- !!int "18"
- !!int "15"
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "15"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
  "Strength": !!int "7"
  "Constitution": !!int "6"
"skillsaves":
  "Intimidation": !!int "5"
  "Athletics": !!int "10"
"senses": "passive Perception 11"
"languages": "any one language (usually Common)"
"cr": "5"
"traits":
- "desc": "The chieftain has advantage on saving throws against being [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Brave"
- "desc": "A melee weapon deals one extra die of its damage when the chieftain hits\
    \ with it (included in the attack)."
  "name": "Brute"
"actions":
- "desc": "The chieftain makes three melee attacks or two ranged attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. and range 20/60\
    \ ft., one target. Hit: 11 (2d6 + 4) piercing damage, or 13 (2d8 + 4) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Spear"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. Hit: 9\
    \ (2d4 + 4) bludgeoning damage. If the target is a Medium or smaller creature,\
    \ it must succeed on a DC 15 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Shield Bash"
"reactions":
- "desc": "The chieftain adds 3 to its AC against one melee attack that would hit\
    \ it. To do so, the chieftain must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Reghed%20Chieftain.webp"
```
^statblock

```encounter-table
name: Reghed Chieftain
creatures:
 - 1: Reghed Chieftain
```