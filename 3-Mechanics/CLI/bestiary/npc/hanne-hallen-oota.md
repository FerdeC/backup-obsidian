---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1-4
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Hanne Hallen"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: Out of the Abyss p. 171
---
# [Hanne Hallen](2-Mechanics\CLI\bestiary\npc/hanne-hallen-oota.md)
*Source: Out of the Abyss p. 171*  

```statblock
"name": "Hanne Hallen (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "13"
"hit_dice": "3d8"
"stats":
- !!int "10"
- !!int "14"
- !!int "10"
- !!int "17"
- !!int "11"
- !!int "12"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Investigation": !!int "5"
  "Perception": !!int "2"
  "Arcana": !!int "5"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "Elvish, Undercommon, Common"
"cr": "1/4"
"traits":
- "desc": "Hanne's spellcasting ability is Charisma (spell save DC 11). It can innately\
    \ cast the following spells, requiring no material components:\n\nAt will:\
    \ [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\n1/day each:\
    \ [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md)"
  "name": "Innate Spellcasting"
- "desc": "Hanne is a 1st-level spellcaster. Her spellcasting ability is Intelligence\
    \ (spell save DC 13, +5 to hit with spell attacks). She has the following wizard\
    \ spells prepared:\n\nCantrips (at will): [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md),\
    \ [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md)\n\n1st level (4 slots):\
    \ [shield](/2-Mechanics/CLI/spells/shield.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
  "name": "Spellcasting"
- "desc": "Hanne has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put Hanne to sleep."
  "name": "Fey Ancestry"
- "desc": "While in sunlight, Hanne has disadvantage on attack rolls, as well as on\
    \ Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks that\
    \ rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit:\
    \ 5 (1d6 + 2) piercing damage, and the target must succeed on a DC 13 Constitution\
    \ saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 hour. If the saving throw fails by 5 or more, the target is also [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)\
    \ while [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) in this way.\
    \ The target wakes up if it takes damage or if another creature takes an action\
    \ to shake it awake."
  "name": "Hand Crossbow"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Hanne%20Hallen.webp"
```
^statblock

```encounter-table
name: Hanne Hallen
creatures:
 - 1: Hanne Hallen
```