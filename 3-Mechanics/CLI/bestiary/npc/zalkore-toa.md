---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/6
- monster/size/medium
- monster/type/monstrosity
aliases: ["Zalkoré"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 79
---
# [Zalkoré](2-Mechanics\CLI\bestiary\npc/zalkore-toa.md)
*Source: Tomb of Annihilation p. 79*  

```statblock
"name": "Zalkoré (ToA)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Lawful Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "127"
"hit_dice": "17d8 + 51"
"stats":
- !!int "10"
- !!int "15"
- !!int "16"
- !!int "12"
- !!int "13"
- !!int "15"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Stealth": !!int "5"
  "Insight": !!int "4"
  "Perception": !!int "4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common"
"cr": "6"
"traits":
- "desc": "When a creature that can see Zalkoré's eyes starts its turn within 30 feet\
    \ of Zalkoré, Zalkoré can force it to make a DC 14 Constitution saving throw if\
    \ Zalkoré isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ and can see the creature. If the saving throw fails by 5 or more, the creature\
    \ is instantly [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified). Otherwise,\
    \ a creature that fails the save begins to turn to stone and is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained).\
    \ The [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained) creature must\
    \ repeat the saving throw at the end of its next turn, becoming [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified)\
    \ on a failure or ending the effect on a success. The petrification lasts until\
    \ the creature is freed by the  [greater restoration](/2-Mechanics/CLI/spells/greater-restoration.md)\
    \ spell or other magic.\n\nUnless [surprised](/2-Mechanics/CLI/rules/conditions.md#surprised),\
    \ a creature can avert its eyes to avoid the saving throw at the start of its\
    \ turn. If the creature does so, it can't see Zalkoré until the start of its next\
    \ turn, when it can avert its eyes again. If the creature looks at Zalkoré in\
    \ the meantime, it must immediately make the save.\n\nIf Zalkoré sees itself reflected\
    \ on a polished surface within 30 feet of it and in an area of bright light, Zalkoré\
    \ is, due to its curse, affected by its own gaze."
  "name": "Petrifying Gaze"
"actions":
- "desc": "Zalkoré makes either three melee attacks—one with its snake hair and two\
    \ with its shortsword—or two ranged attacks with its longbow."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 4\
    \ (1d4 + 2) piercing damage plus 14 (4d6) poison damage."
  "name": "Snake Hair"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +5 to hit, range 150/600 ft., one target. Hit:\
    \ 6 (1d8 + 2) piercing damage plus 7 (2d6) poison damage."
  "name": "Longbow"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Zalkore.webp"
```
^statblock

```encounter-table
name: Zalkoré
creatures:
 - 1: Zalkoré
```