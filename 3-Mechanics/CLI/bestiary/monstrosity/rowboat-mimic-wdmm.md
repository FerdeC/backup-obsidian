---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/2
- monster/size/large
- monster/type/monstrosity/shapechanger
aliases: ["Rowboat Mimic"]
NoteIcon: monster
BestiaryType: monstrosity (shapechanger)
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 76
---
# [Rowboat Mimic](2-Mechanics\CLI\bestiary\monstrosity/rowboat-mimic-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 76*  

```statblock
"name": "Rowboat Mimic (WDMM)"
"size": "Large"
"type": "monstrosity"
"subtype": "shapechanger"
"alignment": "Neutral"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "67"
"hit_dice": "9d10 + 18"
"stats":
- !!int "17"
- !!int "12"
- !!int "15"
- !!int "5"
- !!int "13"
- !!int "8"
"speed": "15 ft."
"skillsaves":
  "Stealth": !!int "5"
"damage_immunities": "acid"
"condition_immunities": "[prone](/2-Mechanics/CLI/rules/conditions.md#prone)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": ""
"cr": "2"
"traits":
- "desc": "The mimic can use its action to polymorph into an object or back into its\
    \ true, amorphous form. Its statistics are the same in each form. Any equipment\
    \ it is wearing or carrying isn't transformed. It reverts to its true form if\
    \ it dies."
  "name": "Shapechanger"
- "desc": "The mimic adheres to anything that touches it. A Huge or smaller creature\
    \ adhered to the mimic is also [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ by it (escape DC 13). Ability checks made to escape this grapple have disadvantage."
  "name": "Adhesive (Object Form Only)"
- "desc": "While the mimic remains motionless, it is indistinguishable from an ordinary\
    \ object."
  "name": "False Appearance (Object Form Only)"
- "desc": "The mimic has advantage on attack rolls against any creature [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ by it."
  "name": "Grappler"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) bludgeoning damage. If the mimic is in object form, the target is subjected\
    \ to its Adhesive trait."
  "name": "Pseudopod"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) piercing damage plus 4 (1d8) acid damage."
  "name": "Bite"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Rowboat%20Mimic.webp"
```
^statblock

```encounter-table
name: Rowboat Mimic
creatures:
 - 1: Rowboat Mimic
```