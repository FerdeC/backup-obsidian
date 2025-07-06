---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/22
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Quenthel Baenre"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: Out of the Abyss p. 204
---
# [Quenthel Baenre](2-Mechanics\CLI\bestiary\npc/quenthel-baenre-oota.md)
*Source: Out of the Abyss p. 204*  

```statblock
"name": "Quenthel Baenre (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Evil"
"ac": !!int "19"
"ac_class": "[+3 scale mail](/2-Mechanics/CLI/items/3-armor.md)"
"hp": !!int "132"
"hit_dice": "24d8 + 24"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "18"
- !!int "20"
- !!int "18"
"speed": "30 ft."
"saves":
  "Charisma": !!int "11"
  "Wisdom": !!int "12"
  "Constitution": !!int "8"
"skillsaves":
  "Stealth": !!int "9"
  "Religion": !!int "11"
  "Insight": !!int "12"
  "Perception": !!int "12"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Elvish, Undercommon"
"cr": "22"
"traits":
- "desc": "Quenthel's spellcasting ability is Charisma (spell save DC 19). She can\
    \ innately cast the following spells, requiring no material components:\n\nAt\
    \ will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\n1/day\
    \ each: [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md) (self only)"
  "name": "Innate Spellcasting"
- "desc": "Quenthel is a 20th-level spellcaster. Her spellcasting ability is Wisdom\
    \ (save DC 20, +12 to hit with spell attacks). Quenthel has the following cleric\
    \ spells prepared:\n\nAt will: Any cleric spell up to 9th level.\n\nCantrips\
    \ (at will): [guidance](/2-Mechanics/CLI/spells/guidance.md), [poison spray](/2-Mechanics/CLI/spells/poison-spray.md),\
    \ [resistance](/2-Mechanics/CLI/spells/resistance.md), [spare the dying](/2-Mechanics/CLI/spells/spare-the-dying.md),\
    \ [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\n1st level (4 slots):\
    \ [animal friendship](/2-Mechanics/CLI/spells/animal-friendship.md), [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md),\
    \ [detect poison and disease](/2-Mechanics/CLI/spells/detect-poison-and-disease.md),\
    \ [ray of sickness](/2-Mechanics/CLI/spells/ray-of-sickness.md)\n\n2nd level\
    \ (3 slots): [lesser restoration](/2-Mechanics/CLI/spells/lesser-restoration.md),\
    \ [protection from poison](/2-Mechanics/CLI/spells/protection-from-poison.md),\
    \ [web](/2-Mechanics/CLI/spells/web.md)\n\n3rd level (3 slots): [conjure animals](/2-Mechanics/CLI/spells/conjure-animals.md)\
    \ (2 giant spiders), [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md)\n\
    \n4th level (3 slots): [divination](/2-Mechanics/CLI/spells/divination.md),\
    \ [freedom of movement](/2-Mechanics/CLI/spells/freedom-of-movement.md)\n\n5th\
    \ level (2 slots): [insect plague](/2-Mechanics/CLI/spells/insect-plague.md),\
    \ [mass cure wounds](/2-Mechanics/CLI/spells/mass-cure-wounds.md)"
  "name": "Spellcasting"
- "desc": "Quenthel has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put Quenthel to sleep."
  "name": "Fey Ancestry"
- "desc": "While in sunlight, Quenthel has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
- "desc": "Quenthel wields a [tentacle rod](/2-Mechanics/CLI/items/tentacle-rod.md)."
  "name": "Special Equipment"
"actions":
- "desc": "Quenthel makes two scourge attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage plus 17 (5d6) poison damage."
  "name": "Scourge"
- "desc": "Quenthel attempts to magically summon a [yochlol](/2-Mechanics/CLI/bestiary/fiend/yochlol.md)\
    \ with a 30% chance chance of success. If the attempt fails, Quenthel takes 5\
    \ (1d10) psychic damage. Otherwise, the summoned demon appears in an unoccupied\
    \ space within 60 feet of its summoner, acts as an ally of its summoner, and can't\
    \ summon other demons. It remains for 10 minutes, until it or its summoner dies,\
    \ or until its summoner dismisses it as an action."
  "name": "Summon Demon (1/Day)"
- "desc": "While seated on her throne, Quenthel can use an action on her turn to cast\
    \ [disintegrate](/2-Mechanics/CLI/spells/disintegrate.md) (save DC 19). A target\
    \ that fails its saving throw takes 10d6 + 40 force damage. If this damage reduces\
    \ the target to 0 hit points, it is disintegrated."
  "name": "Throne Activation"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Quenthel%20Baenre.webp"
```
^statblock

```encounter-table
name: Quenthel Baenre
creatures:
 - 1: Quenthel Baenre
```