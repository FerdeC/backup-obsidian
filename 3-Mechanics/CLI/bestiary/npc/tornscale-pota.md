---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/lizardfolk
aliases: ["Tornscale"]
NoteIcon: monster
BestiaryType: humanoid (lizardfolk)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 90
---
# [Tornscale](2-Mechanics\CLI\bestiary\npc/tornscale-pota.md)
*Source: Princes of the Apocalypse p. 90*  

```statblock
"name": "Tornscale (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "lizardfolk"
"alignment": "Neutral"
"ac": !!int "15"
"ac_class": "natural armor, [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "36"
"hit_dice": "4d8 + 4"
"stats":
- !!int "15"
- !!int "10"
- !!int "13"
- !!int "7"
- !!int "12"
- !!int "7"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "3"
  "Survival": !!int "5"
"senses": "passive Perception 13"
"languages": "Draconic"
"cr": "1/2"
"traits":
- "desc": "Tornscale can hold its breath for 15 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "Tornscale makes two melee attacks, each one with a different weapon."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage."
  "name": "Heavy Club"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 5 (1d6 + 2) piercing damage."
  "name": "Javelin"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Spiked Shield"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Tornscale.webp"
```
^statblock

```encounter-table
name: Tornscale
creatures:
 - 1: Tornscale
```