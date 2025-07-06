---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/11
- monster/size/huge
- monster/type/monstrosity
aliases: ["Necrotic Centipede"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 119
---
# [Necrotic Centipede](2-Mechanics\CLI\bestiary\monstrosity/necrotic-centipede-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 119*  

```statblock
"name": "Necrotic Centipede (BGDIA)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "195"
"hit_dice": "17d12 + 85"
"stats":
- !!int "24"
- !!int "13"
- !!int "21"
- !!int "4"
- !!int "10"
- !!int "5"
"speed": "30 ft., burrow 20 ft."
"damage_immunities": "necrotic, fire"
"senses": "darkvision 60 ft., tremorsense 60 ft., passive Perception 10"
"languages": ""
"cr": "11"
"traits":
- "desc": "A creature that touches the centipede or hits it with a melee attack while\
    \ within 5 feet of it takes 10 (3d6) necrotic damage."
  "name": "Necrotic Body"
"actions":
- "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 40\
    \ (6d10 + 7) piercing damage plus 10 (3d6) necrotic damage. If the target\
    \ is a creature, it is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 17). Until this grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and the centipede can't bite another target."
  "name": "Bite"
- "desc": "The centipede makes one bite attack against a Medium or smaller creature\
    \ it is grappling. If the attack hits, that creature takes the bite's damage and\
    \ is swallowed, and the grapple ends. While swallowed, the creature is [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded)\
    \ and [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained), it has total\
    \ cover against attacks and other effects outside the centipede, and it takes\
    \ 21 (6d6) acid damage at the start of each of the centipede's turns.\n\nIf\
    \ the centipede takes 30 damage or more on a single turn from a creature inside\
    \ it, the centipede must succeed on a DC 15 Constitution saving throw at the end\
    \ of that turn or regurgitate all swallowed creatures, which fall [prone](/2-Mechanics/CLI/rules/conditions.md#prone)\
    \ in a space within 10 feet of the centipede. If the centipede dies, a swallowed\
    \ creature is no longer [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ by it and can escape from the corpse using 15 feet of movement, exiting [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Swallow"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Necrotic%20Centipede.webp"
```
^statblock

```encounter-table
name: Necrotic Centipede
creatures:
 - 1: Necrotic Centipede
```