---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/2
- monster/size/medium
- monster/type/fiend/demon
aliases: ["Rutterkin"]
NoteIcon: monster
BestiaryType: fiend (demon)
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 210, Mordenkainen's Tome of Foes p. 136
---
# [Rutterkin](2-Mechanics\CLI\bestiary\fiend/rutterkin-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 210, Mordenkainen's Tome of Foes p. 136*  

> [!quote]- A quote from Tasha  
> 
> Eugh, rutterkins. You've heard of stinking cloud—now get ready for its sequel, rancid crows.
> 
> (Mordenkainen, my dear, I know you just died inside when you read that. Kisses!)

Rutterkins are warped demons that roam the Abyss in mobs, constantly searching for intruders to surround and devour. These Fiends protect the Abyss from non-demons. When they spot any interlopers, they gather in a crowd and surge forward, emitting a wave of fear in advance of their attacks that leaves their victims terrified and rooted in place.

Creatures bitten by rutterkins are exposed to a terrible disease that infects them with the corrupting influence of the Abyss. Victims afflicted with the disease experience tremendous pain as their bodies become disfigured, flesh twisting around the bones, until they transform to join the mass of [manes](/2-Mechanics/CLI/bestiary/fiend/manes.md) demons that follow in the wake of the rutterkin mob that laid them low.

```statblock
"name": "Rutterkin (MPMM)"
"size": "Medium"
"type": "fiend"
"subtype": "demon"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "12"
"hp": !!int "37"
"hit_dice": "5d8 + 15"
"stats":
- !!int "14"
- !!int "15"
- !!int "17"
- !!int "5"
- !!int "12"
- !!int "6"
"speed": "20 ft."
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "understands Abyssal but can't speak"
"cr": "2"
"traits":
- "desc": "When a creature that isn't a demon starts its turn within 30 feet of one\
    \ or more rutterkins, that creature must make a DC 11 Wisdom saving throw. The\
    \ creature has disadvantage on the save if it's within 30 feet of six or more\
    \ rutterkins. On a failed save, the creature becomes [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ of the rutterkins for 1 minute. While [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ in this way, the creature is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained).\
    \ At the end of each of the [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ creature's turns, it can repeat the saving throw, ending the effect on itself\
    \ on a success. On a successful save, the creature is immune to the Crippling\
    \ Fear of all rutterkins for 24 hours."
  "name": "Immobilizing Fear"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 12\
    \ (3d6 + 2) piercing damage. If the target is a creature, it must succeed on\
    \ a DC 13 Constitution saving throw against disease or become [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned).\
    \ At the end of each long rest, the [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ target can repeat the saving throw, ending the effect on itself on a success.\
    \ If the target is reduced to 0 hit points while [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ in this way, it dies and instantly transforms into a living [manes](/2-Mechanics/CLI/bestiary/fiend/manes.md).\
    \ The transformation can be undone only by a [wish](/2-Mechanics/CLI/spells/wish.md)\
    \ spell."
  "name": "Bite"
"source":
- "MPMM"
- "MTF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPMM/Rutterkin.webp"
```
^statblock

```encounter-table
name: Rutterkin
creatures:
 - 1: Rutterkin
```