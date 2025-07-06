---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/lizardfolk
aliases: ["Othokent"]
NoteIcon: monster
BestiaryType: humanoid (lizardfolk)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 81
---
# [Othokent](2-Mechanics\CLI\bestiary\npc/othokent-gos.md)
*Source: Ghosts of Saltmarsh p. 81*  

```statblock
"name": "Othokent (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "lizardfolk"
"alignment": "Lawful Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"stats":
- !!int "17"
- !!int "12"
- !!int "15"
- !!int "11"
- !!int "11"
- !!int "15"
"speed": "30 ft., swim 30 ft."
"saves":
  "Wisdom": !!int "2"
  "Constitution": !!int "4"
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "4"
  "Survival": !!int "4"
"condition_immunities": "[frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Abyssal, Draconic"
"cr": "4"
"traits":
- "desc": "Othokent can hold its breath for 15 minutes."
  "name": "Hold Breath"
- "desc": "Once per turn, when Othokent makes a melee attack with its trident and\
    \ hits, the target takes an extra 10 (3d6) damage, and Othokent gains temporary\
    \ hit points equal to the extra damage dealt."
  "name": "Skewer"
"actions":
- "desc": "Othokent makes two attacks: one with its bite and one with its claws or\
    \ trident or two melee attacks with its trident."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
    \ + 3) slashing damage."
  "name": "Claws"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 6 (1d6 + 3) piercing damage, or 7 (1d8 + 3) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Trident"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Othokent.webp"
```
^statblock

```encounter-table
name: Othokent
creatures:
 - 1: Othokent
```