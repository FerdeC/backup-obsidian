---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/6
- monster/size/medium
- monster/type/monstrosity/sorcerer
aliases: ["Captain Hask"]
NoteIcon: monster
BestiaryType: monstrosity (sorcerer)
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 148
---
# [Captain Hask](2-Mechanics\CLI\bestiary\npc/captain-hask-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 148*  

```statblock
"name": "Captain Hask (DSotDQ)"
"size": "Medium"
"type": "monstrosity"
"subtype": "sorcerer"
"alignment": "typically  Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"stats":
- !!int "13"
- !!int "14"
- !!int "16"
- !!int "16"
- !!int "11"
- !!int "17"
"speed": "35 ft."
"saves":
  "Charisma": !!int "6"
  "Wisdom": !!int "3"
  "Intelligence": !!int "6"
"skillsaves":
  "Perception": !!int "3"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)"
"senses": "truesight 60 ft., passive Perception 13"
"languages": "Common, Draconic"
"cr": "6"
"traits":
- "desc": "Hask casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 14):\n\nAt will:\
    \ [invisibility](/2-Mechanics/CLI/spells/invisibility.md), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md)\n\
    \n1/day: [dominate person](/2-Mechanics/CLI/spells/dominate-person.md)\n\n\
    2/day each: [dimension door](/2-Mechanics/CLI/spells/dimension-door.md), [disguise\
    \ self](/2-Mechanics/CLI/spells/disguise-self.md), [sending](/2-Mechanics/CLI/spells/sending.md)"
  "name": "Spellcasting"
- "desc": "Hask radiates a commanding presence in a 20-foot-radius sphere centered\
    \ on itself. A draconian in the aura that can see or hear the aurak can't be [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ and has advantage on saving throws made to avoid or end the [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ condition on itself."
  "name": "Aura of Command"
- "desc": "When Hask is reduced to 0 hit points, its magical essence lashes out as\
    \ a ball of lightning at the closest creature within 30 feet of it before arcing\
    \ out to up to two other creatures within 15 feet of the first. Each creature\
    \ must make a DC 14 Dexterity saving throw. On a failed save, the creature takes\
    \ 9 (2d8) lightning damage and is [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)\
    \ until the end of its next turn. On a successful save, the creature takes half\
    \ as much damage and isn't [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)."
  "name": "Death Throes"
"actions":
- "desc": "Hask makes three Rend or Energy Ray attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (1d12\
    \ + 2) slashing damage."
  "name": "Rend"
- "desc": "Ranged Spell Attack: +6 to hit, range 60 ft., one target. Hit: 8\
    \ (1d10 + 3) force damage."
  "name": "Energy Ray"
- "desc": "Hask exhales a 15-foot cone of noxious gas. Each creature in that area\
    \ must make a DC 14 Constitution saving throw. On a failed save, the creature\
    \ takes 21 (6d6) poison damage and gains 1 level of [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion).\
    \ On a successful save, the creature takes half as much damage, doesn't gain [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
    \ and is immune to all draconians' Noxious Breath for 24 hours."
  "name": "Noxious Breath (Recharge 5-6)"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Captain%20Hask.webp"
```
^statblock

```encounter-table
name: Captain Hask
creatures:
 - 1: Captain Hask
```