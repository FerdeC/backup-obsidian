---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/rot
- monster/cr/7
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Varram"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: The Rise of Tiamat p. 9
---
# [Varram](2-Mechanics\CLI\bestiary\npc/varram-rot.md)
*Source: The Rise of Tiamat p. 9*  

```statblock
"name": "Varram (RoT)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "110"
"hit_dice": "17d8 + 34"
"stats":
- !!int "11"
- !!int "18"
- !!int "14"
- !!int "13"
- !!int "12"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
"skillsaves":
  "Deception": !!int "6"
  "Stealth": !!int "7"
"damage_resistances": "one of the following: acid, cold, fire, lightning, poison;\
  \ poison"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Draconic, Infernal, Dwarvish"
"cr": "7"
"traits":
- "desc": "Varram is presented in The Rise of Tiamat as a male dwarf. The [dragonsoul](/2-Mechanics/CLI/bestiary/humanoid/dragonsoul-rot.md)\
    \ stat block, modified with dwarf racial traits, has been provided here for ease\
    \ of use."
  "name": "5etools Note"
- "desc": "Varram has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened). While Varram\
    \ can see a dragon or higher-ranking Cult of the Dragon cultist friendly to it,\
    \ Varram ignores the effects of being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Dragon Fanatic"
- "desc": "Once per turn, if Varram makes a weapon attack with advantage on the attack\
    \ roll and hits, the target takes an extra 10 (3d6) damage."
  "name": "Fanatic Advantage"
- "desc": "Varram can use a bonus action to gain a flying speed of 30 feet until the\
    \ end of its turn."
  "name": "Limited Flight"
- "desc": "Varram has advantage on an attack roll against a creature if at least one\
    \ of Varram's allies is within 5 feet of the creature and the ally isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
- "desc": "Varram"
  "name": "Dwarven Resilience"
"actions":
- "desc": "Varram attacks twice with its shortsword."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage plus 10 (3d6) damage of the type to which Varram has\
    \ resistance."
  "name": "Shortsword"
- "desc": "Ranged Spell Attack: +7 to hit, range 90 ft., one target. Hit: 27\
    \ (6d8) damage of the type to which Varram has damage resistance."
  "name": "Orb of Dragon's Breath (3/Day)"
"source":
- "RoT"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/RoT/Varram.webp"
```
^statblock

```encounter-table
name: Varram
creatures:
 - 1: Varram
```