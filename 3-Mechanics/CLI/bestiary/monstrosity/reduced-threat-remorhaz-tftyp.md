---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/11
- monster/size/large
- monster/type/monstrosity
aliases: ["Reduced-Threat Remorhaz"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 113
---
# [Reduced-Threat Remorhaz](2-Mechanics\CLI\bestiary\monstrosity/reduced-threat-remorhaz-tftyp.md)
*Source: Tales from the Yawning Portal p. 113*  

```statblock
"name": "Reduced-Threat Remorhaz (TftYP)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "97"
"hit_dice": "17d12 + 85"
"stats":
- !!int "24"
- !!int "13"
- !!int "21"
- !!int "4"
- !!int "10"
- !!int "5"
"speed": "30 ft., burrow 20 ft."
"damage_immunities": "cold, fire"
"senses": "darkvision 60 ft., tremorsense 60 ft., passive Perception 10"
"languages": ""
"cr": "11"
"traits":
- "desc": "A reduced-threat monster takes a −2 penalty on attack rolls (included in\
    \ the stat block), ability checks (included in the stat block for skill proficiencies),\
    \ saving throws (included in the stat block for saving throw proficiencies), and\
    \ saving throw DCs (included in the stat block)."
  "name": "Reduced Threat"
- "desc": "A creature that touches the remorhaz or hits it with a melee attack while\
    \ within 5 feet of it takes 10 (3d6) fire damage."
  "name": "Heated Body"
"actions":
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 40\
    \ (6d10 + 7) piercing damage plus 10 (3d6) fire damage. If the target is a\
    \ creature, it is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled) (escape\
    \ DC 15). Until this grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and the remorhaz can't bite another target."
  "name": "Bite"
- "desc": "The remorhaz makes one bite attack against a Medium or smaller creature\
    \ it is grappling. If the attack hits, that creature takes the bite's damage and\
    \ is swallowed, and the grapple ends. While swallowed, the creature is [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded)\
    \ and [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained), it has total\
    \ cover against attacks and other effects outside the remorhaz, and it takes 21\
    \ (6d6) acid damage at the start of each of the remorhaz's turns.\n\nIf the\
    \ remorhaz takes 30 damage or more on a single turn from a creature inside it,\
    \ the remorhaz must succeed on a DC 13 Constitution saving throw at the end of\
    \ that turn or regurgitate all swallowed creatures, which fall [prone](/2-Mechanics/CLI/rules/conditions.md#prone)\
    \ in a space within 10 feet of the remorhaz. If the remorhaz dies, a swallowed\
    \ creature is no longer [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ by it and can escape from the corpse using 15 feet of movement, exiting [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Swallow"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Reduced-Threat%20Remorhaz.webp"
```
^statblock

```encounter-table
name: Reduced-Threat Remorhaz
creatures:
 - 1: Reduced-Threat Remorhaz
```