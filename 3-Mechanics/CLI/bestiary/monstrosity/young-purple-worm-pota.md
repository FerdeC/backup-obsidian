---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/13
- monster/size/gargantuan
- monster/type/monstrosity
aliases: ["Young Purple Worm"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 113
---
# [Young Purple Worm](2-Mechanics\CLI\bestiary\monstrosity/young-purple-worm-pota.md)
*Source: Princes of the Apocalypse p. 113*  

```statblock
"name": "Young Purple Worm (PotA)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "184"
"hit_dice": "15d20 + 90"
"stats":
- !!int "28"
- !!int "7"
- !!int "22"
- !!int "1"
- !!int "8"
- !!int "4"
"speed": "50 ft., burrow 30 ft."
"saves":
  "Wisdom": !!int "4"
  "Constitution": !!int "11"
"senses": "blindsight 30 ft., tremorsense 60 ft., passive Perception 9"
"languages": ""
"cr": "13"
"traits":
- "desc": "The worm can burrow through solid rock at half its burrow speed and leaves\
    \ a 10-foot-diameter tunnel in its wake."
  "name": "Tunneler"
"actions":
- "desc": "The worm makes two attacks: one with its bite and one with its stinger."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 22\
    \ (3d8 + 9) piercing damage. If the target is a Large or smaller creature, it\
    \ must succeed on a DC 19 Dexterity saving throw or be swallowed by the worm.\
    \ A swallowed creature is [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded)\
    \ and [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained), it has total\
    \ cover against attacks and other effects outside the worm, and it takes 21 (6d6)\
    \ acid damage at the start of each of the worm's turns.\n\nIf the worm takes 30\
    \ damage or more on a single turn from a creature inside it, the worm must succeed\
    \ on a DC 21 Constitution saving throw at the end of that turn or regurgitate\
    \ all swallowed creatures, which fall [prone](/2-Mechanics/CLI/rules/conditions.md#prone)\
    \ in a space within 10 feet of the worm. If the worm dies, a swallowed creature\
    \ is no longer [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained) by\
    \ it and can escape from the corpse by using 20 feet of movement, exiting [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one creature. Hit:\
    \ 19 (3d6 + 9) piercing damage, and the target must make a DC 19 Constitution\
    \ saving throw, taking 42 (12d6) poison damage on a failed save, or half as\
    \ much damage on a successful one."
  "name": "Tail Stinger"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Young%20Purple%20Worm.webp"
```
^statblock

```encounter-table
name: Young Purple Worm
creatures:
 - 1: Young Purple Worm
```