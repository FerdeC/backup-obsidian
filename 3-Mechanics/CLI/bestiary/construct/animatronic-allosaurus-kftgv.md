---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/2
- monster/size/large
- monster/type/construct
aliases: ["Animatronic Allosaurus"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 22
---
# [Animatronic Allosaurus](2-Mechanics\CLI\bestiary\construct/animatronic-allosaurus-kftgv.md)
*Source: Keys from the Golden Vault p. 22*  

The allosaurus is a predatory dinosaur of great size, strength, and speed. It can run down almost any prey over open ground, pouncing to pull creatures down with its wicked claws.

```statblock
"name": "Animatronic Allosaurus (KftGV)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "51"
"hit_dice": "6d10 + 18"
"stats":
- !!int "19"
- !!int "13"
- !!int "17"
- !!int "2"
- !!int "12"
- !!int "5"
"speed": "60 ft."
"skillsaves":
  "Perception": !!int "5"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "passive Perception 15"
"languages": ""
"cr": "2"
"traits":
- "desc": "If the animatronic allosaurus moves at least 30 feet straight toward a\
    \ creature and then hits it with a claw attack on the same turn, that target must\
    \ succeed on a DC 13 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone).\
    \ If the target is [prone](/2-Mechanics/CLI/rules/conditions.md#prone), the animatronic\
    \ allosaurus can make one bite attack against it as a bonus action."
  "name": "Pounce"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 15\
    \ (2d10 + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) slashing damage."
  "name": "Claw"
"source":
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/KftGV/Animatronic%20Allosaurus.webp"
```
^statblock

```encounter-table
name: Animatronic Allosaurus
creatures:
 - 1: Animatronic Allosaurus
```