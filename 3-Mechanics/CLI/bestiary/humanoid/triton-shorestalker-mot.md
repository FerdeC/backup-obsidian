---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mot
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/triton
aliases: ["Triton Shorestalker"]
NoteIcon: monster
BestiaryType: humanoid (triton)
SourceType: Bestiary
BookSource: Mythic Odysseys of Theros p. 244
---
# [Triton Shorestalker](2-Mechanics\CLI\bestiary\humanoid/triton-shorestalker-mot.md)
*Source: Mythic Odysseys of Theros p. 244*  

Some insults don't wash away with the tides. When surface dwellers threaten the safety of triton communities, impede upon Thassa's holiest depths, or steal the treasures of the deep, triton shorestalkers seek vengeance. Using speed and poison harvested from deadly sea beasts, these triton assassins slip into shallow waters and strike when least expected. Often, surface dwellers don't even realize they've been attacked by shorestalkers, chalking disappearances and deaths up to the innumerable dangers of the sea.

Clever, far-ranging people of the sea, tritons live rich lives unknown to most land-dwelling individuals. While the waves separate most tritons from land-dwellers, occasionally the inhabitants of the surface and the deep come into conflict. In such cases, tritons prove skilled at sabotaging ocean-going vessels, employing water-based magic, and otherwise whipping up the fury of the sea. Few dare insult tritons in their home environment, but those who do and survive often learn that the tritons' wrath doesn't end at the shore.

```statblock
"name": "Triton Shorestalker (MOT)"
"size": "Medium"
"type": "humanoid"
"subtype": "triton"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"stats":
- !!int "11"
- !!int "16"
- !!int "14"
- !!int "10"
- !!int "15"
- !!int "11"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Nature": !!int "4"
  "Stealth": !!int "5"
  "Perception": !!int "4"
"damage_resistances": "cold"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Primordial"
"cr": "2"
"traits":
- "desc": "The triton's spellcasting ability is Wisdom (spell save DC 12). It can\
    \ innately cast the following spells, requiring no material components:\n\n1/day\
    \ each: [fog cloud](/2-Mechanics/CLI/spells/fog-cloud.md), [gust of wind](/2-Mechanics/CLI/spells/gust-of-wind.md)"
  "name": "Innate Spellcasting"
- "desc": "The triton can breathe air and water."
  "name": "Amphibious"
- "desc": "The triton can take the Disengage or Hide actions as a bonus action on\
    \ each of its turns."
  "name": "Nimble Escape"
"actions":
- "desc": "The triton makes two urchin-spine shortsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage plus 10 (3d6) poison damage. If the damage reduces a\
    \ creature to 0 hit points, that creature is stable but [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 hour, even after regaining hit points, and is [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed)\
    \ while [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) in this way."
  "name": "Urchin-Spine Shortsword"
- "desc": "Ranged Weapon Attack: +5 to hit, range 30/60 ft., one target. Hit:\
    \ 5 (1d4 + 3) piercing damage plus 10 (3d6) poison damage."
  "name": "Poisoned Spine"
"source":
- "MOT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MOT/Triton%20Shorestalker.webp"
```
^statblock

```encounter-table
name: Triton Shorestalker
creatures:
 - 1: Triton Shorestalker
```