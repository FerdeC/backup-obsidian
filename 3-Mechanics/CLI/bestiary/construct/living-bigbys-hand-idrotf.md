---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/4
- monster/size/large
- monster/type/construct
aliases: ["Living Bigby's Hand"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 298
---
# [Living Bigby's Hand](2-Mechanics\CLI\bestiary\construct/living-bigbys-hand-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 298*  

A living Bigby's hand is a Large, hovering hand of shimmering, translucent force. It often serves as a guardian, attacking creatures that cross its path while remaining loyal to its caster.

Areas of wild magic and sites that have been ravaged by powerful eldritch forces can give rise to spell effects that become living beings. These so-called living spells haunt the places where they were created, subsisting on ambient magical energy.

```statblock
"name": "Living Bigby's Hand (IDRotF)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "52"
"hit_dice": "5d10 + 25"
"stats":
- !!int "26"
- !!int "10"
- !!int "20"
- !!int "1"
- !!int "10"
- !!int "1"
"speed": "0 ft., fly 60 ft. (hover)"
"saves":
  "Dexterity": !!int "2"
  "Wisdom": !!int "2"
"skillsaves":
  "Stealth": !!int "2"
  "Perception": !!int "2"
"damage_immunities": "poison"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned), [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": ""
"cr": "4"
"traits":
- "desc": "The living spell has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
- "desc": "The living spell doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "Melee Spell Attack: +10 to hit, reach 5 ft., one target. Hit: 26\
    \ (4d8 + 8) force damage. If the target is a Large or smaller creature, the\
    \ living spell can move it up to 5 feet and move with it, without provoking opportunity\
    \ attacks."
  "name": "Force Fist"
- "desc": "The living spell attempts to grab a Huge or smaller creature within 5 feet\
    \ of it. The target must succeed on a DC 15 Dexterity saving throw or be [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 15). Until the grapple ends, the target takes 15 (2d6 + 8) bludgeoning\
    \ damage at the start of each of its turns. The living spell can grapple only\
    \ one creature at a time and can't use Force Fist until the grapple ends."
  "name": "Grasping Hand"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Living%20Bigby%27s%20Hand.webp"
```
^statblock

```encounter-table
name: Living Bigby's Hand
creatures:
 - 1: Living Bigby's Hand
```