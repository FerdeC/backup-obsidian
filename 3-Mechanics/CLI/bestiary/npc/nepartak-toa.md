---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/4
- monster/size/tiny
- monster/type/undead
aliases: ["Nepartak"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 137
---
# [Nepartak](2-Mechanics\CLI\bestiary\npc/nepartak-toa.md)
*Source: Tomb of Annihilation p. 137*  

```statblock
"name": "Nepartak (ToA)"
"size": "Tiny"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "40"
"hit_dice": "9d4 + 18"
"stats":
- !!int "1"
- !!int "17"
- !!int "14"
- !!int "16"
- !!int "10"
- !!int "11"
"speed": "0 ft., fly 40 ft. (hover)"
"skillsaves":
  "Perception": !!int "2"
  "Arcana": !!int "5"
"damage_resistances": "lightning, necrotic, piercing"
"damage_immunities": "cold, fire, poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned), [prone](/2-Mechanics/CLI/rules/conditions.md#prone)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, telepathy 30 ft."
"cr": "4"
"traits":
- "desc": "Nepartak is a 5th-level spellcaster. Its spellcasting ability is Intelligence\
    \ (spell save DC 13, +5 to hit with spell attacks). It requires no somatic or\
    \ material components to cast its spells. Nepartak has the following wizard spells\
    \ prepared:\n\nCantrips (at will): [mage hand](/2-Mechanics/CLI/spells/mage-hand.md)\n\
    \n1st level (3 slots): [magic missile](/2-Mechanics/CLI/spells/magic-missile.md),\
    \ [shield](/2-Mechanics/CLI/spells/shield.md)\n\n2nd level (2 slots): [blur](/2-Mechanics/CLI/spells/blur.md),\
    \ [flaming sphere](/2-Mechanics/CLI/spells/flaming-sphere.md)\n\n3rd level (1\
    \ slots): [fireball](/2-Mechanics/CLI/spells/fireball.md)"
  "name": "Spellcasting"
- "desc": "Nepartak sheds either dim light in a 15-foot radius, or bright light in\
    \ a 15-foot radius and dim light for an additional 15 feet. It can switch between\
    \ the options as an action."
  "name": "Illumination"
- "desc": "Nepartak has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "If Nepartak is destroyed, it regains all its hit points in 1 hour unless\
    \ holy water is sprinkled on its remains or a [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md)\
    \ or [remove curse](/2-Mechanics/CLI/spells/remove-curse.md) spell is cast on\
    \ them."
  "name": "Rejuvenation"
"actions":
- "desc": "Nepartak uses Fire Ray twice."
  "name": "Multiattack"
- "desc": "Ranged Spell Attack: +5 to hit, range 30 ft., one target. Hit: 10\
    \ (3d6) fire damage."
  "name": "Fire Ray"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Nepartak.webp"
```
^statblock

```encounter-table
name: Nepartak
creatures:
 - 1: Nepartak
```