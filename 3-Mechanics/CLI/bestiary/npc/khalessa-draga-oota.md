---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Khalessa Draga"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Out of the Abyss p. 149
---
# [Khalessa Draga](2-Mechanics\CLI\bestiary\npc/khalessa-draga-oota.md)
*Source: Out of the Abyss p. 149*  

```statblock
"name": "Khalessa Draga (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral"
"ac": !!int "12"
"hp": !!int "27"
"hit_dice": "6d8"
"stats":
- !!int "10"
- !!int "15"
- !!int "10"
- !!int "12"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Sleight of Hand": !!int "4"
  "Deception": !!int "5"
  "Stealth": !!int "4"
  "Investigation": !!int "5"
  "Insight": !!int "4"
  "Perception": !!int "6"
  "Persuasion": !!int "5"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "any two languages, Undercommon, Elvish"
"cr": "1"
"traits":
- "desc": "Khalessa can innately cast the following spell, requiring no material components:\n\
    \nAt will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)"
  "name": "Innate Spellcasting"
- "desc": "Khalessa owns a [hat of disguise](/2-Mechanics/CLI/items/hat-of-disguise.md),\
    \ which she uses to appear as a female drow while in the company of drow."
  "name": "Special Equipment"
- "desc": "On each of its turns, Khalessa can use a bonus action to take the Dash,\
    \ Disengage, or Hide action."
  "name": "Cunning Action"
- "desc": "Khalessa deals an extra 7 (2d6) damage when it hits a target with a weapon\
    \ attack and has advantage on the attack roll, or when the target is within 5\
    \ feet of an ally of Khalessa that isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ and Khalessa doesn't have disadvantage on the attack roll."
  "name": "Sneak Attack (1/Turn)"
- "desc": "Khalessa"
  "name": "Fey Ancestry"
"actions":
- "desc": "Khalessa makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit:\
    \ 5 (1d6 + 2) piercing damage."
  "name": "Hand Crossbow"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Khalessa%20Draga.webp"
```
^statblock

```encounter-table
name: Khalessa Draga
creatures:
 - 1: Khalessa Draga
```