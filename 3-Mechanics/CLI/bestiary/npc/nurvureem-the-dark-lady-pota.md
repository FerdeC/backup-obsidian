---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/14
- monster/size/huge
- monster/type/dragon
aliases: ["Nurvureem, The Dark Lady"]
NoteIcon: monster
BestiaryType: dragon
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 180
---
# [Nurvureem, The Dark Lady](2-Mechanics\CLI\bestiary\npc/nurvureem-the-dark-lady-pota.md)
*Source: Princes of the Apocalypse p. 180*  

```statblock
"name": "Nurvureem, The Dark Lady (PotA)"
"size": "Huge"
"type": "dragon"
"alignment": "Chaotic Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "195"
"hit_dice": "17d12 + 85"
"stats":
- !!int "23"
- !!int "14"
- !!int "21"
- !!int "14"
- !!int "13"
- !!int "17"
"speed": "40 ft., fly 80 ft., swim 40 ft."
"saves":
  "Charisma": !!int "8"
  "Dexterity": !!int "7"
  "Wisdom": !!int "6"
  "Constitution": !!int "10"
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "11"
"damage_resistances": "necrotic"
"damage_immunities": "acid"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 21"
"languages": "Common, Draconic"
"cr": "14"
"traits":
- "desc": "Nurvureem can breathe air and water."
  "name": "Amphibious"
- "desc": "If Nurvureem fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "While in dim light or darkness, the dragon has resistance to damage that\
    \ isn't force, psychic, or radiant."
  "name": "Living Shadow"
- "desc": "While in dim light or darkness, the dragon can take the [Hide](/2-Mechanics/CLI/rules/actions.md#Hide)\
    \ action as a bonus action."
  "name": "Shadow Stealth"
- "desc": "While in sunlight, the dragon has disadvantage on attack rolls, as well\
    \ as on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Nurvureem can use its Frightful Presence. It then makes three attacks:\
    \ one with its bite and two with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 17\
    \ (2d10 + 6) piercing damage plus 4 (1d8) necrotic damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +11 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d6 + 6) slashing damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +11 to hit, reach 15 ft., one target. Hit: 15\
    \ (2d8 + 6) bludgeoning damage."
  "name": "Tail"
- "desc": "Each creature of Nurvureem's choice that is within 120 feet of Nurvureem\
    \ and aware of it must succeed on a DC 16 Wisdom saving throw or become [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ for 1 minute. A creature can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success. If a creature's saving throw\
    \ is successful or the effect ends for it, the creature is immune to Nurvureem's\
    \ Frightful Presence for the next 24 hours."
  "name": "Frightful Presence"
- "desc": "Nurvureem exhales necrotic in a 60-foot line that is 5 feet wide. Each\
    \ creature in that line must make a DC 18 Dexterity saving throw, taking 54 (12d8)\
    \ necrotic damage on a failed save, or half as much damage on a successful one."
  "name": "Acid Breath (Recharge 5-6)"
"legendary_actions":
- "desc": "Nurvureem makes a Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ check."
  "name": "Detect"
- "desc": "Nurvureem makes a tail attack."
  "name": "Tail Attack"
- "desc": "Nurvureem beats its wings. Each creature within 10 feet of Nurvureem must\
    \ succeed on a DC 19 Dexterity saving throw or take 13 (2d6 + 6) bludgeoning\
    \ damage and be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone). Nurvureem\
    \ can then fly up to half its flying speed."
  "name": "Wing Attack (Costs 2 Actions)"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Nurvureem%2C%20The%20Dark%20Lady.webp"
```
^statblock

```encounter-table
name: Nurvureem, The Dark Lady
creatures:
 - 1: Nurvureem, The Dark Lady
```