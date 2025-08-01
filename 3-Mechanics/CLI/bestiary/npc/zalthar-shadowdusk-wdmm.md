---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/17
- monster/size/medium
- monster/type/undead
aliases: ["Zalthar Shadowdusk"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 286
---
# [Zalthar Shadowdusk](2-Mechanics\CLI\bestiary\npc/zalthar-shadowdusk-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 286*  

```statblock
"name": "Zalthar Shadowdusk (WDMM)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "20"
"ac_class": "[plate armor](/2-Mechanics/CLI/items/plate-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "180"
"hit_dice": "19d8 + 95"
"stats":
- !!int "20"
- !!int "11"
- !!int "20"
- !!int "12"
- !!int "16"
- !!int "18"
"speed": "30 ft."
"saves":
  "Charisma": !!int "10"
  "Dexterity": !!int "6"
  "Wisdom": !!int "9"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Abyssal, Common, Deep Speech"
"cr": "17"
"traits":
- "desc": "Zalthar is a 19th-level spellcaster. Its spellcasting ability is Charisma\
    \ (spell save DC 18, +10 to hit with spell attacks). It has the following paladin\
    \ spells prepared:\n\n1st level (4 slots): [command](/2-Mechanics/CLI/spells/command.md),\
    \ [compelled duel](/2-Mechanics/CLI/spells/compelled-duel.md), [searing smite](/2-Mechanics/CLI/spells/searing-smite.md)\n\
    \n2nd level (3 slots): [hold person](/2-Mechanics/CLI/spells/hold-person.md),\
    \ [magic weapon](/2-Mechanics/CLI/spells/magic-weapon.md)\n\n3rd level (3 slots):\
    \ [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), [elemental weapon](/2-Mechanics/CLI/spells/elemental-weapon.md)\n\
    \n4th level (3 slots): [locate creature](/2-Mechanics/CLI/spells/locate-creature.md),\
    \ [staggering smite](/2-Mechanics/CLI/spells/staggering-smite.md)\n\n5th level\
    \ (2 slots): [destructive wave](/2-Mechanics/CLI/spells/destructive-wave.md)\
    \ (necrotic)"
  "name": "Spellcasting"
- "desc": "Zalthar wields a [nine lives stealer](/2-Mechanics/CLI/items/nine-lives-stealer.md)\
    \ longsword with 5 charges remaining."
  "name": "Special Equipment"
- "desc": "Zalthar has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Unless Zalthar is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated),\
    \ it and undead creatures of its choice within 60 feet of it have advantage on\
    \ saving throws against features that turn undead."
  "name": "Marshal Undead"
"actions":
- "desc": "Zalthar makes three longsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +13 to hit, reach 5 ft., one target. Hit: 11\
    \ (1d8 + 7) slashing damage, or 12 (1d10 + 7) slashing damage if used with\
    \ two hands, plus 18 (4d8) necrotic damage."
  "name": "Nine Lives Stealer Longsword"
- "desc": "Zalthar hurls a magical ball of fire that explodes at a point it can see\
    \ within 120 feet of it. Each creature in a 20-foot-radius sphere centered on\
    \ that point must make a DC 18 Dexterity saving throw. The sphere spreads around\
    \ corners. A creature takes 35 (10d6) fire damage and 35 (10d6) necrotic damage\
    \ on a failed save, or half as much damage on a successful one."
  "name": "Hellfire Orb (1/Day)"
"reactions":
- "desc": "Zalthar adds 6 to its AC against one melee attack that would hit it. To\
    \ do so, Zalthar must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Zalthar%20Shadowdusk.webp"
```
^statblock

```encounter-table
name: Zalthar Shadowdusk
creatures:
 - 1: Zalthar Shadowdusk
```