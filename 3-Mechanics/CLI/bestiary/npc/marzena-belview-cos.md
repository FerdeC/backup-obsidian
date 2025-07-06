---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cos
- monster/cr/1-4
- monster/size/medium
- monster/type/humanoid/mongrelfolk
aliases: ["Marzena Belview"]
NoteIcon: monster
BestiaryType: humanoid (mongrelfolk)
SourceType: Bestiary
BookSource: Curse of Strahd p. 150
---
# [Marzena Belview](2-Mechanics\CLI\bestiary\npc/marzena-belview-cos.md)
*Source: Curse of Strahd p. 150*  

```statblock
"name": "Marzena Belview (CoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "mongrelfolk"
"alignment": "Any alignment"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "26"
"hit_dice": "4d8 + 8"
"stats":
- !!int "12"
- !!int "9"
- !!int "15"
- !!int "9"
- !!int "10"
- !!int "6"
"speed": "20 ft., fly 40 ft."
"skillsaves":
  "Deception": !!int "2"
  "Stealth": !!int "3"
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "1/4"
"traits":
- "desc": "The mongrelfolk has leathery wings and a flying speed of 40 feet."
  "name": "Flight"
- "desc": "Marzena can mimic any sounds it has heard, including voices. A creature\
    \ that hears the sounds can tell they are imitations with a successful DC 12 Wisdom\
    \ ([Insight](/2-Mechanics/CLI/rules/skills.md#Insight)) check."
  "name": "Mimicry"
"actions":
- "desc": "Marzena makes two attacks: one with its bite and one with its claw or dagger."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d4\
    \ + 1) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d4\
    \ + 1) slashing damage."
  "name": "Claw"
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 3 (1d4 + 1) piercing damage."
  "name": "Dagger"
"source":
- "CoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CoS/Marzena%20Belview.webp"
```
^statblock

```encounter-table
name: Marzena Belview
creatures:
 - 1: Marzena Belview
```