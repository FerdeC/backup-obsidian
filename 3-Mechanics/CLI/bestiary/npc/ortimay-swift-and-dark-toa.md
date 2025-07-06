---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Ortimay Swift and Dark"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 21
---
# [Ortimay Swift and Dark](2-Mechanics\CLI\bestiary\npc/ortimay-swift-and-dark-toa.md)
*Source: Tomb of Annihilation p. 21*  

```statblock
"name": "Ortimay Swift and Dark (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Good"
"ac": !!int "15"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "15"
- !!int "16"
- !!int "14"
- !!int "14"
- !!int "11"
- !!int "14"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "2"
  "Strength": !!int "4"
"skillsaves":
  "Athletics": !!int "4"
  "Deception": !!int "4"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "any two languages, Gnomish"
"cr": "2"
"traits":
- "desc": "Ortimay"
  "name": "Gnome Cunning"
"actions":
- "desc": "Ortimay makes three melee attacks: two with its scimitar and one with its\
    \ dagger. Or Ortimay makes two ranged attacks with its daggers."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Scimitar"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage."
  "name": "Dagger"
"reactions":
- "desc": "Ortimay adds 2 to its AC against one melee attack that would hit it. To\
    \ do so, Ortimay must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Ortimay%20Swift%20and%20Dark.webp"
```
^statblock

```encounter-table
name: Ortimay Swift and Dark
creatures:
 - 1: Ortimay Swift and Dark
```