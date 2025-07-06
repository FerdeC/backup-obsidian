---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/9
- monster/size/huge
- monster/type/plant
aliases: ["Duskwalker"]
NoteIcon: monster
BestiaryType: plant
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 150
---
# [Duskwalker](2-Mechanics\CLI\bestiary\npc/duskwalker-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 150*  

```statblock
"name": "Duskwalker (DSotDQ)"
"size": "Huge"
"type": "plant"
"alignment": "Neutral"
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
"damage_resistances": "bludgeoning, piercing"
"senses": "passive Perception 13"
"languages": "Common, Druidic, Elvish, Sylvan"
"cr": "9"
"traits":
- "desc": "While Duskwalker remains motionless, it is indistinguishable from a normal\
    \ tree."
  "name": "False Appearance"
- "desc": "Duskwalker deals double damage to objects and structures."
  "name": "Siege Monster"
"actions":
- "desc": "Duskwalker makes two slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 16\
    \ (3d6 + 6) bludgeoning damage."
  "name": "Slam"
- "desc": "Ranged Weapon Attack: +10 to hit, range 60/180 ft., one target. Hit:\
    \ 28 (4d10 + 6) bludgeoning damage."
  "name": "Rock"
- "desc": "Duskwalker magically animates one or two trees it can see within 60 feet\
    \ of it. These trees have the same statistics as a [treant](/2-Mechanics/CLI/bestiary/plant/treant.md),\
    \ except they have Intelligence and Charisma scores of 1, they can't speak, and\
    \ they have only the Slam action option. An animated tree acts as an ally of Duskwalker.\
    \ The tree remains animate for 1 day or until it dies; until Duskwalker dies or\
    \ is more than 120 feet from the tree; or until Duskwalker takes a bonus action\
    \ to turn it back into an inanimate tree. The tree then takes root if possible."
  "name": "Animate Trees (1/Day)"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Duskwalker.webp"
```
^statblock

```encounter-table
name: Duskwalker
creatures:
 - 1: Duskwalker
```