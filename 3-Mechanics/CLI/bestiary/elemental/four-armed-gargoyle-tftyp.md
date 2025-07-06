---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/2
- monster/size/medium
- monster/type/elemental
aliases: ["Four-Armed Gargoyle"]
NoteIcon: monster
BestiaryType: elemental
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 129
---
# [Four-Armed Gargoyle](2-Mechanics\CLI\bestiary\elemental/four-armed-gargoyle-tftyp.md)
*Source: Tales from the Yawning Portal p. 129*  

```statblock
"name": "Four-Armed Gargoyle (TftYP)"
"size": "Medium"
"type": "elemental"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "63"
"hit_dice": "7d8 + 21"
"stats":
- !!int "15"
- !!int "11"
- !!int "16"
- !!int "6"
- !!int "11"
- !!int "7"
"speed": "30 ft., fly 60 ft."
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't adamantine"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Terran"
"cr": "2"
"traits":
- "desc": "While the gargoyle remains motionless, it is indistinguishable from an\
    \ inanimate statue."
  "name": "False Appearance"
"actions":
- "desc": "The gargoyle makes three attacks: one with its bite and two with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) slashing damage."
  "name": "Claws"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Four-Armed%20Gargoyle.webp"
```
^statblock

```encounter-table
name: Four-Armed Gargoyle
creatures:
 - 1: Four-Armed Gargoyle
```