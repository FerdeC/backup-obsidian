---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/1-2
- monster/environment/grassland
- monster/environment/urban
- monster/size/large
- monster/type/fiend/cattle
aliases: ["Stench Kow"]
NoteIcon: monster
BestiaryType: fiend (cattle)
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 72, Volo's Guide to Monsters p. 208
---
# [Stench Kow](2-Mechanics\CLI\bestiary\fiend/stench-kow-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 72, Volo's Guide to Monsters p. 208*  

Stench kows are misshapen bison native to the Lower Planes. These orange and green creatures defend themselves by exuding a miasma so hideous as to be toxic. Some mischievous and malevolent wizards have summoned stench kows to the Material Plane, disguised the creatures as oxen, and let the infernal bison loose on unsuspecting villages.

## Cattle

Many kinds of cattle roam the multiverse, some of them domesticated and others feral. In many cultures, cattle are almost like family to the folk who tend to them.

```statblock
"name": "Stench Kow (MPMM)"
"size": "Large"
"type": "fiend"
"subtype": "cattle"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "15"
"hit_dice": "2d10 + 4"
"stats":
- !!int "18"
- !!int "10"
- !!int "14"
- !!int "2"
- !!int "10"
- !!int "4"
"speed": "30 ft."
"damage_resistances": "cold, fire, poison"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "Any creature other than a stench kow that starts its turn within 5 feet\
    \ of the stench kow must succeed on a DC 12 Constitution saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ until the start of the creature's next turn. On a successful saving throw, the\
    \ creature is immune to the Stench of all stench kows for 1 hour."
  "name": "Stench"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) piercing damage. If the stench kow moved at least 20 feet straight toward\
    \ the target immediately before the hit, the target takes an extra 7 (2d6) piercing\
    \ damage."
  "name": "Gore"
"source":
- "MPMM"
- "VGM"
- "AATM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPMM/Stench%20Kow.webp"
```
^statblock

```encounter-table
name: Stench Kow
creatures:
 - 1: Stench Kow
```

## Environment

grassland, urban