---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/human
- monster/type/humanoid/warlock
aliases: ["Markos Delphi"]
NoteIcon: monster
BestiaryType: humanoid (human, warlock)
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 53
---
# [Markos Delphi](2-Mechanics\CLI\bestiary\npc/markos-delphi-kftgv.md)
*Source: Keys from the Golden Vault p. 53*  

Markos Delphi grew up with an insatiable curiosity. Eventually, he had his fill of worldly knowledge and began delving into the arcane, eager to understand the secrets of the planes of existence. Raised in a family of scholars and academics, Markos wished to make a breakthrough discovery that would propel himself and his family to new heights.

This quest for understanding became Markos's obsession. He sequestered himself and his fellow researchers in the remote Delphi Mansion. Markos used astrology-based magic to attempt to contact other planes, and something finally answered him: an entity that called itself Krokulmar. This entity made a pact with Markos, granting insight into the multiverse in exchange for influence on the Material Plane. Markos assumed Krokulmar's intentions were benign.

```statblock
"name": "Markos Delphi (KftGV)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, warlock"
"alignment": "Chaotic Neutral"
"ac": !!int "12"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"stats":
- !!int "8"
- !!int "15"
- !!int "12"
- !!int "17"
- !!int "13"
- !!int "16"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Wisdom": !!int "3"
"skillsaves":
  "Perception": !!int "3"
  "History": !!int "7"
  "Arcana": !!int "7"
"damage_immunities": "psychic"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Celestial, Common, Deep Speech"
"cr": "3"
"traits":
- "desc": "Markos casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 13):\n\n1/day\
    \ each: [arms of Hadar](/2-Mechanics/CLI/spells/arms-of-hadar.md), [charm person](/2-Mechanics/CLI/spells/charm-person.md),\
    \ [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Markos makes two Ceremonial Blade attacks, two Psychic Orb attacks, or\
    \ one of each."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage plus 3 (1d6) poison damage. If the target is a creature,\
    \ it must succeed on a DC 13 Constitution saving throw or become [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 minute. The creature can repeat the saving throw at the end of each of\
    \ its turns, ending the effect on itself on a success."
  "name": "Ceremonial Blade"
- "desc": "Ranged Spell Attack: +5 to hit, range 60 ft., one creature. Hit:\
    \ 10 (2d6 + 3) psychic damage."
  "name": "Psychic Orb"
"bonus_actions":
- "desc": "Markos targets one Medium or Small creature he can see within 30 feet of\
    \ himself. The target must succeed on a DC 13 Constitution saving throw or it\
    \ teleports, along with any equipment it is wearing or carrying, exchanging positions\
    \ with Markos."
  "name": "Swap Space"
"source":
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/KftGV/Markos%20Delphi.webp"
```
^statblock

```encounter-table
name: Markos Delphi
creatures:
 - 1: Markos Delphi
```