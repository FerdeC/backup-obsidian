---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cm
- monster/cr/18
- monster/size/medium
- monster/type/undead
aliases: ["Lichen Lich"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Candlekeep Mysteries p. 223
---
# [Lichen Lich](2-Mechanics\CLI\bestiary\undead/lichen-lich-cm.md)
*Source: Candlekeep Mysteries p. 223*  

Lichen liches are undead remnants of powerful druids.

A lichen lich looks like a skeleton covered with fungi and bark-like lichen. A lichen lich has vines within its chest cavity. These vines exude viscid and poisonous black fluid.

```statblock
"name": "Lichen Lich (CM)"
"size": "Medium"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "225"
"hit_dice": "30d8 + 90"
"stats":
- !!int "11"
- !!int "16"
- !!int "16"
- !!int "14"
- !!int "20"
- !!int "16"
"speed": "30 ft."
"saves":
  "Charisma": !!int "9"
  "Wisdom": !!int "11"
  "Intelligence": !!int "8"
  "Constitution": !!int "9"
"skillsaves":
  "Medicine": !!int "11"
  "Nature": !!int "14"
  "Perception": !!int "11"
  "Survival": !!int "11"
"damage_resistances": "cold, necrotic"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned),\
  \ [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)"
"senses": "truesight 120 ft., passive Perception 21"
"languages": "Common, Druidic, Sylvan"
"cr": "18"
"traits":
- "desc": "The lich casts one of the following spells using Wisdom as the spellcasting\
    \ ability (save DC 19):\n\nAt will: [druidcraft](/2-Mechanics/CLI/spells/druidcraft.md)\n\
    \n1/day each: [antilife shell](/2-Mechanics/CLI/spells/antilife-shell.md),\
    \ [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), [speak with plants](/2-Mechanics/CLI/spells/speak-with-plants.md),\
    \ [transport via plants](/2-Mechanics/CLI/spells/transport-via-plants.md), \n\n\
    3/day each: [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [fog\
    \ cloud](/2-Mechanics/CLI/spells/fog-cloud.md), [pass without trace](/2-Mechanics/CLI/spells/pass-without-trace.md)"
  "name": "Spellcasting"
- "desc": "If the lich fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "If it has a phylactery, a destroyed lich gains a new body in 1d10 days,\
    \ regaining all its hit points and becoming active again. The new body appears\
    \ within 5 feet of the phylactery."
  "name": "Rejuvenation"
"actions":
- "desc": "The lich makes four attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one creature. Hit:\
    \ 17 (5d6) poison damage, and the target must succeed on a DC 19 Constitution\
    \ saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 minute. The target can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success."
  "name": "Poisonous Touch"
- "desc": "Ranged Spell Attack: +9 to hit, range 60 ft., one target. Hit: 14\
    \ (4d6) necrotic damage."
  "name": "Wither"
- "desc": "The lich fills up to ten 10-foot cubes with fire. Every cube must be within\
    \ 150 feet of the lich and occupy a space the lich can see, and each cube must\
    \ have at least one face adjacent to the face of another cube. Each creature in\
    \ the area must make a DC 19 Dexterity saving throw, taking 38 (7d10) fire damage\
    \ on a failed save, or half as much damage on a successful one. The fire ignites\
    \ flammable objects in the area that aren't being worn or carried. If the lich\
    \ chooses, plant life in the area is unaffected by the spell."
  "name": "Fire Storm (7th-Level Spell; 1/Day)"
"legendary_actions":
- "desc": "The lich makes an attack."
  "name": "Attack"
- "desc": "The lich targets one [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ creature it can see within 30 feet of it. The target must succeed on a DC 19\
    \ Constitution saving throw or fall [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)\
    \ until the [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) condition\
    \ ends on it."
  "name": "Poison Prick (Cost 2 Actions)"
- "desc": "The lich targets one creature it can see within 30 feet of it. The target\
    \ must succeed on a DC 19 Constitution saving throw or take 11 (2d10) necrotic\
    \ damage. The lich regains a number of hit points equal to the amount of damage\
    \ that the creature takes."
  "name": "Sap Life (Costs 2 Actions)"
"lair_actions":
- "desc": "On initiative count 20 (losing initiative ties), the lichen lich can take\
    \ a lair action to cause one of the following effects:"
  "name": ""
- "desc": "- Poisonous spores fill a 10-foot cube that the lich can see within 120\
    \ feet of it. Any creature that enters the cloud for the first time on a turn\
    \ or starts its turn there must succeed on a DC 19 Constitution saving throw or\
    \ be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) until the end of\
    \ its next turn. The cloud lasts for 1 minute or until it is dispersed by a strong\
    \ wind.  \n- The lich commands the might of its diseased grove, creating a shambling\
    \ mound. The shambling mound appears in an unoccupied space within 30 feet of\
    \ the lich, acts on its own initiative count, and obeys the lich's commands. The\
    \ shambling mound dies after 1 hour or when the lich uses this lair action again.\
    \  \n- Rotten roots and vines magically erupt in a 20-foot radius centered on\
    \ a point on the ground that the lich can see within 120 feet of it. The lich\
    \ is unaffected by the roots and vines. For all other creatures, the area becomes\
    \ difficult terrain, and each creature in the area must succeed on a DC 19 Strength\
    \ saving throw or be [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ by the roots. As an action, a creature can try to free itself or another creature\
    \ within its reach, doing so with a successful DC 19 Strength ([Athletics](/2-Mechanics/CLI/rules/skills.md#Athletics))\
    \ check. The roots and vines wilt away when the lich uses this lair action again\
    \ or when the lich dies.  "
  "name": ""
"source":
- "CM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CM/Lichen%20Lich.webp"
```
^statblock

```encounter-table
name: Lichen Lich
creatures:
 - 1: Lichen Lich
```