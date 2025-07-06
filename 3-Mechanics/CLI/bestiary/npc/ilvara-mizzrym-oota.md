---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/8
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Ilvara Mizzrym"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: Out of the Abyss p. 9
---
# [Ilvara Mizzrym](2-Mechanics\CLI\bestiary\npc/ilvara-mizzrym-oota.md)
*Source: Out of the Abyss p. 9*  

```statblock
"name": "Ilvara Mizzrym (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
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
- "desc": "Ilvara's spellcasting ability is Charisma (spell save DC 15). She can innately\
    \ cast the following spells, requiring no material components:\n\nAt will:\
    \ [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\n1/day each:\
    \ [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md) (self only)"
  "name": "Innate Spellcasting"
- "desc": "Ilvara is a 10th-level spellcaster. Her spellcasting ability is Wisdom\
    \ (save DC 14, +6 to hit with spell attacks). Ilvara has the following cleric\
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
- "desc": "Ilvara wields a [tentacle rod](/2-Mechanics/CLI/items/tentacle-rod.md)\
    \ in addition to her scourge."
  "name": "Special Equipment"
- "desc": "Ilvara has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put Ilvara to sleep."
  "name": "Fey Ancestry"
- "desc": "While in sunlight, Ilvara has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Ilvara makes two scourge attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage plus 17 (5d6) poison damage."
  "name": "Scourge"
- "desc": "Ilvara attempts to magically summon a [yochlol](/2-Mechanics/CLI/bestiary/fiend/yochlol.md)\
    \ with a 30% chance chance of success. If the attempt fails, Ilvara takes 5 (1d10)\
    \ psychic damage. Otherwise, the summoned demon appears in an unoccupied space\
    \ within 60 feet of its summoner, acts as an ally of its summoner, and can't summon\
    \ other demons. It remains for 10 minutes, until it or its summoner dies, or until\
    \ its summoner dismisses it as an action."
  "name": "Summon Demon (1/Day)"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Ilvara%20Mizzrym.webp"
```
^statblock

```encounter-table
name: Ilvara Mizzrym
creatures:
 - 1: Ilvara Mizzrym
```