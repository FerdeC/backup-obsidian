---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/2
- monster/size/large
- monster/type/ooze
aliases: ["Glabbagool"]
NoteIcon: monster
BestiaryType: ooze
SourceType: Bestiary
BookSource: Out of the Abyss p. 35
---
# [Glabbagool](2-Mechanics\CLI\bestiary\npc/glabbagool-oota.md)
*Source: Out of the Abyss p. 35*  

Juiblex's arrival in the Underdark has granted Glabbagool sentience and awareness. The ooze is genuinely curious about other creatures and wants to learn more about the world. It defends itself if attacked, but doesn't otherwise try to harm the characters, instead asking who they are, where they come from, and why they have come to the temple.

```statblock
"name": "Glabbagool (OotA)"
"size": "Large"
"type": "ooze"
"alignment": "Unaligned"
"ac": !!int "6"
"hp": !!int "84"
"hit_dice": "8d10 + 40"
"stats":
- !!int "14"
- !!int "3"
- !!int "20"
- !!int "10"
- !!int "6"
- !!int "1"
"speed": "15 ft."
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 8"
"languages": "telepathy 60 ft."
"cr": "2"
"traits":
- "desc": "Glabbagool takes up its entire space. Other creatures can enter the space,\
    \ but a creature that does so is subjected to Glabbagool's Engulf and has disadvantage\
    \ on the saving throw.\n\nCreatures inside Glabbagool can be seen but have total\
    \ cover.\n\nA creature within 5 feet of Glabbagool can take an action to pull\
    \ a creature or object out of Glabbagool. Doing so requires a successful DC 12\
    \ Strength check, and the creature making the attempt takes 10 (3d6) acid damage.\n\
    \nGlabbagool can hold only one Large creature or up to four Medium or smaller\
    \ creatures inside it at a time."
  "name": "Ooze Cube"
- "desc": "Even when Glabbagool is in plain sight, it takes a successful DC 15 Wisdom\
    \ ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) check to spot a\
    \ cube that has neither moved nor attacked. A creature that tries to enter Glabbagool's\
    \ space while unaware of Glabbagool is [surprised](/2-Mechanics/CLI/rules/conditions.md#surprised)\
    \ by Glabbagool."
  "name": "Transparent"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 10\
    \ (3d6) acid damage."
  "name": "Pseudopod"
- "desc": "Glabbagool moves up to its speed. While doing so, it can enter Large or\
    \ smaller creatures' spaces. Whenever Glabbagool enters a creature's space, the\
    \ creature must make a DC 12 Dexterity saving throw.\n\nOn a successful save,\
    \ the creature can choose to be pushed 5 feet back or to the side of Glabbagool.\
    \ A creature that chooses not to be pushed suffers the consequences of a failed\
    \ saving throw.\n\nOn a failed save, Glabbagool enters the creature's space, and\
    \ the creature takes 10 (3d6) acid damage and is engulfed. The engulfed creature\
    \ can't breathe, is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and takes 21 (6d6) acid damage at the start of each of Glabbagool's turns.\
    \ When Glabbagool moves, the engulfed creature moves with it.\n\nAn engulfed creature\
    \ can try to escape by taking an action to make a DC 12 Strength check. On a success,\
    \ the creature escapes and enters a space of its choice within 5 feet of Glabbagool."
  "name": "Engulf"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Glabbagool.webp"
```
^statblock

```encounter-table
name: Glabbagool
creatures:
 - 1: Glabbagool
```