---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/22
- monster/size/large
- monster/type/construct
aliases: ["Trobriand"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 294
---
# [Trobriand](2-Mechanics\CLI\bestiary\npc/trobriand-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 294*  

```statblock
"name": "Trobriand (WDMM)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "210"
"hit_dice": "20d10 + 100"
"stats":
- !!int "24"
- !!int "9"
- !!int "20"
- !!int "20"
- !!int "11"
- !!int "1"
"speed": "30 ft."
"damage_immunities": "fire; poison; psychic; bludgeoning, piercing, slashing from\
  \ nonmagical attacks that aren't adamantine"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "22"
"traits":
- "desc": "Trobriand is an 18th-level spellcaster. His spellcasting ability is Intelligence\
    \ (spell save DC 20, +12 to hit with spell attacks). He has the following wizard\
    \ spells prepared:\n\nCantrips (at will): [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\
    \n1st level (4 slots): [detect magic](/2-Mechanics/CLI/spells/detect-magic.md),\
    \ [magic missile](/2-Mechanics/CLI/spells/magic-missile.md), [shield](/2-Mechanics/CLI/spells/shield.md)\n\
    \n2nd level (3 slots): [blur](/2-Mechanics/CLI/spells/blur.md), [detect thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md),\
    \ [misty step](/2-Mechanics/CLI/spells/misty-step.md), [shatter](/2-Mechanics/CLI/spells/shatter.md)\n\
    \n3rd level (3 slots): [counterspell](/2-Mechanics/CLI/spells/counterspell.md),\
    \ [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), [fireball](/2-Mechanics/CLI/spells/fireball.md),\
    \ [haste](/2-Mechanics/CLI/spells/haste.md)\n\n4th level (3 slots): [blight](/2-Mechanics/CLI/spells/blight.md),\
    \ [greater invisibility](/2-Mechanics/CLI/spells/greater-invisibility.md)\n\n\
    5th level (3 slots): [animate objects](/2-Mechanics/CLI/spells/animate-objects.md),\
    \ [Bigby's hand](/2-Mechanics/CLI/spells/bigbys-hand.md), [scrying](/2-Mechanics/CLI/spells/scrying.md)\n\
    \n6th level (1 slots): [chain lightning](/2-Mechanics/CLI/spells/chain-lightning.md),\
    \ [globe of invulnerability](/2-Mechanics/CLI/spells/globe-of-invulnerability.md)\n\
    \n7th level (1 slots): [finger of death](/2-Mechanics/CLI/spells/finger-of-death.md),\
    \ [forcecage](/2-Mechanics/CLI/spells/forcecage.md)\n\n8th level (1 slots):\
    \ [incendiary cloud](/2-Mechanics/CLI/spells/incendiary-cloud.md), [power word\
    \ stun](/2-Mechanics/CLI/spells/power-word-stun.md)\n\n9th level (1 slots):\
    \ [power word kill](/2-Mechanics/CLI/spells/power-word-kill.md)"
  "name": "Spellcasting"
- "desc": "Whenever Trobriand is subjected to fire damage, it takes no damage and\
    \ instead regains a number of hit points equal to the fire damage dealt."
  "name": "Fire Absorption"
- "desc": "Trobriand is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
- "desc": "Trobriand has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Trobriand's weapon attacks are magical."
  "name": "Magic Weapons"
"actions":
- "desc": "Trobriand makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +13 to hit, reach 5 ft., one target. Hit: 20\
    \ (3d8 + 7) bludgeoning damage."
  "name": "Slam"
- "desc": "Melee Weapon Attack: +13 to hit, reach 10 ft., one target. Hit: 23\
    \ (3d10 + 7) slashing damage."
  "name": "Sword"
- "desc": "Trobriand exhales poisonous gas in a 15-foot cone. Each creature in that\
    \ area must make a DC 19 Constitution saving throw, taking 45 (10d8) poison\
    \ damage on a failed save, or half as much damage on a successful one."
  "name": "Poison Breath (Recharge 5-6)"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Trobriand.webp"
```
^statblock

```encounter-table
name: Trobriand
creatures:
 - 1: Trobriand
```