---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/ftd
- monster/cr/6
- monster/size/medium
- monster/type/monstrosity
aliases: ["Draconian Mastermind"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Fizban's Treasury of Dragons p. 180
---
# [Draconian Mastermind](2-Mechanics\CLI\bestiary\monstrosity/draconian-mastermind-ftd.md)
*Source: Fizban's Treasury of Dragons p. 180*  

The rarest and most powerful of the draconians are the masterminds—spellcasters and strategists who most often serve as military commanders or as advisors to those who created them. They emerge from gold, red, or amethyst dragon eggs, wingless but possessed of an arsenal of eldritch power. Like their dragon progenitors, masterminds have a breath weapon—a billowing cloud of poisonous gas. They also have formidable claws and teeth they use to rend foes in close combat.

Dying draconian masterminds are a sight to behold, as their magical essence coalesces as a ball of lightning that arcs out at those nearby.

On the world of Krynn, draconian masterminds formed from gold dragon eggs are called aurak draconians.

## Draconians

Draconians are bipedal monsters born from dragon eggs that have been corrupted or warped by powerful magic. Most often, this corruption is a deliberate act, the work of an aspiring tyrant seeking to transform stolen eggs into a draconian army. A single corrupted egg yields several draconians of the same kind. A draconian might be taken for a dragonborn at first glance, though most kinds of draconians have wings.

When draconians die, they do not go quietly. Instead, their lifeless bodies unleash a last act of magical violence.

```statblock
"name": "Draconian Mastermind (FTD)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"stats":
- !!int "13"
- !!int "14"
- !!int "16"
- !!int "15"
- !!int "11"
- !!int "17"
"speed": "35 ft."
"saves":
  "Charisma": !!int "6"
  "Wisdom": !!int "3"
  "Intelligence": !!int "5"
"skillsaves":
  "Perception": !!int "3"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)"
"senses": "truesight 60 ft., passive Perception 13"
"languages": "Common, Draconic"
"cr": "6"
"traits":
- "desc": "The draconian casts one of the following spells, requiring no material\
    \ components and using Charisma as the spellcasting ability (spell save DC 14):\n\
    \nAt will: [invisibility](/2-Mechanics/CLI/spells/invisibility.md), [mage\
    \ hand](/2-Mechanics/CLI/spells/mage-hand.md)\n\n2/day each: [dimension door](/2-Mechanics/CLI/spells/dimension-door.md),\
    \ [disguise self](/2-Mechanics/CLI/spells/disguise-self.md), [sending](/2-Mechanics/CLI/spells/sending.md)"
  "name": "Spellcasting"
- "desc": "When the draconian is reduced to 0 hit points, its magical essence lashes\
    \ out as a ball of lightning at the closest creature within 30 feet of it before\
    \ arcing out to up to two other creatures within 15 feet of the first. Each creature\
    \ must make a DC 14 Dexterity saving throw. On a failed save, the creature takes\
    \ 9 (2d8) lightning damage and is [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)\
    \ until the end of its next turn. On a successful save, the creature takes half\
    \ as much damage and isn't [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)."
  "name": "Death Throes"
"actions":
- "desc": "The draconian makes three Rend or Energy Ray attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) slashing damage."
  "name": "Rend"
- "desc": "Ranged Spell Attack: +6 to hit, range 60 ft., one target. Hit: 8\
    \ (1d10 + 3) force damage."
  "name": "Energy Ray"
- "desc": "The draconian exhales a 15-foot cone of noxious gas. Each creature in that\
    \ area must make a DC 14 Constitution saving throw. On a failed save, the creature\
    \ takes 21 (6d6) poison damage and gains 1 level of [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion).\
    \ On a successful save, the creature takes half as much damage, doesn't gain [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
    \ and is immune to all draconians' Noxious Breath for 24 hours."
  "name": "Noxious Breath (Recharge 5-6)"
"reactions":
- "desc": "When the draconian is hit by an attack roll, it can create an [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ barrier of magical force around itself, granting it a +5 bonus to its AC against\
    \ that attack and potentially causing the attack to miss."
  "name": "Magic Shield (3/Day)"
"source":
- "FTD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/FTD/Draconian%20Mastermind.webp"
```
^statblock

```encounter-table
name: Draconian Mastermind
creatures:
 - 1: Draconian Mastermind
```