---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Drow Commander"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 209
---
# [Drow Commander](2-Mechanics\CLI\bestiary\humanoid/drow-commander-tftyp.md)
*Source: Tales from the Yawning Portal p. 209*  

```statblock
"name": "Drow Commander (TftYP)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "110"
"hit_dice": "11d8 + 22"
"stats":
- !!int "13"
- !!int "18"
- !!int "14"
- !!int "11"
- !!int "13"
- !!int "12"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "7"
  "Wisdom": !!int "4"
  "Constitution": !!int "5"
"skillsaves":
  "Stealth": !!int "10"
  "Perception": !!int "4"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "Elvish, Undercommon"
"cr": "5"
"traits":
- "desc": "The drow's spellcasting ability is Charisma (spell save DC 12). It can\
    \ innately cast the following spells, requiring no material components:\n\nAt\
    \ will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\n1/day\
    \ each: [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md) (self only)"
  "name": "Innate Spellcasting"
- "desc": "The drow carries three magical bolts, as follows:\n\n- A bolt of holding,\
    \ which casts [hold person](/2-Mechanics/CLI/spells/hold-person.md) on a target\
    \ hit with the bolt, as well as up to two other targets within 30 feet of that\
    \ target  \n- A bolt of blinding, which casts [blindness/deafness](/2-Mechanics/CLI/spells/blindness-deafness.md)\
    \ to blind on a target hit with the bolt, as well as up to two other targets within\
    \ 30 feet of that target  \n- A bolt of vapors, which casts [stinking cloud](/2-Mechanics/CLI/spells/stinking-cloud.md)\
    \ centered on the point it hits  \n\nEach of these effects has a spell save DC\
    \ of 15 and a duration of 1 minute."
  "name": "Special Equipment"
- "desc": "The drow has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put the drow to sleep."
  "name": "Fey Ancestry"
- "desc": "While in sunlight, the drow has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "The drow makes two shortsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 9 (1d6\
    \ + 6) piercing damage plus 10 (3d6) poison damage."
  "name": "Shortsword +2"
- "desc": "Ranged Weapon Attack: +8 to hit, range 30/120 ft., one target. Hit:\
    \ 8 (1d6 + 5) piercing damage, and the target must succeed on a DC 13 Constitution\
    \ saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 hour. If the saving throw fails by 5 or more, the target is also [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)\
    \ while [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) in this way.\
    \ The target wakes up if it takes damage or if another creature takes an action\
    \ to shake it awake."
  "name": "Hand Crossbow +1"
"reactions":
- "desc": "The drow adds 3 to its AC against one melee attack that would hit it. To\
    \ do so, the drow must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Drow%20Commander.webp"
```
^statblock

```encounter-table
name: Drow Commander
creatures:
 - 1: Drow Commander
```