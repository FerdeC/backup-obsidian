---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mot
- monster/cr/1-8
- monster/size/medium
- monster/type/monstrosity
aliases: ["Blood-Toll Harpy"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Mythic Odysseys of Theros p. 227
---
# [Blood-Toll Harpy](2-Mechanics\CLI\bestiary\monstrosity/blood-toll-harpy-mot.md)
*Source: Mythic Odysseys of Theros p. 227*  

Murderous gangs of harpies collect in grim places across Theros, preying on any who pass by. Many merchants face regular losses at the harpies' claws, common casualties often referred to as a "blood toll."

Cruel, corpse-eating creatures, harpies endlessly seek their next meal, careless of whether it comes from the living or the dead. With equal zeal, these vicious scavengers set upon travelers or claw open fresh graves, stripping bodies of riches and flesh. Then they carry back any treasures or appealing bones they find to reeking nests situated in cramped caves or rotten trees.

```statblock
"name": "Blood-Toll Harpy (MOT)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "11"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "12"
- !!int "13"
- !!int "10"
- !!int "6"
- !!int "11"
- !!int "13"
"speed": "20 ft., fly 40 ft."
"skillsaves":
  "Intimidation": !!int "3"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "1/8"
"traits":
- "desc": "The harpy has advantage on melee attack rolls against any creature that\
    \ doesn't have all its hit points."
  "name": "Blood Frenzy"
- "desc": "The harpy has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Dark Devotion"
"actions":
- "desc": "The harpy makes two melee attacks: one with its bite and one with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d4\
    \ + 1) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d4\
    \ + 1) slashing damage."
  "name": "Claws"
"source":
- "MOT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MOT/Blood-Toll%20Harpy.webp"
```
^statblock

```encounter-table
name: Blood-Toll Harpy
creatures:
 - 1: Blood-Toll Harpy
```