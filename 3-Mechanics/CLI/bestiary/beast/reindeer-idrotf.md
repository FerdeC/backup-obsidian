---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/1-4
- monster/size/large
- monster/type/beast
aliases: ["Reindeer"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 107
---
# [Reindeer](2-Mechanics\CLI\bestiary\beast/reindeer-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 107*  

To ensure that they don't starve in the winter, the Reghed nomads of Icewind Dale follow the migration routes of reindeer herds and are mindful not to deplete the herds to the point where the beasts can no longer flourish or defend themselves against other natural predators.

The average adult reindeer is 5 feet tall at the shoulder and weighs 250 pounds. Both male and female reindeer have antlers, though a male's antlers are larger.

```statblock
"name": "Reindeer (IDRotF)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "13"
"hit_dice": "2d10 + 2"
"stats":
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "2"
- !!int "10"
- !!int "6"
"speed": "50 ft."
"senses": "passive Perception 10"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "If the reindeer moves at least 20 feet straight toward a target and then\
    \ hits it with a ram attack on the same turn, the target takes an extra 7 (2d6)\
    \ damage. If the target is a creature, it must succeed on a DC 13 Strength saving\
    \ throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Charge"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) bludgeoning damage."
  "name": "Ram"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one [prone](/2-Mechanics/CLI/rules/conditions.md#prone)\
    \ creature. Hit: 8 (2d4 + 3) bludgeoning damage."
  "name": "Hooves"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Reindeer.webp"
```
^statblock

```encounter-table
name: Reindeer
creatures:
 - 1: Reindeer
```