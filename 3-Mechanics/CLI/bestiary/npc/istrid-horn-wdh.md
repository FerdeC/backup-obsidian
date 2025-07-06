---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/8
- monster/size/medium
- monster/type/humanoid/dwarf
aliases: ["Istrid Horn"]
NoteIcon: monster
BestiaryType: humanoid (dwarf)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 199
---
# [Istrid Horn](2-Mechanics\CLI\bestiary\npc/istrid-horn-wdh.md)
*Source: Waterdeep: Dragon Heist p. 199*  

Istrid is regarded as the Black Network's Master of Trade and Coin in Waterdeep. The shield dwarf operates an illegal lending operation out of a heavily guarded warehouse in the Dock Ward, offering loans to those in need of coin. Her interest rates are comparable to those of her competitors (including noble families of bankers such as the Cassalanters and the Irlingstars), but the penalties for not paying back Istrid's loans are severe.

Istrid worships Vergadain, the dwarven god of wealth and luck. She likes having others indebted to her, and she employs thugs and enforcers to collect on her loans. If those resources prove inadequate, Istrid can call on her old adventuring companions for assistance.

## The Doom Raiders

The Doom Raiders were five unscrupulous adventurers who liked to plunder lich lairs (called "dooms" by some). They gave up adventuring to join the Black Network and came to Waterdeep three years ago with plans to establish a Zhentarim foothold in the city. In that time, they have forged alliances with various nobles and guilds and run afoul of others, all the while fending off Harper spies.

```statblock
"name": "Istrid Horn (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[plate armor](/2-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"stats":
- !!int "12"
- !!int "10"
- !!int "14"
- !!int "11"
- !!int "17"
- !!int "13"
"speed": "25 ft."
"saves":
  "Wisdom": !!int "6"
  "Constitution": !!int "5"
"skillsaves":
  "Intimidation": !!int "4"
  "Religion": !!int "3"
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Dwarvish"
"cr": "8"
"traits":
- "desc": "Istrid is a 9th-level spellcaster. Her spellcasting ability is Wisdom (spell\
    \ save DC 14, +6 to hit with spell attacks) She has the following cleric spells\
    \ prepared:\n\nCantrips (at will): [light](/2-Mechanics/CLI/spells/light.md),\
    \ [mending](/2-Mechanics/CLI/spells/mending.md), [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md),\
    \ [spare the dying](/2-Mechanics/CLI/spells/spare-the-dying.md)\n\n1st level\
    \ (4 slots): [divine favor](/2-Mechanics/CLI/spells/divine-favor.md), [guiding\
    \ bolt](/2-Mechanics/CLI/spells/guiding-bolt.md), [healing word](/2-Mechanics/CLI/spells/healing-word.md),\
    \ [shield of faith](/2-Mechanics/CLI/spells/shield-of-faith.md)\n\n2nd level\
    \ (3 slots): [lesser restoration](/2-Mechanics/CLI/spells/lesser-restoration.md),\
    \ [magic weapon](/2-Mechanics/CLI/spells/magic-weapon.md), [hold person](/2-Mechanics/CLI/spells/hold-person.md),\
    \ [silence](/2-Mechanics/CLI/spells/silence.md), [spiritual weapon](/2-Mechanics/CLI/spells/spiritual-weapon.md)\n\
    \n3rd level (3 slots): [beacon of hope](/2-Mechanics/CLI/spells/beacon-of-hope.md),\
    \ [crusader's mantle](/2-Mechanics/CLI/spells/crusaders-mantle.md), [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md),\
    \ [revivify](/2-Mechanics/CLI/spells/revivify.md), [spirit guardians](/2-Mechanics/CLI/spells/spirit-guardians.md),\
    \ [water walk](/2-Mechanics/CLI/spells/water-walk.md)\n\n4th level (3 slots):\
    \ [banishment](/2-Mechanics/CLI/spells/banishment.md), [freedom of movement](/2-Mechanics/CLI/spells/freedom-of-movement.md),\
    \ [guardian of faith](/2-Mechanics/CLI/spells/guardian-of-faith.md), [stoneskin](/2-Mechanics/CLI/spells/stoneskin.md)\n\
    \n5th level (1 slots): [flame strike](/2-Mechanics/CLI/spells/flame-strike.md),\
    \ [mass cure wounds](/2-Mechanics/CLI/spells/mass-cure-wounds.md), [hold monster](/2-Mechanics/CLI/spells/hold-monster.md)"
  "name": "Spellcasting"
- "desc": "Istrid has advantage on saving throws against being [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)."
  "name": "Dwarven Resilience"
"actions":
- "desc": "Istrid makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 8 (2d6\
    \ + 1) bludgeoning damage."
  "name": "Maul"
- "desc": "Istrid magically pinpoints precious metals and stones, such as coins and\
    \ gems, within 60 feet of her."
  "name": "Treasure Sense (3/Day)"
"source":
- "WDH"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDH/Istrid%20Horn.webp"
```
^statblock

```encounter-table
name: Istrid Horn
creatures:
 - 1: Istrid Horn
```