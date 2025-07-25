---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/5
- monster/size/huge
- monster/type/beast
aliases: ["Hulking Crab"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Storm King's Thunder p. 240
---
# [Hulking Crab](2-Mechanics\CLI\bestiary\beast/hulking-crab-skt.md)
*Source: Storm King's Thunder p. 240*  

Much bigger than a giant crab, a hulking crab has a body 15 to 20 feet in diameter. Its shell is often covered with coral, anemones, ship wreckage, or some other sort of detritus salvaged from the ocean floor.

```statblock
"name": "Hulking Crab (SKT)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "76"
"hit_dice": "8d12 + 24"
"stats":
- !!int "19"
- !!int "8"
- !!int "16"
- !!int "3"
- !!int "11"
- !!int "3"
"speed": "20 ft., swim 30 ft."
"skillsaves":
  "Stealth": !!int "2"
"senses": "blindsight 30 ft., passive Perception 10"
"languages": ""
"cr": "5"
"traits":
- "desc": "The crab can breathe air and water."
  "name": "Amphibious"
- "desc": "While the crab remains motionless with its eyestalks and pincers tucked\
    \ close to its body, it resembles a natural formation or a pile of detritus. A\
    \ creature within 30 feet of it can discern its true nature with a successful\
    \ DC 15 Intelligence ([Nature](/2-Mechanics/CLI/rules/skills.md#Nature)) check."
  "name": "Shell Camouflage"
"actions":
- "desc": "The crab makes two attacks with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 20\
    \ (3d10 + 4) bludgeoning damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 15). The crab has two claws, each of which can grapple only one target"
  "name": "Claw"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Hulking%20Crab.webp"
```
^statblock

```encounter-table
name: Hulking Crab
creatures:
 - 1: Hulking Crab
```