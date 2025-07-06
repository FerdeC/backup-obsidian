---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/17
- monster/size/huge
- monster/type/dragon
aliases: ["Themberchaud"]
NoteIcon: monster
BestiaryType: dragon
SourceType: Bestiary
BookSource: Out of the Abyss p. 53
---
# [Themberchaud](2-Mechanics\CLI\bestiary\npc/themberchaud-oota.md)
*Source: Out of the Abyss p. 53*  

```statblock
"name": "Themberchaud (OotA)"
"size": "Huge"
"type": "dragon"
"alignment": "Chaotic Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "256"
"hit_dice": "19d12 + 133"
"stats":
- !!int "27"
- !!int "10"
- !!int "25"
- !!int "16"
- !!int "13"
- !!int "21"
"speed": "40 ft., climb 40 ft., fly 80 ft."
"saves":
  "Charisma": !!int "11"
  "Dexterity": !!int "6"
  "Wisdom": !!int "7"
  "Constitution": !!int "13"
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "13"
"damage_immunities": "fire"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 23"
"languages": "Common, Draconic"
"cr": "17"
"traits":
- "desc": "If Themberchaud fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
"actions":
- "desc": "Themberchaud can use its Frightful Presence. It then makes three attacks:\
    \ one with its bite and two with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 19\
    \ (2d10 + 8) piercing damage plus 7 (2d6) fire damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +14 to hit, reach 5 ft., one target. Hit: 15\
    \ (2d6 + 8) slashing damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +14 to hit, reach 15 ft., one target. Hit: 17\
    \ (2d8 + 8) bludgeoning damage."
  "name": "Tail"
- "desc": "Each creature of Themberchaud's choice that is within 120 feet of Themberchaud\
    \ and aware of it must succeed on a DC 19 Wisdom saving throw or become [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ for 1 minute. A creature can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success. If a creature's saving throw\
    \ is successful or the effect ends for it, the creature is immune to Themberchaud's\
    \ Frightful Presence for the next 24 hours."
  "name": "Frightful Presence"
- "desc": "Themberchaud exhales fire in a 60-foot cone. Each creature in that area\
    \ must make a DC 21 Dexterity saving throw, taking 63 (18d6) fire damage on\
    \ a failed save, or half as much damage on a successful one."
  "name": "Fire Breath (Recharge 5-6)"
"legendary_actions":
- "desc": "Themberchaud makes a Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ check."
  "name": "Detect"
- "desc": "Themberchaud makes a tail attack."
  "name": "Tail Attack"
- "desc": "Themberchaud beats its wings. Each creature within 10 feet of Themberchaud\
    \ must succeed on a DC 22 Dexterity saving throw or take 15 (2d6 + 8) bludgeoning\
    \ damage and be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone). Themberchaud\
    \ can then fly up to half its flying speed."
  "name": "Wing Attack (Costs 2 Actions)"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Themberchaud.webp"
```
^statblock

```encounter-table
name: Themberchaud
creatures:
 - 1: Themberchaud
```