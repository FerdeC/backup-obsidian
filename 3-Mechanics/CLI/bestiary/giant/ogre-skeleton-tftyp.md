---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/2
- monster/size/large
- monster/type/giant
aliases: ["Ogre Skeleton"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 54
---
# [Ogre Skeleton](2-Mechanics\CLI\bestiary\giant/ogre-skeleton-tftyp.md)
*Source: Tales from the Yawning Portal p. 54*  

```statblock
"name": "Ogre Skeleton (TftYP)"
"size": "Large"
"type": "giant"
"alignment": "Chaotic Evil"
"ac": !!int "11"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "59"
"hit_dice": "7d10 + 21"
"stats":
- !!int "19"
- !!int "8"
- !!int "16"
- !!int "5"
- !!int "7"
- !!int "7"
"speed": "40 ft."
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., darkvision 60 ft., passive Perception 8"
"languages": "Common, Giant, understands all languages it spoke in life but can't\
  \ speak"
"cr": "2"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) bludgeoning damage."
  "name": "Greatclub"
- "desc": "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 11 (2d6 + 4) piercing damage."
  "name": "Javelin"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Ogre%20Skeleton.webp"
```
^statblock

```encounter-table
name: Ogre Skeleton
creatures:
 - 1: Ogre Skeleton
```