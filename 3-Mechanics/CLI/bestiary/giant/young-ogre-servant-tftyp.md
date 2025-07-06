---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/1-2
- monster/size/medium
- monster/type/giant
aliases: ["Young Ogre Servant"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 171
---
# [Young Ogre Servant](2-Mechanics\CLI\bestiary\giant/young-ogre-servant-tftyp.md)
*Source: Tales from the Yawning Portal p. 171*  

```statblock
"name": "Young Ogre Servant (TftYP)"
"size": "Medium"
"type": "giant"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "15"
"hit_dice": "2d8 + 6"
"stats":
- !!int "16"
- !!int "12"
- !!int "16"
- !!int "7"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "2"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Orc"
"cr": "1/2"
"traits":
- "desc": "As a bonus action, the ogre can move up to its speed toward a hostile creature\
    \ that it can see."
  "name": "Aggressive"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 9 (1d12\
    \ + 3) slashing damage."
  "name": "Greataxe"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 6 (1d6 + 3) piercing damage."
  "name": "Javelin"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Young%20Ogre%20Servant.webp"
```
^statblock

```encounter-table
name: Young Ogre Servant
creatures:
 - 1: Young Ogre Servant
```