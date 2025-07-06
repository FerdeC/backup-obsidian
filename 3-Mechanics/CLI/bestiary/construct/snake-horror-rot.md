---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/rot
- monster/cr/4
- monster/size/medium
- monster/type/construct
aliases: ["Snake Horror"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: The Rise of Tiamat p. 46
---
# [Snake Horror](2-Mechanics\CLI\bestiary\construct/snake-horror-rot.md)
*Source: The Rise of Tiamat p. 46*  

```statblock
"name": "Snake Horror (RoT)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "20"
"ac_class": "[plate armor](/2-Mechanics/CLI/items/plate-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "60"
"hit_dice": "8d8 + 24"
"stats":
- !!int "18"
- !!int "13"
- !!int "16"
- !!int "10"
- !!int "10"
- !!int "10"
"speed": "30 ft., fly 30 ft."
"skillsaves":
  "Perception": !!int "4"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't adamantine"
"damage_immunities": "force, necrotic, poison"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned),\
  \ [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 14"
"languages": "understands the languages of its creator but can't speak"
"cr": "4"
"traits":
- "desc": "The snake horror has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
- "desc": "The snake horror is immune to three spells chosen by its creator. Typical\
    \ immunities include [fireball](/2-Mechanics/CLI/spells/fireball.md), [heat metal](/2-Mechanics/CLI/spells/heat-metal.md),\
    \ and [lightning bolt](/2-Mechanics/CLI/spells/lightning-bolt.md)."
  "name": "Spell Immunity"
"actions":
- "desc": "The snake horror makes two longsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands,\
    \ and the target must make a DC 12 Constitution saving throw, taking 9 (2d8)\
    \ poison damage on a failed save, or half as much damage on a successful one."
  "name": "Longsword"
"source":
- "RoT"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/RoT/Snake%20Horror.webp"
```
^statblock

```encounter-table
name: Snake Horror
creatures:
 - 1: Snake Horror
```