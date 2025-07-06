---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/scc
- monster/cr/4
- monster/size/large
- monster/type/construct
aliases: ["Cogwork Archivist"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Strixhaven: A Curriculum of Chaos p. 188
---
# [Cogwork Archivist](2-Mechanics\CLI\bestiary\construct/cogwork-archivist-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 188*  

Programmed with knowledge of Strixhaven's extensive lore catalog, cogwork archivists serve as keepers of the university's various libraries. The archivists' towering metal frames are equipped with long, articulated limbs and retractable conservator tools, which they use to organize and preserve documents from throughout Strixhaven's winding history. Many cogwork archivists can be found among the towering shelves of the Biblioplex, simultaneously retrieving scrolls for curious students while keeping a stern eye on any rowdy groups that might disrupt the quiet atmosphere.

```statblock
"name": "Cogwork Archivist (SCC)"
"size": "Large"
"type": "construct"
"alignment": "typically  Lawful Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "90"
"hit_dice": "12d10 + 24"
"stats":
- !!int "18"
- !!int "10"
- !!int "15"
- !!int "17"
- !!int "11"
- !!int "6"
"speed": "40 ft."
"skillsaves":
  "Nature": !!int "5"
  "Religion": !!int "5"
  "Perception": !!int "2"
  "History": !!int "5"
  "Arcana": !!int "5"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "all"
"cr": "4"
"traits":
- "desc": "The archivist casts one of the following spells, requiring no material\
    \ components and using Intelligence as the spellcasting ability:\n\nAt will:\
    \ [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\
    \n2/day: [silence](/2-Mechanics/CLI/spells/silence.md)"
  "name": "Spellcasting"
- "desc": "The archivist has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The archivist makes two Grasping Limb attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 15 ft., one target. Hit: 13\
    \ (2d8 + 4) bludgeoning damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 14). The archivist can have no more than two targets [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ at a time."
  "name": "Grasping Limb"
"source":
- "SCC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SCC/Cogwork%20Archivist.webp"
```
^statblock

```encounter-table
name: Cogwork Archivist
creatures:
 - 1: Cogwork Archivist
```