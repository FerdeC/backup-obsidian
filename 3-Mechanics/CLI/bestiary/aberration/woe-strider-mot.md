---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mot
- monster/cr/7
- monster/size/large
- monster/type/aberration
aliases: ["Woe Strider"]
NoteIcon: monster
BestiaryType: aberration
SourceType: Bestiary
BookSource: Mythic Odysseys of Theros p. 247
---
# [Woe Strider](2-Mechanics\CLI\bestiary\aberration/woe-strider-mot.md)
*Source: Mythic Odysseys of Theros p. 247*  

Woe striders form from the souls of those who've broken the bonds of destiny. Over centuries, these cosmic blasphemers transform into hunched, long-limbed horrors. Sadistic things, woe striders seek ways to reweave themselves into the tapestry of destiny. This leads them to search for answers within the bowels of other beings, performing murderous haruspicy in pursuit of their discarded cosmic purpose. When they fail to find answers, their unnatural cries cause reality to shudder, undermining magic and sane minds alike.

```statblock
"name": "Woe Strider (MOT)"
"size": "Large"
"type": "aberration"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "110"
"hit_dice": "13d10 + 39"
"stats":
- !!int "18"
- !!int "15"
- !!int "16"
- !!int "8"
- !!int "14"
- !!int "14"
"speed": "40 ft., climb 40 ft."
"skillsaves":
  "Intimidation": !!int "5"
  "Perception": !!int "5"
"condition_immunities": "[frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": "telepathy 120 ft."
"cr": "7"
"traits":
- "desc": "The woe strider's open mouth creates an area of antimagic, as in the [antimagic\
    \ field](/2-Mechanics/CLI/spells/antimagic-field.md) spell, in a 60-foot cone.\
    \ At the start of each of its turns, the woe strider decides which way the cone\
    \ faces and whether its mouth is open or closed."
  "name": "Antimagic Cone"
"actions":
- "desc": "The woe strider makes two claw attacks and one bite attack. If both claws\
    \ hit the same creature, the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 14)."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 7\
    \ (1d6 + 4) slashing damage plus 3 (1d6) psychic damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one creature that is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled),\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated), or [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained).\
    \ Hit: 13 (2d8 + 4) piercing damage plus 16 (3d10) psychic damage. In addition,\
    \ each magic item the creature is carrying that isn't an artifact has its magical\
    \ properties suppressed for 1 minute."
  "name": "Bite"
"source":
- "MOT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MOT/Woe%20Strider.webp"
```
^statblock

```encounter-table
name: Woe Strider
creatures:
 - 1: Woe Strider
```