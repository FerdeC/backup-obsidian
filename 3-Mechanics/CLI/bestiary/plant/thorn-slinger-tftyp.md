---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/1-2
- monster/size/large
- monster/type/plant
aliases: ["Thorn Slinger"]
NoteIcon: monster
BestiaryType: plant
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 246
---
# [Thorn Slinger](2-Mechanics\CLI\bestiary\plant/thorn-slinger-tftyp.md)
*Source: Tales from the Yawning Portal p. 246*  

```statblock
"name": "Thorn Slinger (TftYP)"
"size": "Large"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "32"
"hit_dice": "5d10 + 5"
"stats":
- !!int "13"
- !!int "12"
- !!int "12"
- !!int "1"
- !!int "10"
- !!int "1"
"speed": "10 ft."
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 10"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "The thorn slinger adheres to anything that touches it. A Medium or smaller\
    \ creature adhered to the thorn slinger is also [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ by it (escape DC 11). Ability checks made to escape this grapple have disadvantage.\n\
    \nAt the end of each of the thorn slinger's turns, anything [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ by it takes 3 (1d6) acid damage."
  "name": "Adhesive Blossoms"
- "desc": "While the thorn slinger remains motionless, it is indistinguishable from\
    \ an inanimate bush."
  "name": "False Appearance"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 30 ft.,\
    \ one target. Hit: 8 (2d6 + 1) piercing damage."
  "name": "Thorns"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Thorn%20Slinger.webp"
```
^statblock

```encounter-table
name: Thorn Slinger
creatures:
 - 1: Thorn Slinger
```