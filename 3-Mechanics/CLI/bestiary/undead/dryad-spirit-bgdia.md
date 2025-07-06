---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/4
- monster/size/medium
- monster/type/undead
aliases: ["Dryad Spirit"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 108
---
# [Dryad Spirit](2-Mechanics\CLI\bestiary\undead/dryad-spirit-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 108*  

```statblock
"name": "Dryad Spirit (BGDIA)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"hp": !!int "58"
"hit_dice": "13d8"
"stats":
- !!int "1"
- !!int "14"
- !!int "10"
- !!int "12"
- !!int "11"
- !!int "17"
"speed": "0 ft., fly 40 ft. (hover)"
"saves":
  "Charisma": !!int "5"
  "Wisdom": !!int "2"
"damage_resistances": "acid; fire; lightning; thunder; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"damage_immunities": "cold, necrotic, poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone), [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Elvish"
"cr": "4"
"traits":
- "desc": "The dryad can magically sense the presence of living creatures up to 5\
    \ miles away that aren't undead or constructs. She knows the general direction\
    \ they're in but not their exact locations."
  "name": "Detect Life"
- "desc": "The dryad can move through other creatures and objects as if they were\
    \ difficult terrain. She takes 5 (1d10) force damage if she ends her turn inside\
    \ an object."
  "name": "Incorporeal Movement"
"actions":
- "desc": "Melee Spell Attack: +4 to hit, reach 5 ft., one target. Hit: 12 (3d6\
    \ + 2) necrotic damage."
  "name": "Corrupting Touch"
- "desc": "Each non-undead creature within 60 feet of the dryad that can see her must\
    \ succeed on a DC 13 Wisdom saving throw or be [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ for 1 minute. A [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ target can repeat the saving throw at the end of each of its turns, with disadvantage\
    \ if the dryad is within line of sight, ending the effect on itself on a success.\
    \ If a target's saving throw is successful or the effect ends for it, the target\
    \ is immune to the dryad's Horrifying Visage for the next 24 hours."
  "name": "Horrifying Visage"
- "desc": "The dryad releases a mournful wail, provided that she isn't in sunlight.\
    \ This wail has no effect on constructs and undead. All other creatures within\
    \ 30 feet of her that can hear her must make a DC 13 Constitution saving throw.\
    \ On a failure, a creature drops to 0 hit points. On a success, a creature takes\
    \ 10 (3d6) psychic damage."
  "name": "Wail (1/Day)"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Dryad%20Spirit.webp"
```
^statblock

```encounter-table
name: Dryad Spirit
creatures:
 - 1: Dryad Spirit
```