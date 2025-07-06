---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/3
- monster/size/small
- monster/type/humanoid/derro
aliases: ["Y"]
NoteIcon: monster
BestiaryType: humanoid (derro)
SourceType: Bestiary
BookSource: Out of the Abyss p. 29
---
# [Y](2-Mechanics\CLI\bestiary\npc/y-oota.md)
*Source: Out of the Abyss p. 29*  

```statblock
"name": "Y (OotA)"
"size": "Small"
"type": "humanoid"
"subtype": "derro"
"alignment": "Neutral"
"ac": !!int "13"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "36"
"hit_dice": "8d6 + 8"
"stats":
- !!int "9"
- !!int "14"
- !!int "12"
- !!int "18"
- !!int "5"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "4"
"senses": "darkvision 120 ft., passive Perception 7"
"languages": "Dwarvish, Undercommon, Elvish"
"cr": "3"
"traits":
- "desc": "Y is a 5th-level spellcaster. Its spellcasting ability is Charisma (spell\
    \ save DC 12, +4 to hit with spell attacks). The derro knows the following sorcerer\
    \ spells:\n\nCantrips (at will): [acid splash](/2-Mechanics/CLI/spells/acid-splash.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [message](/2-Mechanics/CLI/spells/message.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md), [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md)\n\
    \n1st level (4 slots): [burning hands](/2-Mechanics/CLI/spells/burning-hands.md),\
    \ [chromatic orb](/2-Mechanics/CLI/spells/chromatic-orb.md), [sleep](/2-Mechanics/CLI/spells/sleep.md)\n\
    \n2nd level (3 slots): [invisibility](/2-Mechanics/CLI/spells/invisibility.md),\
    \ [spider climb](/2-Mechanics/CLI/spells/spider-climb.md)\n\n3rd level (2 slots):\
    \ [lightning bolt](/2-Mechanics/CLI/spells/lightning-bolt.md)"
  "name": "Spellcasting"
- "desc": "Y can innately cast can cast the [teleport](/2-Mechanics/CLI/spells/teleport.md)\
    \ spell once per day, but the intended destination must be within 30 feet of another\
    \ society member. This teleport effect can be disrupted (see \"Faerzress\"), which\
    \ is how society members sometimes end up in far corners of the Underdark, separated\
    \ from their fellows.\n\n1/day each: [teleport](/2-Mechanics/CLI/spells/teleport.md)"
  "name": "Innate Spellcasting"
- "desc": "Y has advantage on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
- "desc": "While in sunlight, Y has disadvantage on attack rolls, as well as on Wisdom\
    \ ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely\
    \ on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee Weapon Attack: +1 to hit, reach 5 ft., one target. Hit: 2 (1d6\
    \ - 1) bludgeoning damage."
  "name": "Quarterstaff"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Y.webp"
```
^statblock

```encounter-table
name: Y
creatures:
 - 1: Y
```