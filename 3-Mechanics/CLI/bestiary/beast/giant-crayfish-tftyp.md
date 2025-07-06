---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/2
- monster/size/large
- monster/type/beast
aliases: ["Giant Crayfish"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 235
---
# [Giant Crayfish](2-Mechanics\CLI\bestiary\beast/giant-crayfish-tftyp.md)
*Source: Tales from the Yawning Portal p. 235*  

```statblock
"name": "Giant Crayfish (TftYP)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "45"
"hit_dice": "7d10 + 7"
"stats":
- !!int "15"
- !!int "13"
- !!int "13"
- !!int "1"
- !!int "9"
- !!int "3"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Stealth": !!int "3"
"senses": "blindsight 30 ft., passive Perception 9"
"languages": ""
"cr": "2"
"traits":
- "desc": "The giant crayfish can breathe air and water."
  "name": "Amphibious"
"actions":
- "desc": "The giant crayfish makes two claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (1d10\
    \ + 2) bludgeoning damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 12). The crayfish has two claws, each of which can grapple only one\
    \ target."
  "name": "Claw"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Giant%20Crayfish.webp"
```
^statblock

```encounter-table
name: Giant Crayfish
creatures:
 - 1: Giant Crayfish
```