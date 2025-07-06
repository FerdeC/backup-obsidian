---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mot
- monster/cr/2
- monster/size/medium
- monster/type/monstrosity
aliases: ["Two-Headed Cerberus"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Mythic Odysseys of Theros p. 215
---
# [Two-Headed Cerberus](2-Mechanics\CLI\bestiary\monstrosity/two-headed-cerberus-mot.md)
*Source: Mythic Odysseys of Theros p. 215*  

Thought to be a lesser breed of cerberi that have interbred with mortal wolves, two-headed cerberi typically roam the mortal side of the Tartyx River. There they generally ignore—or only modestly menace—the souls of the dead. Such isn't the case for mortals, though, and they eagerly set upon those who tread too close to the Underworld's borders.

Feared by the living and the dead, cerberi patrol both banks of the Tartyx River. These multiheaded hounds of the Underworld breathe gouts of molten rock that sear and imprison those who trespass upon the borders of life and death. Most cerberi have a boundless hunger for fresh meat, especially the flesh of humanoids. Villains have been known to exploit that hunger by luring cerberi away from the river and setting them loose on mortal settlements.

```statblock
"name": "Two-Headed Cerberus (MOT)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Lawful Evil"
"ac": !!int "12"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"stats":
- !!int "15"
- !!int "14"
- !!int "14"
- !!int "3"
- !!int "13"
- !!int "6"
"speed": "40 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "5"
"damage_immunities": "fire, necrotic"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": ""
"cr": "2"
"traits":
- "desc": "As a bonus action, the cerberus can move up to its speed toward a hostile\
    \ creature that it can see."
  "name": "Aggressive"
- "desc": "The cerberus can't be [surprised](/2-Mechanics/CLI/rules/conditions.md#surprised),\
    \ and it has advantage on saving throws against being knocked [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)."
  "name": "Multiheaded"
- "desc": "The cerberus has advantage on an attack roll against a creature if at least\
    \ one of the cerberus's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "The cerberus makes two bite attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage plus 2 (1d4) fire damage."
  "name": "Bite"
- "desc": "The cerberus exhales a 15-foot cone of molten rock. Each creature in the\
    \ cone must make a DC 12 Dexterity saving throw, taking 10 (3d6) fire damage\
    \ on a failed save, or half as much damage on a successful one. On a failed save,\
    \ a creature is also [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ by the hardening rock. A creature can make a DC 12 Strength ([Athletics](/2-Mechanics/CLI/rules/skills.md#Athletics))\
    \ check as an action, freeing itself or a creature within reach from the rock\
    \ on a success. The rock has AC 17 and 10 hit points, and it is immune to fire,\
    \ poison, and psychic damage."
  "name": "Breath Weapon (Recharge 5-6)"
"source":
- "MOT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MOT/Two-Headed%20Cerberus.webp"
```
^statblock

```encounter-table
name: Two-Headed Cerberus
creatures:
 - 1: Two-Headed Cerberus
```