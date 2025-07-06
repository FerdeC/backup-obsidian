---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/5
- monster/size/huge
- monster/type/beast
aliases: ["Elder Giant Lizard"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 176
---
# [Elder Giant Lizard](2-Mechanics\CLI\bestiary\beast/elder-giant-lizard-tftyp.md)
*Source: Tales from the Yawning Portal p. 176*  

```statblock
"name": "Elder Giant Lizard (TftYP)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "9d12 + 27"
"stats":
- !!int "21"
- !!int "9"
- !!int "17"
- !!int "2"
- !!int "10"
- !!int "7"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Stealth": !!int "5"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "5"
"traits":
- "desc": "The lizard can hold its breath for 30 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "The lizard makes two attacks: one with its bite and one with its tail."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 21\
    \ (3d10 + 5) piercing damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 16). Until this grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and the lizard can't bite another target."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target not [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ by the lizard. Hit: 14 (2d8 + 5) bludgeoning damage. If the target is a\
    \ creature, it must succeed on a DC 16 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Tail"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Elder%20Giant%20Lizard.webp"
```
^statblock

```encounter-table
name: Elder Giant Lizard
creatures:
 - 1: Elder Giant Lizard
```