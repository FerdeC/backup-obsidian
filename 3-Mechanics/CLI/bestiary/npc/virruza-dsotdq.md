---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/8
- monster/size/large
- monster/type/aberration/shapechanger
aliases: ["Virruza"]
NoteIcon: monster
BestiaryType: aberration (shapechanger)
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 119
---
# [Virruza](2-Mechanics\CLI\bestiary\npc/virruza-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 119*  

Changed by days of strange experiments involving draconian blood and exposure to the Spawning Shard, Virruza now looks like a tumescent draconian with warty green skin and an overly large mouth.

```statblock
"name": "Virruza (DSotDQ)"
"size": "Large"
"type": "aberration"
"subtype": "shapechanger"
"alignment": "Chaotic Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "127"
"hit_dice": "15d10 + 45"
"stats":
- !!int "18"
- !!int "15"
- !!int "16"
- !!int "11"
- !!int "8"
- !!int "12"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "2"
  "Arcana": !!int "3"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"senses": "blindsight 30 ft., darkvision 60 ft., passive Perception 12"
"languages": "Slaad, telepathy 60 ft."
"cr": "8"
"traits":
- "desc": "Virruza's innate spellcasting ability is Charisma (spell save DC 12). Virruza\
    \ can innately cast the following spells, requiring no material components:\n\n\
    At will: [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [detect\
    \ thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md)\n\
    \n1/day: [fireball](/2-Mechanics/CLI/spells/fireball.md)\n\n2/day each:\
    \ [fear](/2-Mechanics/CLI/spells/fear.md), [invisibility](/2-Mechanics/CLI/spells/invisibility.md)\
    \ (self only)"
  "name": "Innate Spellcasting"
- "desc": "When Virruza is reduced to 0 hit points, he turns into a puddle of acid\
    \ and splashes acid on those around him. Each creature within 5 feet of him must\
    \ succeed on a DC 12 Dexterity saving throw or be covered in acid for 1 minute.\
    \ A creature can use its action to scrape or wash the acid off itself or another\
    \ creature. A creature covered in the acid takes 7 (2d6) acid damage at the\
    \ start of each of its turns."
  "name": "Death Throes"
- "desc": "Virruza has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Virruza regains 10 hit points at the start of its turn if it has at least\
    \ 1 hit point."
  "name": "Regeneration"
"actions":
- "desc": "Virruza makes three attacks: one with its bite and two with its claws or\
    \ staff. Alternatively, it uses its Hurl Flame twice."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) piercing damage."
  "name": "Bite (Slaad Form Only)"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) slashing damage."
  "name": "Claw (Slaad Form Only)"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) bludgeoning damage."
  "name": "Staff"
- "desc": "Ranged Spell Attack: +4 to hit, range 60 ft., one target. Hit: 10\
    \ (3d6) fire damage. The fire ignites flammable objects that aren't being worn\
    \ or carried."
  "name": "Hurl Flame"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Virruza.webp"
```
^statblock

```encounter-table
name: Virruza
creatures:
 - 1: Virruza
```