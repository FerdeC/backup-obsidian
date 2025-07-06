---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/jttrc
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Madam Kulp"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Journeys through the Radiant Citadel p. 27
---
# [Madam Kulp](2-Mechanics\CLI\bestiary\npc/madam-kulp-jttrc.md)
*Source: Journeys through the Radiant Citadel p. 27*  

```statblock
"name": "Madam Kulp (JttRC)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral"
"ac": !!int "15"
"ac_class": "[breastplate](/2-Mechanics/CLI/items/breastplate.md)"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "11"
- !!int "12"
- !!int "11"
- !!int "12"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Insight": !!int "4"
  "Persuasion": !!int "5"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "any two languages, Gnomish"
"cr": "1/8"
"traits":
- "desc": "Madam"
  "name": "Gnome Cunning"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d8\
    \ + 1) piercing damage."
  "name": "Rapier"
"reactions":
- "desc": "Madam Kulp adds 2 to its AC against one melee attack that would hit it.\
    \ To do so, Madam Kulp must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "JttRC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/JttRC/Madam%20Kulp.webp"
```
^statblock

```encounter-table
name: Madam Kulp
creatures:
 - 1: Madam Kulp
```