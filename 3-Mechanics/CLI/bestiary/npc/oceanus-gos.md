---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Oceanus"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 246
---
# [Oceanus](2-Mechanics\CLI\bestiary\npc/oceanus-gos.md)
*Source: Ghosts of Saltmarsh p. 246*  

Before being captured, this sea elf had been tasked with investigating the Sea Ghost's movements in The Sinister Secret of Saltmarsh. Oceanus is a smart and resourceful elf who is more than willing to join adventurers who have brave hearts and good intentions.

```statblock
"name": "Oceanus (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Good"
"ac": !!int "12"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "30"
"hit_dice": "4d8 + 12"
"stats":
- !!int "15"
- !!int "12"
- !!int "16"
- !!int "11"
- !!int "12"
- !!int "10"
"speed": "30 ft., swim 30 ft."
"saves":
  "Constitution": !!int "5"
"skillsaves":
  "Athletics": !!int "4"
  "Perception": !!int "3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Aquan, Elvish"
"cr": "1/2"
"traits":
- "desc": "Oceanus can breathe air and water."
  "name": "Amphibious"
- "desc": "Using gestures and sounds, Oceanus can communicate simple ideas with any\
    \ beast that has an innate swimming speed."
  "name": "Friend of the Sea"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Trident"
- "desc": "Ranged Weapon Attack: +3 to hit, range 80/320 ft., one target. Hit:\
    \ 5 (1d8 + 1) piercing damage."
  "name": "Light Crossbow"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Oceanus.webp"
```
^statblock

```encounter-table
name: Oceanus
creatures:
 - 1: Oceanus
```