---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/3
- monster/size/large
- monster/type/beast
aliases: ["Giant Lightning Eel"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 236
---
# [Giant Lightning Eel](2-Mechanics\CLI\bestiary\beast/giant-lightning-eel-tftyp.md)
*Source: Tales from the Yawning Portal p. 236*  

```statblock
"name": "Giant Lightning Eel (TftYP)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "42"
"hit_dice": "5d10 + 15"
"stats":
- !!int "11"
- !!int "17"
- !!int "16"
- !!int "2"
- !!int "12"
- !!int "3"
"speed": "5 ft., swim 30 ft."
"damage_resistances": "lightning"
"senses": "blindsight 60 ft., passive Perception 11"
"languages": ""
"cr": "3"
"traits":
- "desc": "The eel can breathe only underwater."
  "name": "Water Breathing"
"actions":
- "desc": "The eel makes two bite attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) piercing damage plus 4 (1d8) lightning damage."
  "name": "Bite"
- "desc": "One creature the eel touches within 5 feet of it outside water, or each\
    \ creature within 15 feet of it in a body of water, must make a DC 12 Constitution\
    \ saving throw. On failed save, a target takes 13 (3d8) lightning damage. If\
    \ the target takes any of this damage, the target is [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)\
    \ until the end of the eel's next turn. On a successful save, a target takes half\
    \ as much damage and isn't [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)."
  "name": "Lightning Jolt (Recharge 5-6)"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Giant%20Lightning%20Eel.webp"
```
^statblock

```encounter-table
name: Giant Lightning Eel
creatures:
 - 1: Giant Lightning Eel
```