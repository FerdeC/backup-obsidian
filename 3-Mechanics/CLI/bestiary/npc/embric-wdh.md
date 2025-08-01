---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/fire-genasi
aliases: ["Embric"]
NoteIcon: monster
BestiaryType: humanoid (Fire genasi)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 32
---
# [Embric](2-Mechanics\CLI\bestiary\npc/embric-wdh.md)
*Source: Waterdeep: Dragon Heist p. 32*  

Embric tends the forge in the Steam and Steel shop in Trollskull Alley. He is an expert weaponsmith and claims descent from the efreet of Calimshan and is prone to extreme mood swings. He is married to Avi.

```statblock
"name": "Embric (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "Fire genasi"
"alignment": "Neutral Good"
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
"languages": "Common, Primordial"
"cr": "2"
"traits":
- "desc": "Embric's spellcasting ability is Constitution (+4 to hit with spell attacks).\
    \ He can innately cast the following spells, requiring no material components:\n\
    \nAt will: [produce flame](/2-Mechanics/CLI/spells/produce-flame.md)"
  "name": "Innate Spellcasting"
"actions":
- "desc": "Embric makes three melee attacks: two with its scimitar and one with its\
    \ dagger. Or Embric makes two ranged attacks with its daggers."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Scimitar"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage."
  "name": "Dagger"
"reactions":
- "desc": "Embric adds 2 to its AC against one melee attack that would hit it. To\
    \ do so, Embric must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "WDH"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDH/Embric.webp"
```
^statblock

```encounter-table
name: Embric
creatures:
 - 1: Embric
```