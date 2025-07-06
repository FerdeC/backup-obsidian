---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/2
- monster/size/large
- monster/type/monstrosity
aliases: ["Eldritch Horror Hatchling"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 24
---
# [Eldritch Horror Hatchling](2-Mechanics\CLI\bestiary\monstrosity/eldritch-horror-hatchling-kftgv.md)
*Source: Keys from the Golden Vault p. 24*  

```statblock
"name": "Eldritch Horror Hatchling (KftGV)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor; 11 while prone"
"hp": !!int "39"
"hit_dice": "6d10 + 6"
"stats":
- !!int "17"
- !!int "11"
- !!int "13"
- !!int "1"
- !!int "13"
- !!int "6"
"speed": "30 ft., burrow 10 ft."
"senses": "darkvision 60 ft., tremorsense 60 ft., passive Perception 11"
"languages": ""
"cr": "2"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) slashing damage plus 3 (1d6) poison damage. If the target is a\
    \ Large or smaller creature, it is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 13). Until this grapple ends, the eldritch horror hatchling can bite\
    \ only the [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled) creature\
    \ and has advantage on attack rolls to do so."
  "name": "Bite"
- "desc": "The eldritch horror hatchling spits acid in a line that is 30 feet long\
    \ and 5 feet wide, provided that it has no creature [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled).\
    \ Each creature in that line must make a DC 13 Dexterity saving throw, taking\
    \ 10 (3d6) acid damage on a failed save, or half as much damage on a successful\
    \ one."
  "name": "Acid Spray (Recharge 6)"
"source":
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/KftGV/Eldritch%20Horror%20Hatchling.webp"
```
^statblock

```encounter-table
name: Eldritch Horror Hatchling
creatures:
 - 1: Eldritch Horror Hatchling
```