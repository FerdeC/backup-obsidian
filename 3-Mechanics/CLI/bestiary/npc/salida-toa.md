---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/yuan-ti
aliases: ["Salida"]
NoteIcon: monster
BestiaryType: humanoid (yuan-ti)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 35
---
# [Salida](2-Mechanics\CLI\bestiary\npc/salida-toa.md)
*Source: Tomb of Annihilation p. 35*  

```statblock
"name": "Salida (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "yuan-ti"
"alignment": "Neutral Evil"
"ac": !!int "11"
"hp": !!int "40"
"hit_dice": "9d8"
"stats":
- !!int "11"
- !!int "12"
- !!int "11"
- !!int "13"
- !!int "12"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "6"
  "Stealth": !!int "3"
  "Perception": !!int "3"
  "Survival": !!int "5"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Abyssal, Common, Draconic"
"cr": "1"
"traits":
- "desc": "Salida's spellcasting ability is Charisma (spell save DC 12). Salida can\
    \ innately cast the following spells, requiring no material components:\n\nAt\
    \ will: [animal friendship](/2-Mechanics/CLI/spells/animal-friendship.md) (snakes\
    \ only)\n\n3/day each: [poison spray](/2-Mechanics/CLI/spells/poison-spray.md),\
    \ [suggestion](/2-Mechanics/CLI/spells/suggestion.md)"
  "name": "Innate Spellcasting"
- "desc": "Salida has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Salida makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) slashing damage."
  "name": "Scimitar"
- "desc": "Ranged Weapon Attack: +3 to hit, range 80/320 ft., one target. Hit:\
    \ 4 (1d6 + 1) piercing damage plus 7 (2d6) poison damage."
  "name": "Shortbow"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Salida.webp"
```
^statblock

```encounter-table
name: Salida
creatures:
 - 1: Salida
```