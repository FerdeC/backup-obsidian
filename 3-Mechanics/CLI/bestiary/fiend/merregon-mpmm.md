---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/4
- monster/size/medium
- monster/type/fiend/devil
aliases: ["Merregon"]
NoteIcon: monster
BestiaryType: fiend (devil)
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 179, Mordenkainen's Tome of Foes p. 166
---
# [Merregon](2-Mechanics\CLI\bestiary\fiend/merregon-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 179, Mordenkainen's Tome of Foes p. 166*  

The souls of fallen soldiers, mercenaries, and bodyguards who served evil without reservation often find everlasting servitude in the Nine Hells as merregons. These faceless foot soldiers are the Hells' legionnaires, tasked with protecting their infernal plane and its rulers against intruders.

Merregons have no individuality and hence no need for faces. Every merregon legionnaire has a metal mask bolted to its head. Markings on the mask indicate the only elements of the wearer's identity that matter: the commander it serves and the layer of the Nine Hells it protects.

Because of their unshakable loyalty, merregons form the backbone of many devils' protective retinues. They shrink from no task, no matter how dangerous. Unless ordered to fall back, they never retreat from a fight.

```statblock
"name": "Merregon (MPMM)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Typically  Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"stats":
- !!int "18"
- !!int "14"
- !!int "17"
- !!int "6"
- !!int "12"
- !!int "8"
"speed": "30 ft."
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "understands Infernal but can't speak, telepathy 120 ft."
"cr": "4"
"traits":
- "desc": "Magical darkness doesn't impede the merregon's [darkvision](/2-Mechanics/CLI/rules/senses.md#darkvision)."
  "name": "Devil's Sight"
- "desc": "The merregon has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The merregon makes three Halberd attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 9\
    \ (1d10 + 4) slashing damage."
  "name": "Halberd"
- "desc": "Ranged Weapon Attack: +4 to hit, range 100/400 ft., one target. Hit:\
    \ 7 (1d10 + 2) piercing damage."
  "name": "Heavy Crossbow"
"reactions":
- "desc": "When another Fiend within 5 feet of the merregon is hit by an attack roll,\
    \ the merregon causes itself to be hit instead."
  "name": "Loyal Bodyguard"
"source":
- "MPMM"
- "MTF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPMM/Merregon.webp"
```
^statblock

```encounter-table
name: Merregon
creatures:
 - 1: Merregon
```