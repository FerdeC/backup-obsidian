---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cm
- monster/cr/2
- monster/size/medium
- monster/type/fey
aliases: ["Naiad"]
NoteIcon: monster
BestiaryType: fey
SourceType: Bestiary
BookSource: Candlekeep Mysteries p. 84
---
# [Naiad](2-Mechanics\CLI\bestiary\fey/naiad-cm.md)
*Source: Candlekeep Mysteries p. 84*  

```statblock
"name": "Naiad (CM)"
"size": "Medium"
"type": "fey"
"alignment": "Chaotic Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "31"
"hit_dice": "7d8"
"stats":
- !!int "10"
- !!int "16"
- !!int "11"
- !!int "15"
- !!int "10"
- !!int "18"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Sleight of Hand": !!int "5"
  "Persuasion": !!int "6"
"damage_resistances": "psychic"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "passive Perception 10"
"languages": "Common, Sylvan"
"cr": "2"
"traits":
- "desc": "The naiad's spellcasting ability is Charisma (spell save DC 14). It can\
    \ innately cast the following spells, requiring no material components:\n\nAt\
    \ will: [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md)\n\n1/day\
    \ each: [fly](/2-Mechanics/CLI/spells/fly.md), [hypnotic pattern](/2-Mechanics/CLI/spells/hypnotic-pattern.md)\n\
    \n3/day: [phantasmal force](/2-Mechanics/CLI/spells/phantasmal-force.md)"
  "name": "Innate Spellcasting"
- "desc": "The naiad can breathe air and water."
  "name": "Amphibious"
- "desc": "The naiad is [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ while fully immersed in water."
  "name": "Invisible in Water"
- "desc": "The naiad has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The naiad makes two psychic touch attacks."
  "name": "Multiattack"
- "desc": "Melee Spell Attack: +6 to hit, reach 5 ft., one target. Hit: 9 (1d10\
    \ + 4) psychic damage."
  "name": "Psychic Touch"
"source":
- "CM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CM/Naiad.webp"
```
^statblock

```encounter-table
name: Naiad
creatures:
 - 1: Naiad
```