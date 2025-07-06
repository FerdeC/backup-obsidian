---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/7
- monster/size/medium
- monster/type/aberration
aliases: ["Grazilaxx"]
NoteIcon: monster
BestiaryType: aberration
SourceType: Bestiary
BookSource: Out of the Abyss p. 29
---
# [Grazilaxx](2-Mechanics\CLI\bestiary\npc/grazilaxx-oota.md)
*Source: Out of the Abyss p. 29*  

```statblock
"name": "Grazilaxx (OotA)"
"size": "Medium"
"type": "aberration"
"alignment": "Neutral"
"ac": !!int "15"
"ac_class": "[breastplate](/2-Mechanics/CLI/items/breastplate.md)"
"hp": !!int "71"
"hit_dice": "13d8 + 13"
"stats":
- !!int "11"
- !!int "12"
- !!int "12"
- !!int "18"
- !!int "17"
- !!int "17"
"speed": "30 ft."
"saves":
  "Charisma": !!int "6"
  "Wisdom": !!int "6"
  "Intelligence": !!int "7"
"skillsaves":
  "Deception": !!int "6"
  "Stealth": !!int "4"
  "Insight": !!int "6"
  "Perception": !!int "6"
  "Arcana": !!int "7"
  "Persuasion": !!int "6"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Deep Speech, Undercommon, telepathy 120 ft., Dwarvish, Elvish"
"cr": "7"
"traits":
- "desc": "Grazilaxx's innate spellcasting ability is Intelligence (spell save DC\
    \ 15). It can innately cast the following spells, requiring no components:\n\n\
    At will: [detect thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md), [levitate](/2-Mechanics/CLI/spells/levitate.md)\n\
    \n1/day each: [dominate monster](/2-Mechanics/CLI/spells/dominate-monster.md),\
    \ [plane shift](/2-Mechanics/CLI/spells/plane-shift.md) (self only)"
  "name": "Innate Spellcasting (Psionics)"
- "desc": "Grazilaxx can innately cast can cast the [teleport](/2-Mechanics/CLI/spells/teleport.md)\
    \ spell once per day, but the intended destination must be within 30 feet of another\
    \ society member. This teleport effect can be disrupted (see \"Faerzress\"), which\
    \ is how society members sometimes end up in far corners of the Underdark, separated\
    \ from their fellows.\n\n1/day each: [teleport](/2-Mechanics/CLI/spells/teleport.md)"
  "name": "Innate Spellcasting"
- "desc": "Grazilaxx has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. Hit: 15\
    \ (2d10 + 4) psychic damage. If the target is Medium or smaller, it is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 15) and must succeed on a DC 15 Intelligence saving throw or be [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)\
    \ until this grapple ends."
  "name": "Tentacles"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ humanoid [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled) by Grazilaxx.\
    \ Hit: The target takes 55 (10d10) piercing damage. If this damage reduces\
    \ the target to 0 hit points, Grazilaxx kills the target by extracting and devouring\
    \ its brain."
  "name": "Extract Brain"
- "desc": "Grazilaxx magically emits psychic energy in a 60-foot cone. Each creature\
    \ in that area must succeed on a DC 15 Intelligence saving throw or take 22 (4d8\
    \ + 4) psychic damage and be [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)\
    \ for 1 minute. A creature can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success."
  "name": "Mind Blast (Recharge 5-6)"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Grazilaxx.webp"
```
^statblock

```encounter-table
name: Grazilaxx
creatures:
 - 1: Grazilaxx
```