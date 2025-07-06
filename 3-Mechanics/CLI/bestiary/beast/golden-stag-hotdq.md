---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/hotdq
- monster/cr/1-4
- monster/size/large
- monster/type/beast
aliases: ["Golden Stag"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Hoard of the Dragon Queen p. 35
---
# [Golden Stag](2-Mechanics\CLI\bestiary\beast/golden-stag-hotdq.md)
*Source: Hoard of the Dragon Queen p. 35*  

```statblock
"name": "Golden Stag (HotDQ)"
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
- "desc": "If the elk moves at least 20 feet straight toward a target and then hits\
    \ it with a ram attack on the same turn, the target takes an extra 7 (2d6) damage.\
    \ If the target is a creature, it must succeed on a DC 13 Strength saving throw\
    \ or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Charge"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) bludgeoning damage."
  "name": "Ram"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one [prone](/2-Mechanics/CLI/rules/conditions.md#prone)\
    \ creature. Hit: 8 (2d4 + 3) bludgeoning damage."
  "name": "Hooves"
"source":
- "HotDQ"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/HotDQ/Golden%20Stag.webp"
```
^statblock

```encounter-table
name: Golden Stag
creatures:
 - 1: Golden Stag
```