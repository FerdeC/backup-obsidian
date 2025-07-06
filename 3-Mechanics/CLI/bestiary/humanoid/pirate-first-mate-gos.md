---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Pirate First Mate"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 248
---
# [Pirate First Mate](2-Mechanics\CLI\bestiary\humanoid/pirate-first-mate-gos.md)
*Source: Ghosts of Saltmarsh p. 248*  

These no-nonsense sailors are the trusted allies of a pirate ship's captain. Ex-soldiers and trained mercenaries often find employment as mates aboard pirate ships. In The Sinister Secret of Saltmarsh, Bloody Bjorn serves as the first mate aboard Sea Ghost.

```statblock
"name": "Pirate First Mate (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[chain mail](/2-Mechanics/CLI/items/chain-mail.md)"
"hp": !!int "26"
"hit_dice": "4d8 + 8"
"stats":
- !!int "14"
- !!int "11"
- !!int "14"
- !!int "11"
- !!int "10"
- !!int "13"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "3"
  "Athletics": !!int "4"
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "1"
"traits":
- "desc": "The first mate has advantage on ability checks and saving throws to resist\
    \ being knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Sea Legs"
"actions":
- "desc": "The first mate makes two attacks with its longsword."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with two hands.\
    \ If the target is a creature, the first mate can choose to deal no damage with\
    \ the attack to disarm the target. The target must succeed on a DC 14 Strength\
    \ saving throw or drop one item it is holding on the ground."
  "name": "Longsword"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Pirate%20First%20Mate.webp"
```
^statblock

```encounter-table
name: Pirate First Mate
creatures:
 - 1: Pirate First Mate
```