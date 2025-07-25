---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mot
- monster/cr/1-2
- monster/size/large
- monster/type/monstrosity
aliases: ["Hippocamp"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Mythic Odysseys of Theros p. 227
---
# [Hippocamp](2-Mechanics\CLI\bestiary\monstrosity/hippocamp-mot.md)
*Source: Mythic Odysseys of Theros p. 227*  

Noble steeds of the sea, hippocamps feature in countless tales as guides and mounts to tritons and other ocean-faring heroes. While these curious but cautious aquatic equines naturally travel in herds, many hold valued places in triton society. Considered to be servants of Thassa, hippocamps are often unpredictable, but their great speed and strength can prove awe-inspiring when harnessed by the god's will.

```statblock
"name": "Hippocamp (MOT)"
"size": "Large"
"type": "monstrosity"
"alignment": "Chaotic Good"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "22"
"hit_dice": "4d10"
"stats":
- !!int "14"
- !!int "15"
- !!int "11"
- !!int "5"
- !!int "10"
- !!int "6"
"speed": "20 ft., swim 50 ft."
"damage_resistances": "cold"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "The hippocamp can breathe air and water."
  "name": "Amphibious"
- "desc": "If the hippocamp moves at least 20 feet straight toward a target and then\
    \ hits it with a ram attack on the same turn, the target takes an extra 7 (2d6)\
    \ bludgeoning damage. If the target is a creature, it must succeed on a DC 12\
    \ Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Charge"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 9 (2d6\
    \ + 2) bludgeoning damage."
  "name": "Hooves"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage."
  "name": "Ram"
"source":
- "MOT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MOT/Hippocamp.webp"
```
^statblock

```encounter-table
name: Hippocamp
creatures:
 - 1: Hippocamp
```