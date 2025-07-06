---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/4
- monster/size/medium
- monster/type/construct
aliases: ["Crimson Helmed Horror"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 152
---
# [Crimson Helmed Horror](2-Mechanics\CLI\bestiary\construct/crimson-helmed-horror-kftgv.md)
*Source: Keys from the Golden Vault p. 152*  

```statblock
"name": "Crimson Helmed Horror (KftGV)"
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
- "desc": "The helmed horror has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
- "desc": "The helmed horror is immune to [burning hands](/2-Mechanics/CLI/spells/burning-hands.md),\
    \ [fireball](/2-Mechanics/CLI/spells/fireball.md), and [scorching ray](/2-Mechanics/CLI/spells/scorching-ray.md)."
  "name": "Spell Immunity"
"actions":
- "desc": "The helmed horror makes two longsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) fire damage, or 9 (1d10 + 4) fire damage if used with two hands."
  "name": "Flaming Longsword"
"bonus_actions":
- "desc": "As a bonus action on its first turn in combat, the helmed horror conjures\
    \ a longsword-sized blade of fire, which appears in its free hand. This sword\
    \ disappears in a cloud of smoke when the helmed horror drops to 0 hit points."
  "name": "Conjure Sword"
"source":
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/KftGV/Crimson%20Helmed%20Horror.webp"
```
^statblock

```encounter-table
name: Crimson Helmed Horror
creatures:
 - 1: Crimson Helmed Horror
```