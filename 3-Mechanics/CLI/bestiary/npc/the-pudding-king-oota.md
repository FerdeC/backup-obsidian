---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/4
- monster/size/small
- monster/type/humanoid/gnome
- monster/type/humanoid/shapechanger
aliases: ["The Pudding King"]
NoteIcon: monster
BestiaryType: humanoid (gnome, shapechanger)
SourceType: Bestiary
BookSource: Out of the Abyss p. 233
---
# [The Pudding King](2-Mechanics\CLI\bestiary\npc/the-pudding-king-oota.md)
*Source: Out of the Abyss p. 233*  

```statblock
"name": "The Pudding King (OotA)"
"size": "Small"
"type": "humanoid"
"subtype": "gnome, shapechanger"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"ac_class": "16 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "49"
"hit_dice": "9d6 + 18"
"stats":
- !!int "10"
- !!int "16"
- !!int "14"
- !!int "12"
- !!int "8"
- !!int "17"
"speed": "30 ft."
"saves":
  "Charisma": !!int "7"
  "Constitution": !!int "6"
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "2"
  "Arcana": !!int "4"
  "Survival": !!int "2"
"damage_resistances": "acid, poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Abyssal, Gnomish, Terran, Undercommon"
"cr": "4"
"traits":
- "desc": "The Pudding King's innate spellcasting ability is Intelligence (spell save\
    \ DC 12). He can innately cast the following spells, requiring no material components:\n\
    \nAt will: [nondetection](/2-Mechanics/CLI/spells/nondetection.md) (self only)\n\
    \n1/day each: [blindness/deafness](/2-Mechanics/CLI/spells/blindness-deafness.md),\
    \ [blur](/2-Mechanics/CLI/spells/blur.md), [disguise self](/2-Mechanics/CLI/spells/disguise-self.md)"
  "name": "Innate Spellcasting"
- "desc": "The Pudding King is a 9th-level spellcaster. His spellcasting ability is\
    \ Charisma (spell save DC 14, +6 to hit with spell attacks). The Pudding King\
    \ knows the following sorcerer spells:\n\nCantrips (at will): [acid splash](/2-Mechanics/CLI/spells/acid-splash.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [poison spray](/2-Mechanics/CLI/spells/poison-spray.md), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\
    \n1st level (4 slots): [false life](/2-Mechanics/CLI/spells/false-life.md),\
    \ [mage armor](/2-Mechanics/CLI/spells/mage-armor.md), [ray of sickness](/2-Mechanics/CLI/spells/ray-of-sickness.md),\
    \ [shield](/2-Mechanics/CLI/spells/shield.md)\n\n2nd level (3 slots): [crown\
    \ of madness](/2-Mechanics/CLI/spells/crown-of-madness.md), [misty step](/2-Mechanics/CLI/spells/misty-step.md)\n\
    \n3rd level (3 slots): [gaseous form](/2-Mechanics/CLI/spells/gaseous-form.md),\
    \ [stinking cloud](/2-Mechanics/CLI/spells/stinking-cloud.md)\n\n4th level (3\
    \ slots): [blight](/2-Mechanics/CLI/spells/blight.md), [confusion](/2-Mechanics/CLI/spells/confusion.md)\n\
    \n5th level (1 slots): [cloudkill](/2-Mechanics/CLI/spells/cloudkill.md)"
  "name": "Spellcasting"
- "desc": "The Pudding King has advantage on Dexterity ([Stealth](/2-Mechanics/CLI/rules/skills.md#Stealth))\
    \ checks made to hide in rocky terrain."
  "name": "Stone Camouflage"
- "desc": "The Pudding King has advantage on Intelligence, Wisdom, and Charisma saving\
    \ throws against magic."
  "name": "Gnome Cunning"
- "desc": "The Pudding King has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Insanity"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d8)\
    \ piercing damage."
  "name": "War Pick"
- "desc": "The Pudding King magically transforms into an ooze, or back into his true\
    \ form. He reverts to his true form if he dies. Any equipment he is wearing or\
    \ carrying is absorbed by the new form. In ooze form, the Pudding King retains\
    \ his alignment, hit points, Hit Dice, and Intelligence, Wisdom, and Charisma\
    \ scores, as well as this action. His statistics and capabilities are otherwise\
    \ replaced by those of the new form."
  "name": "Change Shape"
- "desc": "The Pudding King creates a patch of green slime (see \"Dungeon Hazards\"\
    \ in chapter 5 of the Dungeon Master's Guide). The slime appears on a section\
    \ of wall, ceiling, or floor within 30 feet of the Pudding King."
  "name": "Create Green Slime (Recharges after a Long Rest)"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/The%20Pudding%20King.webp"
```
^statblock

```encounter-table
name: The Pudding King
creatures:
 - 1: The Pudding King
```