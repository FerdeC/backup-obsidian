---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Fel'rekt Lafeen"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 67
---
# [Fel'rekt Lafeen](2-Mechanics\CLI\bestiary\npc/felrekt-lafeen-wdh.md)
*Source: Waterdeep: Dragon Heist p. 67*  

```statblock
"name": "Fel'rekt Lafeen (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Good"
"ac": !!int "18"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "84"
"hit_dice": "13d8 + 26"
"stats":
- !!int "13"
- !!int "18"
- !!int "14"
- !!int "11"
- !!int "13"
- !!int "14"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "6"
  "Wisdom": !!int "3"
  "Constitution": !!int "4"
"skillsaves":
  "Stealth": !!int "8"
  "Perception": !!int "3"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Elvish, Undercommon"
"cr": "4"
"traits":
- "desc": "Fel'rekt's spellcasting ability is Charisma (spell save DC 12) It can innately\
    \ cast the following spells, requiring no material components:\n\nAt will:\
    \ [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\n1/day each:\
    \ [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md) (self only)"
  "name": "Innate Spellcasting"
- "desc": "Fel'rekt has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put Fel'rekt to sleep."
  "name": "Fey Ancestry"
- "desc": "Being within 5 feet of a hostile creature or attacking at long range doesn't\
    \ impose disadvantage on Fel'rekt's ranged attack rolls with a pistol. In addition,\
    \ Fel'rekt ignores half cover and three-quarters cover when making ranged attacks\
    \ with a pistol."
  "name": "Gunslinger"
- "desc": "While in sunlight, Fel'rekt has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Fel'rekt makes two shortsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +6 to hit, range 30/90 ft., one target. Hit:\
    \ 9 (1d10 + 4) piercing damage plus 11 (2d10) poison damage."
  "name": "Poisonous Pistol"
"source":
- "WDH"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDH/Fel%27rekt%20Lafeen.webp"
```
^statblock

```encounter-table
name: Fel'rekt Lafeen
creatures:
 - 1: Fel'rekt Lafeen
```