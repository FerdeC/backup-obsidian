---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Sekelok"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 120
---
# [Sekelok](2-Mechanics\CLI\bestiary\npc/sekelok-toa.md)
*Source: Tomb of Annihilation p. 120*  

```statblock
"name": "Sekelok (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "143"
"hit_dice": "22d8 + 44"
"stats":
- !!int "20"
- !!int "15"
- !!int "14"
- !!int "10"
- !!int "14"
- !!int "12"
"speed": "30 ft."
"saves":
  "Strength": !!int "9"
  "Constitution": !!int "6"
"skillsaves":
  "Intimidation": !!int "5"
  "Athletics": !!int "9"
  "Perception": !!int "6"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "any one language (usually Common), Abyssal, Draconic"
"cr": "9"
"traits":
- "desc": "Sekelok\n\nAt will: [animal friendship](/2-Mechanics/CLI/spells/animal-friendship.md)\
    \ (snakes only), [poison spray](/2-Mechanics/CLI/spells/poison-spray.md)\n\n3/day\
    \ each: [suggestion](/2-Mechanics/CLI/spells/suggestion.md)"
  "name": "Innate Spellcasting"
- "desc": "Sekelok rerolls a failed saving throw."
  "name": "Indomitable (2/Day)"
- "desc": "As a bonus action, Sekelok can regain 20 hit points."
  "name": "Second Wind (Recharges after a Short or Long Rest)"
- "desc": "Sekelok"
  "name": "Magic Resistance"
"actions":
- "desc": "Sekelok makes three attacks with its greatsword or its shortbow."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) slashing damage, plus 7 (2d6) slashing damage if Sekelok has more\
    \ than half of its total hit points remaining."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +6 to hit, range 80/320 ft., one target. Hit:\
    \ 5 (1d6 + 2) piercing damage, plus 7 (2d6) piercing damage if Sekelok has\
    \ more than half of its total hit points remaining."
  "name": "Shortbow"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Sekelok.webp"
```
^statblock

```encounter-table
name: Sekelok
creatures:
 - 1: Sekelok
```