---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cos
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Lady Fiona Wachter"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Curse of Strahd p. 110
---
# [Lady Fiona Wachter](2-Mechanics\CLI\bestiary\npc/lady-fiona-wachter-cos.md)
*Source: Curse of Strahd p. 110*  

```statblock
"name": "Lady Fiona Wachter (CoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "10"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "10"
- !!int "10"
- !!int "12"
- !!int "13"
- !!int "16"
- !!int "13"
"speed": "30 ft."
"skillsaves":
  "Medicine": !!int "7"
  "Religion": !!int "5"
  "Persuasion": !!int "3"
"senses": "passive Perception 13"
"languages": "any two languages"
"cr": "2"
"traits":
- "desc": "Fiona is a 5th-level spellcaster. Her spellcasting ability is Wisdom (spell\
    \ save DC 13, +5 to hit with spell attacks). Fiona has the following cleric\
    \ spells prepared:\n\nCantrips (at will): [light](/2-Mechanics/CLI/spells/light.md),\
    \ [mending](/2-Mechanics/CLI/spells/mending.md), [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1st level (4 slots): [command](/2-Mechanics/CLI/spells/command.md), [purify\
    \ food and drink](/2-Mechanics/CLI/spells/purify-food-and-drink.md), [sanctuary](/2-Mechanics/CLI/spells/sanctuary.md)\n\
    \n2nd level (3 slots): [augury](/2-Mechanics/CLI/spells/augury.md), [gentle\
    \ repose](/2-Mechanics/CLI/spells/gentle-repose.md), [hold person](/2-Mechanics/CLI/spells/hold-person.md)\n\
    \n3rd level (2 slots): [animate dead](/2-Mechanics/CLI/spells/animate-dead.md),\
    \ [create food and water](/2-Mechanics/CLI/spells/create-food-and-water.md)"
  "name": "Spellcasting"
- "desc": "As a bonus action, Fiona can expend a spell slot to cause its melee weapon\
    \ attacks to magically deal an extra 10 (3d6) radiant damage to a target on\
    \ a hit. This benefit lasts until the end of the turn. If Fiona expends a spell\
    \ slot of 2nd level or higher, the extra damage increases by 1d6 for each level\
    \ above 1st."
  "name": "Divine Eminence"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 3 (1d6)\
    \ bludgeoning damage."
  "name": "Mace"
"source":
- "CoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CoS/Lady%20Fiona%20Wachter.webp"
```
^statblock

```encounter-table
name: Lady Fiona Wachter
creatures:
 - 1: Lady Fiona Wachter
```