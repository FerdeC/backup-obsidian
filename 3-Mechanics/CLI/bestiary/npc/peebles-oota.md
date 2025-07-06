---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Peebles"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Out of the Abyss p. 134
---
# [Peebles](2-Mechanics\CLI\bestiary\npc/peebles-oota.md)
*Source: Out of the Abyss p. 134*  

```statblock
"name": "Peebles (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
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
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "any two languages, Gnomish, Terran, Undercommon"
"cr": "1"
"traits":
- "desc": "Peebles\n\nAt will: [nondetection](/2-Mechanics/CLI/spells/nondetection.md)\
    \ (self only)\n\n1/day each: [blindness/deafness](/2-Mechanics/CLI/spells/blindness-deafness.md),\
    \ [blur](/2-Mechanics/CLI/spells/blur.md), [disguise self](/2-Mechanics/CLI/spells/disguise-self.md)"
  "name": "Innate Spellcasting"
- "desc": "On each of its turns, Peebles can use a bonus action to take the Dash,\
    \ Disengage, or Hide action."
  "name": "Cunning Action"
- "desc": "Peebles deals an extra 7 (2d6) damage when it hits a target with a weapon\
    \ attack and has advantage on the attack roll, or when the target is within 5\
    \ feet of an ally of Peebles that isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ and Peebles doesn't have disadvantage on the attack roll."
  "name": "Sneak Attack (1/Turn)"
- "desc": "Peebles"
  "name": "Gnome Cunning"
- "desc": "Peebles"
  "name": "Stone Camouflage"
"actions":
- "desc": "Peebles makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit:\
    \ 5 (1d6 + 2) piercing damage."
  "name": "Hand Crossbow"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Peebles.webp"
```
^statblock

```encounter-table
name: Peebles
creatures:
 - 1: Peebles
```