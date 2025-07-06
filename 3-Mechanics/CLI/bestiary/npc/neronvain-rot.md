---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/rot
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Neronvain"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: The Rise of Tiamat p. 91
---
# [Neronvain](2-Mechanics\CLI\bestiary\npc/neronvain-rot.md)
*Source: The Rise of Tiamat p. 91*  

```statblock
"name": "Neronvain (RoT)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Evil"
"ac": !!int "17"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"stats":
- !!int "8"
- !!int "17"
- !!int "15"
- !!int "16"
- !!int "13"
- !!int "18"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
  "Constitution": !!int "5"
"skillsaves":
  "Perception": !!int "4"
  "Arcana": !!int "6"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common, Draconic, Elvish, Infernal"
"cr": "9"
"traits":
- "desc": "Neronvain adds his Charisma bonus to his AC (included)."
  "name": "Draconic Majesty"
- "desc": "Magic can't put Neronvain to sleep."
  "name": "Fey Ancestry"
"actions":
- "desc": "Neronvain makes two attacks, either with his shortsword or Eldritch Arrow."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage plus 13 (3d8) poison damage."
  "name": "Shortsword"
- "desc": "Ranged Spell Attack: +7 to hit, range 120 ft., one target. Hit: 11\
    \ (2d10) force damage plus 9 (2d8) poison damage."
  "name": "Eldritch Arrow"
- "desc": "Poison gas fills a 20-foot-radius sphere centered on a point Neronvain\
    \ can see within 50 feet of him. The gas spreads around corners and remains until\
    \ the start of Neronvain's next turn. Each creature that starts its turn in the\
    \ gas must succeed on a DC 16 Constitution saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 minute. A creature can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success."
  "name": "Poisonous Cloud (2/Day)"
"source":
- "RoT"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/RoT/Neronvain.webp"
```
^statblock

```encounter-table
name: Neronvain
creatures:
 - 1: Neronvain
```