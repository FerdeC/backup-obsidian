---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/locathah
aliases: ["Locathah"]
NoteIcon: monster
BestiaryType: humanoid (locathah)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 243
---
# [Locathah](2-Mechanics\CLI\bestiary\humanoid/locathah-gos.md)
*Source: Ghosts of Saltmarsh p. 243*  

These resilient and proud fish-folk (found in Danger at Dunwater) have endured war, slavery, and mistreatment at the hands of other aquatic creatures. They dwell in submerged tribal communities along seacoasts, and hunt both above and below the water.

```statblock
"name": "Locathah (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "locathah"
"alignment": "Neutral"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"stats":
- !!int "13"
- !!int "12"
- !!int "12"
- !!int "11"
- !!int "10"
- !!int "11"
"speed": "30 ft., swim 30 ft."
"saves":
  "Dexterity": !!int "3"
"skillsaves":
  "Athletics": !!int "3"
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "Aquan, Common"
"cr": "1/2"
"traits":
- "desc": "The locathah has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
    \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned), [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned),\
    \ or put to sleep."
  "name": "Leviathan Will"
- "desc": "The locathah can breathe air and water, but it needs to be submerged at\
    \ least once every 4 hours to avoid suffocating."
  "name": "Limited Amphibiousness"
"actions":
- "desc": "The locathah makes two melee attacks with its spear."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d6 + 1) piercing damage, or 5 (1d8 + 1) piercing\
    \ damage if used with two hands."
  "name": "Spear"
"source":
- "GoS"
- "IMR"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Locathah.webp"
```
^statblock

```encounter-table
name: Locathah
creatures:
 - 1: Locathah
```