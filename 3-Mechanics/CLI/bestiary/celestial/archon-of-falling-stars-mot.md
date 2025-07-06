---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mot
- monster/cr/12
- monster/size/medium
- monster/type/celestial
aliases: ["Archon of Falling Stars"]
NoteIcon: monster
BestiaryType: celestial
SourceType: Bestiary
BookSource: Mythic Odysseys of Theros p. 212
---
# [Archon of Falling Stars](2-Mechanics\CLI\bestiary\celestial/archon-of-falling-stars-mot.md)
*Source: Mythic Odysseys of Theros p. 212*  

The epic accounting of the world's earliest histories called *The Cosmogony* recounts the battle between a group of the gods' champions and a mighty archon, which took place at the mysterious eastern edge of the world. Defeated, the falling archon is said to have met the rising sun. But Heliod showed mercy to the penitent archon, who swore to uphold justice and righteousness in the world's wildest places. As a sign of his mercy, Heliod gave the archon a spear that rivaled his own in its brilliance. This was the first archon of falling stars.

The mysterious conquerors known as archons once ruled vast empires. These armored warlords saw themselves as champions of merciless justice, and they ruled with iron fists. But their dominance ultimately came to an end. As the archon overlords toppled, they scattered to the fringes of the world, and their holdings developed into the poleis of today.

Even though the age of archons is long past, many wonder if the few surviving archons might someday attempt to reestablish their empire or if they are truly resigned to their lesser role in the world.

```statblock
"name": "Archon of Falling Stars (MOT)"
"size": "Medium"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "18"
"ac_class": "[plate](/2-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "144"
"hit_dice": "17d8 + 68"
"stats":
- !!int "20"
- !!int "15"
- !!int "19"
- !!int "15"
- !!int "21"
- !!int "19"
"speed": "30 ft."
"saves":
  "Charisma": !!int "8"
  "Wisdom": !!int "9"
  "Strength": !!int "9"
  "Constitution": !!int "8"
"skillsaves":
  "Insight": !!int "9"
  "Perception": !!int "9"
  "History": !!int "6"
  "Arcana": !!int "6"
"damage_immunities": "radiant"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "truesight 120 ft., passive Perception 19"
"languages": "all"
"cr": "12"
"traits":
- "desc": "The archon's spellcasting ability is Wisdom (spell save DC 17, +9 to\
    \ hit with spell attacks). The archon can innately cast the following spells,\
    \ requiring no material components:\n\nAt will: [command](/2-Mechanics/CLI/spells/command.md),\
    \ [guiding bolt](/2-Mechanics/CLI/spells/guiding-bolt.md), [spare the dying](/2-Mechanics/CLI/spells/spare-the-dying.md)\n\
    \n1/day each: [crusader's mantle](/2-Mechanics/CLI/spells/crusaders-mantle.md),\
    \ [spirit guardians](/2-Mechanics/CLI/spells/spirit-guardians.md)"
  "name": "Innate Spellcasting"
- "desc": "The archon has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "If the archon isn't mounted, it can use a bonus action to magically teleport\
    \ onto the creature serving as its mount, provided the archon and its mount are\
    \ on the same plane of existence. When it teleports, the archon appears astride\
    \ the mount, along with any equipment it is wearing or carrying. While mounted\
    \ and not [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated),\
    \ the archon can't be [surprised](/2-Mechanics/CLI/rules/conditions.md#surprised),\
    \ and both it and its mount have advantage on Dexterity saving throws. If the\
    \ archon is reduced to 0 hit points while riding its mount, the mount is reduced\
    \ to 0 hit points as well."
  "name": "Mount"
- "desc": "If the archon is reduced to 0 hit points, it regains 30 hit points and\
    \ springs back to its feet with a burst of radiance. Each creature of the archon's\
    \ choice within 30 feet of it must succeed on a DC 16 Constitution saving throw,\
    \ or the creature takes 13 (3d8) radiant damage and is [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded)\
    \ until the start of the archon's turn."
  "name": "Radiant Rebirth (Recharges after a Long Rest)"
"actions":
- "desc": "The archon makes two attacks with its radiant spear."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 12\
    \ (2d6 + 5) piercing damage plus 10 (3d6) radiant damage."
  "name": "Radiant Spear"
"legendary_actions":
- "desc": "The archon makes a radiant spear attack or casts [guiding bolt](/2-Mechanics/CLI/spells/guiding-bolt.md)."
  "name": "Attack"
- "desc": "The archon makes a radiant spear attack, and then its mount can use its\
    \ reaction to make a melee weapon attack."
  "name": "Coordinated Assault (Costs 2 Actions)"
- "desc": "The archon causes a corpse it can see within 30 feet of it to burst into\
    \ a shower of radiant stars leaving no trace of it behind. Everything it is wearing\
    \ or carrying remains. Each creature within 10 feet of the corpse when it bursts\
    \ must succeed on a DC 16 Dexterity saving throw or take 22 (4d10) radiant damage."
  "name": "Return to Nyx (Costs 3 Actions)"
"source":
- "MOT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MOT/Archon%20of%20Falling%20Stars.webp"
```
^statblock

```encounter-table
name: Archon of Falling Stars
creatures:
 - 1: Archon of Falling Stars
```