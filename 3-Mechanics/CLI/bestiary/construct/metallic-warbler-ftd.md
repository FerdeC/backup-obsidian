---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/ftd
- monster/cr/1-4
- monster/size/tiny
- monster/type/construct
aliases: ["Metallic Warbler"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Fizban's Treasury of Dragons p. 210
---
# [Metallic Warbler](2-Mechanics\CLI\bestiary\construct/metallic-warbler-ftd.md)
*Source: Fizban's Treasury of Dragons p. 210*  

Metallic warblers resemble songbirds and serve as clandestine agents of their creators, keeping watch over communities without directly intervening. Their telepathic bond lets them summon their dragon creators in case of dire need.

## Metallic Sentinels

A metallic sentinel is a guardian created by a metallic dragon, forged from the metal associated with its creator and powered by the energy of the dragon's breath. An artificial being sculpted in elegant filigree, it is dedicated to defusing tensions that could spiral into violence.

```statblock
"name": "Metallic Warbler (FTD)"
"size": "Tiny"
"type": "construct"
"alignment": "typically  Neutral Good"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "14"
"hit_dice": "4d4 + 4"
"stats":
- !!int "4"
- !!int "15"
- !!int "12"
- !!int "9"
- !!int "10"
- !!int "12"
"speed": "40 ft., fly 60 ft."
"saves":
  "Dexterity": !!int "4"
"damage_immunities": "fire"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands Common and Draconic but can't speak"
"cr": "1/4"
"traits":
- "desc": "The warbler is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
- "desc": "While the warbler is on the same plane of existence as its master, it can\
    \ magically convey what it senses to its master, and the two can communicate telepathically\
    \ with each other."
  "name": "Telepathic Bond"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) slashing damage."
  "name": "Claw"
- "desc": "The warbler releases a calming gas in a 5-foot-radius sphere centered on\
    \ itself. Each creature in that area must succeed on a DC 11 Charisma saving throw\
    \ or become [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed) by the warbler\
    \ for 1 minute. While [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ in this way, the creature is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ and has a speed of 0."
  "name": "Calming Mist (Recharge 5-6)"
"source":
- "FTD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/FTD/Metallic%20Warbler.webp"
```
^statblock

```encounter-table
name: Metallic Warbler
creatures:
 - 1: Metallic Warbler
```