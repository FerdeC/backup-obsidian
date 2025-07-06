---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wbtw
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid
aliases: ["Witchlight Hand (Medium)"]
NoteIcon: monster
BestiaryType: humanoid
SourceType: Bestiary
BookSource: The Wild Beyond the Witchlight p. 27
---
# [Witchlight Hand (Medium)](2-Mechanics\CLI\bestiary\humanoid/witchlight-hand-medium-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 27*  

Witchlight hands are the backbone of the Witchlight Carnival, a motley collection of individuals who operate many of the booths, make repairs, feed and exercise the animals, keep an eye out for thieves and other miscreants, and perform other miscellaneous tasks as Mister Witch dictates. A few also work part-time as performers and attractions. Although they travel to many worlds throughout the Material Plane, Witchlight hands rarely leave the carnival grounds. The carnival is the only world they know and care about.

All hands enter into an agreement when they join the carnival: they must never harm another staff member, and they can't leave the carnival for more than a day at a time. (A longer absence is equivalent to resignation, in Mister Witch's estimation.) On-duty staff members are required to wear fake butterfly wings strapped to their backs. Mister Witch and Mister Light also furnish them with small amounts of pixie dust (see appendix A).

Witchlight hands are paid only a small fraction of the carnival's profits, but it's enough to keep them fed, clothed, and cared for. Some hands work longer hours or do extra chores to pay off debts and loans.

Most Witchlight hands are taught how to perform minor magic tricks, which they use to amuse themselves as well as entertain the masses.

```statblock
"name": "Witchlight Hand (Medium) (WBtW)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "10"
- !!int "14"
- !!int "11"
- !!int "12"
- !!int "13"
- !!int "12"
"speed": "30 ft."
"skillsaves":
  "Sleight of Hand": !!int "6"
"senses": "passive Perception 11"
"languages": "Common plus any one language"
"cr": "1/8"
"traits":
- "desc": "The hand casts one of the following spells, using Charisma as the spellcasting\
    \ ability:\n\nAt will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md),\
    \ [message](/2-Mechanics/CLI/spells/message.md), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)"
  "name": "Spellcasting"
- "desc": "The hand has one of these additional skills: [Acrobatics](/2-Mechanics/CLI/rules/skills.md#Acrobatics)\
    \ [Acrobatics](/2-Mechanics/CLI/rules/skills.md#Acrobatics) (+6), [Animal Handling](/2-Mechanics/CLI/rules/skills.md#Animal%20Handling)\
    \ [Animal Handling](/2-Mechanics/CLI/rules/skills.md#Animal%20Handling) (+5),\
    \ [Arcana](/2-Mechanics/CLI/rules/skills.md#Arcana) [Arcana](/2-Mechanics/CLI/rules/skills.md#Arcana)\
    \ (+5), [Athletics](/2-Mechanics/CLI/rules/skills.md#Athletics) [Athletics](/2-Mechanics/CLI/rules/skills.md#Athletics)\
    \ (+4), [Medicine](/2-Mechanics/CLI/rules/skills.md#Medicine) [Medicine](/2-Mechanics/CLI/rules/skills.md#Medicine)\
    \ (+5), or [Performance](/2-Mechanics/CLI/rules/skills.md#Performance) [Performance](/2-Mechanics/CLI/rules/skills.md#Performance)\
    \ (+5)."
  "name": "Secret Expertise"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
- "desc": "The hand sprinkles a pinch of pixie dust on itself or another creature\
    \ it can see within 5 feet of it. The recipient gains a flying speed of 30 feet\
    \ for 1 minute. If the creature is airborne when this effect ends, it falls safely\
    \ to the ground, taking no damage and landing on its feet."
  "name": "Pixie Dust (1/Day)"
"source":
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WBtW/Witchlight%20Hand%20%28Medium%29.webp"
```
^statblock

```encounter-table
name: Witchlight Hand (Medium)
creatures:
 - 1: Witchlight Hand (Medium)
```