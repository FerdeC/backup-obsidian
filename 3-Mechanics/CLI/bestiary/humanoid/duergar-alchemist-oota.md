---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/dwarf
aliases: ["Duergar Alchemist"]
NoteIcon: monster
BestiaryType: humanoid (dwarf)
SourceType: Bestiary
BookSource: Out of the Abyss p. 76
---
# [Duergar Alchemist](2-Mechanics\CLI\bestiary\humanoid/duergar-alchemist-oota.md)
*Source: Out of the Abyss p. 76*  

```statblock
"name": "Duergar Alchemist (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "[scale mail](/2-Mechanics/CLI/items/scale-mail.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "26"
"hit_dice": "4d8 + 4"
"stats":
- !!int "14"
- !!int "11"
- !!int "14"
- !!int "11"
- !!int "10"
- !!int "9"
"speed": "25 ft."
"damage_resistances": "poison"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "Dwarvish, Undercommon"
"cr": "1"
"traits":
- "desc": "The duergar has advantage on saving throws against poison, spells, and\
    \ illusions, as well as to resist being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed)."
  "name": "Duergar Resilience"
- "desc": "While in sunlight, the duergar has disadvantage on attack rolls, as well\
    \ as on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "For 1 minute, the duergar magically increases in size, along with anything\
    \ it is wearing or carrying. While enlarged, the duergar is Large, doubles its\
    \ damage dice on Strength-based weapon attacks (included in the attacks), and\
    \ makes Strength checks and Strength saving throws with advantage. If the duergar\
    \ lacks the room to become Large, it attains the maximum size possible in the\
    \ space available."
  "name": "Enlarge (Recharges after a Short or Long Rest)"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) piercing damage, or 11 (2d8 + 2) piercing damage while enlarged."
  "name": "War Pick"
- "desc": "Ranged Weapon Attack: +4 to hit, range 20 ft., one target. Hit: 7\
    \ (2d6) acid damage."
  "name": "Acid Vial"
- "desc": "Ranged Weapon Attack: +4 to hit, range 20 ft., one target. Hit: 2\
    \ (1d4) fire damage at the start of each of the target's turns. A creature can\
    \ end this damage by using its action to make a successful DC 10 Dexterity check\
    \ to extinguish the flames."
  "name": "Alchemist's Fire"
- "desc": "The duergar magically turns [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ until it attacks, casts a spell, or uses its Enlarge, or until its [concentration](/2-Mechanics/CLI/rules/conditions.md#concentration)\
    \ is broken, up to 1 hour (as if concentrating on a spell). Any equipment the\
    \ duergar wears or carries is [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ with it."
  "name": "Invisibility (Recharges after a Short or Long Rest)"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Duergar%20Alchemist.webp"
```
^statblock

```encounter-table
name: Duergar Alchemist
creatures:
 - 1: Duergar Alchemist
```