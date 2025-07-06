---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/7
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Zilchyn Q'Leptin"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: Out of the Abyss p. 137
---
# [Zilchyn Q'Leptin](2-Mechanics\CLI\bestiary\npc/zilchyn-qleptin-oota.md)
*Source: Out of the Abyss p. 137*  

```statblock
"name": "Zilchyn Q'Leptin (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "45"
"hit_dice": "10d8"
"stats":
- !!int "9"
- !!int "14"
- !!int "10"
- !!int "17"
- !!int "13"
- !!int "12"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "4"
  "Stealth": !!int "5"
  "Perception": !!int "4"
  "Arcana": !!int "6"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "Elvish, Undercommon"
"cr": "7"
"traits":
- "desc": "Zilchyn's spellcasting ability is Charisma (spell save DC 12). It can innately\
    \ cast the following spells, requiring no material components:\n\nAt will:\
    \ [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\n1/day each:\
    \ [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md) (self only)"
  "name": "Innate Spellcasting"
- "desc": "Zilchyn is a 10th-level spellcaster. Its spellcasting ability is Intelligence\
    \ (spell save DC 14, +6 to hit with spell attacks). Zilchyn has the following\
    \ wizard spells prepared:\n\nCantrips (at will): [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md), [poison spray](/2-Mechanics/CLI/spells/poison-spray.md),\
    \ [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md)\n\n1st level (4 slots):\
    \ [mage armor](/2-Mechanics/CLI/spells/mage-armor.md), [magic missile](/2-Mechanics/CLI/spells/magic-missile.md),\
    \ [shield](/2-Mechanics/CLI/spells/shield.md), [witch bolt](/2-Mechanics/CLI/spells/witch-bolt.md)\n\
    \n2nd level (3 slots): [alter self](/2-Mechanics/CLI/spells/alter-self.md),\
    \ [misty step](/2-Mechanics/CLI/spells/misty-step.md), [web](/2-Mechanics/CLI/spells/web.md)\n\
    \n3rd level (3 slots): [fly](/2-Mechanics/CLI/spells/fly.md), [lightning bolt](/2-Mechanics/CLI/spells/lightning-bolt.md)\n\
    \n4th level (3 slots): [Evard's black tentacles](/2-Mechanics/CLI/spells/evards-black-tentacles.md),\
    \ [greater invisibility](/2-Mechanics/CLI/spells/greater-invisibility.md)\n\n\
    5th level (2 slots): [cloudkill](/2-Mechanics/CLI/spells/cloudkill.md)"
  "name": "Spellcasting"
- "desc": "Zilchyn has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put Zilchyn to sleep."
  "name": "Fey Ancestry"
- "desc": "While in sunlight, Zilchyn has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d6\
    \ - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two\
    \ hands, plus 3 (1d6) poison damage."
  "name": "Staff"
- "desc": "Zilchyn magically summons a [quasit](/2-Mechanics/CLI/bestiary/fiend/quasit.md),\
    \ or attempts to summon a [shadow demon](/2-Mechanics/CLI/bestiary/fiend/shadow-demon.md)\
    \ with a 50% chance chance of success. The summoned demon appears in an unoccupied\
    \ space within 60 feet of its summoner, acts as an ally of its summoner, and can't\
    \ summon other demons. It remains for 10 minutes, until it or its summoner dies,\
    \ or until its summoner dismisses it as an action."
  "name": "Summon Demon (1/Day)"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Zilchyn%20Q%27Leptin.webp"
```
^statblock

```encounter-table
name: Zilchyn Q'Leptin
creatures:
 - 1: Zilchyn Q'Leptin
```