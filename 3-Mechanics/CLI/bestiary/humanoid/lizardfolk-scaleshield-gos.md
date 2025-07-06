---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/lizardfolk
aliases: ["Lizardfolk Scaleshield"]
NoteIcon: monster
BestiaryType: humanoid (lizardfolk)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 242
---
# [Lizardfolk Scaleshield](2-Mechanics\CLI\bestiary\humanoid/lizardfolk-scaleshield-gos.md)
*Source: Ghosts of Saltmarsh p. 242*  

Serving as the elite warriors and officers of a lizardfolk clan, these robust creatures wear thick armor made from crocodile scales and metal. Trained in martial weapons and advanced combat tactics, they are found protecting lizardfolk lairs such as the one in Danger at Dunwater.

```statblock
"name": "Lizardfolk Scaleshield (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "lizardfolk"
"alignment": "Neutral"
"ac": !!int "16"
"ac_class": "[scale mail](/2-Mechanics/CLI/items/scale-mail.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"stats":
- !!int "15"
- !!int "10"
- !!int "14"
- !!int "7"
- !!int "12"
- !!int "7"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Athletics": !!int "4"
  "Perception": !!int "3"
  "Survival": !!int "5"
"senses": "passive Perception 13"
"languages": "Draconic"
"cr": "1"
"traits":
- "desc": "The scaleshield can hold its breath for 15 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "The scaleshield makes two melee attacks, each one with a different weapon."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) piercing damage."
  "name": "Morningstar"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Spiked Shield"
"reactions":
- "desc": "If an ally within 5 feet of the scaleshield is hit by an attack, the scaleshield\
    \ can reduce that attack's damage by half."
  "name": "Shield Block"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Lizardfolk%20Scaleshield.webp"
```
^statblock

```encounter-table
name: Lizardfolk Scaleshield
creatures:
 - 1: Lizardfolk Scaleshield
```