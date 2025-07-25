---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/9
- monster/size/huge
- monster/type/undead
aliases: ["Undead Tree"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 109
---
# [Undead Tree](2-Mechanics\CLI\bestiary\undead/undead-tree-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 109*  

```statblock
"name": "Undead Tree (BGDIA)"
"size": "Huge"
"type": "undead"
"alignment": "Chaotic Good"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "138"
"hit_dice": "12d12 + 60"
"stats":
- !!int "23"
- !!int "8"
- !!int "21"
- !!int "12"
- !!int "16"
- !!int "12"
"speed": "30 ft."
"damage_vulnerabilities": "fire"
"damage_resistances": "necrotic"
"senses": "passive Perception 13"
"languages": "Common, Druidic, Elvish, Sylvan"
"cr": "9"
"traits":
- "desc": "While the tree remains motionless, it is indistinguishable from a normal\
    \ tree."
  "name": "False Appearance"
- "desc": "The tree deals double damage to objects and structures."
  "name": "Siege Monster"
"actions":
- "desc": "The tree makes two slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 16\
    \ (3d6 + 6) bludgeoning damage."
  "name": "Slam"
- "desc": "Ranged Weapon Attack: +10 to hit, range 60/180 ft., one target. Hit:\
    \ 28 (4d10 + 6) bludgeoning damage."
  "name": "Rock"
- "desc": "The tree magically animates one or two trees it can see within 60 feet\
    \ of it. These trees have the same statistics as a tree, except they have Intelligence\
    \ and Charisma scores of 1, they can't speak, and they have only the Slam action\
    \ option. An animated tree acts as an ally of the tree. The tree remains animate\
    \ for 1 day or until it dies; until the tree dies or is more than 120 feet from\
    \ the tree; or until the tree takes a bonus action to turn it back into an inanimate\
    \ tree. The tree then takes root if possible."
  "name": "Animate Trees (1/Day)"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Undead%20Tree.webp"
```
^statblock

```encounter-table
name: Undead Tree
creatures:
 - 1: Undead Tree
```