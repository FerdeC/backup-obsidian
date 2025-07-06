---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/2
- monster/size/small
- monster/type/humanoid/derro
aliases: ["Narrak"]
NoteIcon: monster
BestiaryType: humanoid (derro)
SourceType: Bestiary
BookSource: Out of the Abyss p. 232
---
# [Narrak](2-Mechanics\CLI\bestiary\npc/narrak-oota.md)
*Source: Out of the Abyss p. 232*  

```statblock
"name": "Narrak (OotA)"
"size": "Small"
"type": "humanoid"
"subtype": "derro"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "40"
"hit_dice": "9d6 + 9"
"stats":
- !!int "9"
- !!int "14"
- !!int "13"
- !!int "14"
- !!int "5"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Arcana": !!int "4"
"senses": "darkvision 120 ft., passive Perception 7"
"languages": "Dwarvish, Undercommon"
"cr": "2"
"traits":
- "desc": "Narrak is a 5th-level spellcaster. His spellcasting ability is Charisma\
    \ (Save DC 13, +5 to hit with spell attacks) Narrak has two 2nd-level spell\
    \ slots, which he regains after finishing a short or long rest, and knows the\
    \ following warlock spells:\n\nCantrips (at will): [eldritch blast](/2-Mechanics/CLI/spells/eldritch-blast.md),\
    \ [friends](/2-Mechanics/CLI/spells/friends.md), [poison spray](/2-Mechanics/CLI/spells/poison-spray.md)\n\
    \n1st-2nd level (2 slots): [armor of Agathys](/2-Mechanics/CLI/spells/armor-of-agathys.md),\
    \ [charm person](/2-Mechanics/CLI/spells/charm-person.md), [hex](/2-Mechanics/CLI/spells/hex.md),\
    \ [hold person](/2-Mechanics/CLI/spells/hold-person.md), [ray of enfeeblement](/2-Mechanics/CLI/spells/ray-of-enfeeblement.md),\
    \ [spider climb](/2-Mechanics/CLI/spells/spider-climb.md)"
  "name": "Spellcasting"
- "desc": "Narrak has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Insanity"
- "desc": "Narrak has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "While in sunlight, Narrak has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Narrak casts [mage armor](/2-Mechanics/CLI/spells/mage-armor.md) on himself"
  "name": "Armor of Shadows (Recharges after a Short or Long Rest)"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword"
- "desc": "While he is in a dim light or darkness, Narrak can become [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible).\
    \ He remains so until he moves or takes an action or reaction."
  "name": "One with Shadows"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Narrak.webp"
```
^statblock

```encounter-table
name: Narrak
creatures:
 - 1: Narrak
```