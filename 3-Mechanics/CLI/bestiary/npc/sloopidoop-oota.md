---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/6
- monster/size/medium
- monster/type/humanoid/kuo-toa
aliases: ["Sloopidoop"]
NoteIcon: monster
BestiaryType: humanoid (kuo-toa)
SourceType: Bestiary
BookSource: Out of the Abyss p. 29
---
# [Sloopidoop](2-Mechanics\CLI\bestiary\npc/sloopidoop-oota.md)
*Source: Out of the Abyss p. 29*  

```statblock
"name": "Sloopidoop (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "kuo-toa"
"alignment": "Neutral"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "97"
"hit_dice": "13d8 + 39"
"stats":
- !!int "16"
- !!int "14"
- !!int "16"
- !!int "18"
- !!int "16"
- !!int "14"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Religion": !!int "7"
  "Perception": !!int "9"
"senses": "darkvision 120 ft., passive Perception 19"
"languages": "Undercommon, Dwarvish, Elvish"
"cr": "6"
"traits":
- "desc": "Sloopidoop is a 10th-level spellcaster. Its spellcasting ability is Wisdom\
    \ (spell save DC 14, +6 to hit with spell attacks). Sloopidoop has the following\
    \ cleric spells prepared:\n\nCantrips (at will): [guidance](/2-Mechanics/CLI/spells/guidance.md),\
    \ [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1st level (4 slots): [detect magic](/2-Mechanics/CLI/spells/detect-magic.md),\
    \ [sanctuary](/2-Mechanics/CLI/spells/sanctuary.md), [shield of faith](/2-Mechanics/CLI/spells/shield-of-faith.md)\n\
    \n2nd level (3 slots): [hold person](/2-Mechanics/CLI/spells/hold-person.md),\
    \ [spiritual weapon](/2-Mechanics/CLI/spells/spiritual-weapon.md)\n\n3rd level\
    \ (3 slots): [spirit guardians](/2-Mechanics/CLI/spells/spirit-guardians.md),\
    \ [tongues](/2-Mechanics/CLI/spells/tongues.md)\n\n4th level (3 slots): [control\
    \ water](/2-Mechanics/CLI/spells/control-water.md), [divination](/2-Mechanics/CLI/spells/divination.md)\n\
    \n5th level (2 slots): [mass cure wounds](/2-Mechanics/CLI/spells/mass-cure-wounds.md),\
    \ [scrying](/2-Mechanics/CLI/spells/scrying.md)"
  "name": "Spellcasting"
- "desc": "Sloopidoop can innately cast can cast the [teleport](/2-Mechanics/CLI/spells/teleport.md)\
    \ spell once per day, but the intended destination must be within 30 feet of another\
    \ society member. This teleport effect can be disrupted (see \"Faerzress\"), which\
    \ is how society members sometimes end up in far corners of the Underdark, separated\
    \ from their fellows.\n\n1/day each: [teleport](/2-Mechanics/CLI/spells/teleport.md)"
  "name": "Innate Spellcasting"
- "desc": "Sloopidoop can breathe air and water."
  "name": "Amphibious"
- "desc": "Sloopidoop can sense the presence of any creature within 30 feet of it\
    \ that is [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible) or on the\
    \ Ethereal Plane. It can pinpoint such a creature that is moving."
  "name": "Otherworldly Perception"
- "desc": "Sloopidoop has advantage on ability checks and saving throws made to escape\
    \ a grapple."
  "name": "Slippery"
- "desc": "While in sunlight, Sloopidoop has disadvantage on attack rolls, as well\
    \ as on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Sloopidoop makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) bludgeoning damage plus 14 (4d6) lightning damage."
  "name": "Scepter"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 5 (1d4\
    \ + 3) bludgeoning damage."
  "name": "Unarmed Strike"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Sloopidoop.webp"
```
^statblock

```encounter-table
name: Sloopidoop
creatures:
 - 1: Sloopidoop
```