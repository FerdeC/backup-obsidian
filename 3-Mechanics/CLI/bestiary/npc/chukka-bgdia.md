---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/1-4
- monster/size/medium
- monster/type/humanoid/kenku
aliases: ["Chukka"]
NoteIcon: monster
BestiaryType: humanoid (kenku)
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 83
---
# [Chukka](2-Mechanics\CLI\bestiary\npc/chukka-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 83*  

```statblock
"name": "Chukka (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "kenku"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"hp": !!int "13"
"hit_dice": "3d8"
"stats":
- !!int "10"
- !!int "16"
- !!int "10"
- !!int "11"
- !!int "10"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "4"
  "Stealth": !!int "5"
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "understands Auran and Common but speaks only through the use of its\
  \ Mimicry trait"
"cr": "1/4"
"traits":
- "desc": "In the first round of a combat, Chukka has advantage on attack rolls against\
    \ any creature it [surprised](/2-Mechanics/CLI/rules/conditions.md#surprised)."
  "name": "Ambusher"
- "desc": "Chukka can mimic any sounds it has heard, including voices. A creature\
    \ that hears the sounds can tell they are imitations with a successful DC 14 Wisdom\
    \ ([Insight](/2-Mechanics/CLI/rules/skills.md#Insight)) check."
  "name": "Mimicry"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 5 (1d10)\
    \ piercing damage."
  "name": "Silvered Pike"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Chukka.webp"
```
^statblock

```encounter-table
name: Chukka
creatures:
 - 1: Chukka
```