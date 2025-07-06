---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/1-2
- monster/size/large
- monster/type/elemental
aliases: ["Ashen Warhorse"]
NoteIcon: monster
BestiaryType: elemental
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 158
---
# [Ashen Warhorse](2-Mechanics\CLI\bestiary\elemental/ashen-warhorse-kftgv.md)
*Source: Keys from the Golden Vault p. 158*  

```statblock
"name": "Ashen Warhorse (KftGV)"
"size": "Large"
"type": "elemental"
"alignment": "Lawful Evil"
"ac": !!int "11"
"hp": !!int "19"
"hit_dice": "3d10 + 3"
"stats":
- !!int "18"
- !!int "12"
- !!int "13"
- !!int "2"
- !!int "12"
- !!int "7"
"speed": "60 ft."
"damage_immunities": "fire"
"senses": "passive Perception 11"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "If the horse moves at least 20 feet straight toward a creature and then\
    \ hits it with a hooves attack on the same turn, that target must succeed on a\
    \ DC 14 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone).\
    \ If the target is [prone](/2-Mechanics/CLI/rules/conditions.md#prone), the horse\
    \ can make another attack with its hooves against it as a bonus action."
  "name": "Trampling Charge"
- "desc": "When the horse drops to 0 hit points, it is reduced to a pile of ash, and\
    \ any equipment it was wearing or carrying falls to the ground."
  "name": "Ashen Creature"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) bludgeoning damage."
  "name": "Hooves"
"source":
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/KftGV/Ashen%20Warhorse.webp"
```
^statblock

```encounter-table
name: Ashen Warhorse
creatures:
 - 1: Ashen Warhorse
```