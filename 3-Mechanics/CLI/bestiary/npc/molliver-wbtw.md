---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wbtw
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Molliver"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: The Wild Beyond the Witchlight p. 226
---
# [Molliver](2-Mechanics\CLI\bestiary\npc/molliver-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 226*  

Molliver is a thief who gives most of what they steal to the destitute, keeping a few choice items for their own use. They're always ready to put themself in harm's way to see justice triumph over tyranny and inequality.

Molliver invites trouble by not thinking through the ramifications of their actions, counting on their friends to bail them out whenever they get in over their head. They always have a friendly jibe or acerbic remark on the tip of their tongue, and their cavalier attitude doesn't always sit well with their more cautious companions.

```statblock
"name": "Molliver (WBtW)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Good"
"ac": !!int "15"
"ac_class": "[+1 leather armor](/2-Mechanics/CLI/items/1-armor.md)"
"hp": !!int "60"
"hit_dice": "8d8 + 24"
"stats":
- !!int "9"
- !!int "17"
- !!int "16"
- !!int "10"
- !!int "9"
- !!int "16"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
  "Intelligence": !!int "2"
"skillsaves":
  "Sleight of Hand": !!int "7"
  "Stealth": !!int "7"
  "Acrobatics": !!int "7"
"senses": "passive Perception 9"
"languages": "Common"
"cr": "3"
"traits":
- "desc": "When subjected to an effect that allows a Dexterity saving throw to take\
    \ only half damage, Molliver takes no damage on a successful save or half damage\
    \ on a failed one, provided Molliver is not [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Evasion"
- "desc": "Molliver wears +1 leather armor and [boots of levitation](/2-Mechanics/CLI/items/boots-of-levitation.md)."
  "name": "Special Equipment"
"actions":
- "desc": "Molliver makes two Dagger or Shortsword attacks, or one of each."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage. The attack deals an extra\
    \ 7 (2d6) piercing damage if Molliver has advantage on the attack roll or if\
    \ the target is within 5 feet of one of Molliver's allies."
  "name": "Dagger"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 6\
    \ (1d6 + 3) piercing damage. The attack deals an extra 7 (2d6) piercing damage\
    \ if Molliver has advantage on the attack roll or if the target is within 5 feet\
    \ of one of Molliver's allies."
  "name": "Shortsword"
- "desc": "While wearing boots of levitation, Molliver casts [levitate](/2-Mechanics/CLI/spells/levitate.md)\
    \ (self only)."
  "name": "Levitate"
"reactions":
- "desc": "Molliver halves the damage they take from an attack made against them,\
    \ provided they can see the attacker."
  "name": "Uncanny Dodge"
"source":
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WBtW/Molliver.webp"
```
^statblock

```encounter-table
name: Molliver
creatures:
 - 1: Molliver
```