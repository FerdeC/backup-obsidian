---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wbtw
- monster/cr/2
- monster/size/tiny
- monster/type/undead
aliases: ["Will-o'-Wells"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: The Wild Beyond the Witchlight p. 61
---
# [Will-o'-Wells](2-Mechanics\CLI\bestiary\undead/will-o-wells-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 61*  

```statblock
"name": "Will-o'-Wells (WBtW)"
"size": "Tiny"
"type": "undead"
"alignment": "Chaotic Good"
"ac": !!int "19"
"hp": !!int "22"
"hit_dice": "9d4"
"stats":
- !!int "1"
- !!int "28"
- !!int "10"
- !!int "13"
- !!int "14"
- !!int "11"
"speed": "0 ft., fly 50 ft. (hover)"
"damage_resistances": "acid; cold; fire; necrotic; thunder; bludgeoning, piercing,\
  \ slashing from nonmagical attacks"
"damage_immunities": "lightning, poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned), [prone](/2-Mechanics/CLI/rules/conditions.md#prone),\
  \ [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained), [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "the languages it knew in life"
"cr": "2"
"traits":
- "desc": "As a bonus action, the will-o'-wells can target one creature it can see\
    \ within 5 feet of it that has 0 hit points and is still alive. The target must\
    \ succeed on a DC 10 Constitution saving throw against this magic or die. If the\
    \ target dies, the will-o'-wells regains 10 (3d6) hit points."
  "name": "Consume Life"
- "desc": "The will-o'-wells can't wear or carry anything."
  "name": "Ephemeral"
- "desc": "The will-o'-wells can move through other creatures and objects as if they\
    \ were difficult terrain. It takes 5 (1d10) force damage if it ends its turn\
    \ inside an object."
  "name": "Incorporeal Movement"
- "desc": "The will-o'-wells sheds bright light in a 5 to 20-foot radius and dim light\
    \ for an additional number of ft. equal to the chosen radius. The will-o'-wells\
    \ can alter the radius as a bonus action."
  "name": "Variable Illumination"
"actions":
- "desc": "Melee Spell Attack: +4 to hit, reach 5 ft., one creature. Hit: 9\
    \ (2d8) lightning damage."
  "name": "Shock"
- "desc": "The will-o'-wells and its light magically become [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ until it attacks or uses its Consume Life, or until its [concentration](/2-Mechanics/CLI/rules/conditions.md#concentration)\
    \ ends (as if concentrating on a spell)."
  "name": "Invisibility"
- "desc": "The will-o'-wells grants a boon to one creature it can see within 5 feet\
    \ of it that isn't an Undead. The boon's recipient gains a d4 and can, at any\
    \ time within the next 24 hours, roll this die and add the number rolled to one\
    \ ability check, attack roll, or saving throw made by it. No creature can have\
    \ more than one of these magic boons at a time."
  "name": "Magic Boon (Recharges after a Long Rest)"
"source":
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WBtW/Will-o%27-Wells.webp"
```
^statblock

```encounter-table
name: Will-o'-Wells
creatures:
 - 1: Will-o'-Wells
```