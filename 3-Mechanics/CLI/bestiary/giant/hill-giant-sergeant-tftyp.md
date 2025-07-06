---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/5
- monster/size/huge
- monster/type/giant
aliases: ["Hill Giant Sergeant"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 170
---
# [Hill Giant Sergeant](2-Mechanics\CLI\bestiary\giant/hill-giant-sergeant-tftyp.md)
*Source: Tales from the Yawning Portal p. 170*  

```statblock
"name": "Hill Giant Sergeant (TftYP)"
"size": "Huge"
"type": "giant"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "[chain mail](/2-Mechanics/CLI/items/chain-mail.md)"
"hp": !!int "115"
"hit_dice": "10d12 + 40"
"stats":
- !!int "21"
- !!int "8"
- !!int "19"
- !!int "5"
- !!int "9"
- !!int "6"
"speed": "40 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "Giant"
"cr": "5"
"actions":
- "desc": "The giant makes two greatclub attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 18\
    \ (3d8 + 5) bludgeoning damage."
  "name": "Greatclub"
- "desc": "Ranged Weapon Attack: +8 to hit, range 60/240 ft., one target. Hit:\
    \ 21 (3d10 + 5) bludgeoning damage."
  "name": "Rock"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Hill%20Giant%20Sergeant.webp"
```
^statblock

```encounter-table
name: Hill Giant Sergeant
creatures:
 - 1: Hill Giant Sergeant
```