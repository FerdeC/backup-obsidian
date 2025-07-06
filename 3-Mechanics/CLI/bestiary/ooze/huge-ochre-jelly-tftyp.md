---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/2
- monster/size/huge
- monster/type/ooze
aliases: ["Huge Ochre Jelly"]
NoteIcon: monster
BestiaryType: ooze
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 225
---
# [Huge Ochre Jelly](2-Mechanics\CLI\bestiary\ooze/huge-ochre-jelly-tftyp.md)
*Source: Tales from the Yawning Portal p. 225*  

```statblock
"name": "Huge Ochre Jelly (TftYP)"
"size": "Huge"
"type": "ooze"
"alignment": "Unaligned"
"ac": !!int "8"
"hp": !!int "51"
"hit_dice": "6d12 + 12"
"stats":
- !!int "15"
- !!int "6"
- !!int "14"
- !!int "2"
- !!int "6"
- !!int "1"
"speed": "10 ft., climb 10 ft."
"damage_resistances": "acid"
"damage_immunities": "lightning, slashing"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 8"
"languages": ""
"cr": "2"
"traits":
- "desc": "The jelly can move through a space as narrow as 1 inch wide without squeezing."
  "name": "Amorphous"
- "desc": "The jelly can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 9 (2d6\
    \ + 2) bludgeoning damage plus 3 (1d6) acid damage."
  "name": "Pseudopod"
"reactions":
- "desc": "When a jelly that is Medium or larger is subjected to lightning or slashing\
    \ damage, it splits into two new jellies if it has at least 10 hit points. Each\
    \ new jelly has hit points equal to half the original jelly's, rounded down. New\
    \ jellies are one size smaller than the original jelly."
  "name": "Split"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Huge%20Ochre%20Jelly.webp"
```
^statblock

```encounter-table
name: Huge Ochre Jelly
creatures:
 - 1: Huge Ochre Jelly
```