---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/8
- monster/size/medium
- monster/type/undead
aliases: ["Yalaga Maladwyn"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 226
---
# [Yalaga Maladwyn](2-Mechanics\CLI\bestiary\npc/yalaga-maladwyn-gos.md)
*Source: Ghosts of Saltmarsh p. 226*  

```statblock
"name": "Yalaga Maladwyn (GoS)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "[scale mail](/2-Mechanics/CLI/items/scale-mail.md)"
"hp": !!int "71"
"hit_dice": "13d8 + 13"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "13"
- !!int "17"
- !!int "18"
"speed": "30 ft."
"saves":
  "Charisma": !!int "7"
  "Wisdom": !!int "6"
  "Constitution": !!int "4"
"skillsaves":
  "Stealth": !!int "5"
  "Religion": !!int "4"
  "Insight": !!int "6"
  "Perception": !!int "6"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Elvish, Undercommon"
"cr": "8"
"traits":
- "desc": "Yalaga's spellcasting ability is Charisma (spell save DC 15). She can innately\
    \ cast the following spells, requiring no material components:\n\nAt will:\
    \ [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\n1/day each:\
    \ [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md) (self only)"
  "name": "Innate Spellcasting"
- "desc": "Yalaga is a 10th-level spellcaster. Her spellcasting ability is Wisdom\
    \ (save DC 14, +6 to hit with spell attacks). Yalaga has the following cleric\
    \ spells prepared:\n\nCantrips (at will): [guidance](/2-Mechanics/CLI/spells/guidance.md),\
    \ [poison spray](/2-Mechanics/CLI/spells/poison-spray.md), [resistance](/2-Mechanics/CLI/spells/resistance.md),\
    \ [spare the dying](/2-Mechanics/CLI/spells/spare-the-dying.md), [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1st level (4 slots): [animal friendship](/2-Mechanics/CLI/spells/animal-friendship.md),\
    \ [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md), [detect poison and disease](/2-Mechanics/CLI/spells/detect-poison-and-disease.md),\
    \ [ray of sickness](/2-Mechanics/CLI/spells/ray-of-sickness.md)\n\n2nd level\
    \ (3 slots): [lesser restoration](/2-Mechanics/CLI/spells/lesser-restoration.md),\
    \ [protection from poison](/2-Mechanics/CLI/spells/protection-from-poison.md),\
    \ [web](/2-Mechanics/CLI/spells/web.md)\n\n3rd level (3 slots): [conjure animals](/2-Mechanics/CLI/spells/conjure-animals.md)\
    \ (2 [giant spiders](/2-Mechanics/CLI/bestiary/beast/giant-spider.md)), [dispel\
    \ magic](/2-Mechanics/CLI/spells/dispel-magic.md)\n\n4th level (3 slots):\
    \ [divination](/2-Mechanics/CLI/spells/divination.md), [freedom of movement](/2-Mechanics/CLI/spells/freedom-of-movement.md)\n\
    \n5th level (2 slots): [insect plague](/2-Mechanics/CLI/spells/insect-plague.md),\
    \ [mass cure wounds](/2-Mechanics/CLI/spells/mass-cure-wounds.md)"
  "name": "Spellcasting"
- "desc": "While in sunlight, Yalaga has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Yalaga makes two scourge attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage plus 17 (5d6) poison damage."
  "name": "Scourge"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Yalaga%20Maladwyn.webp"
```
^statblock

```encounter-table
name: Yalaga Maladwyn
creatures:
 - 1: Yalaga Maladwyn
```