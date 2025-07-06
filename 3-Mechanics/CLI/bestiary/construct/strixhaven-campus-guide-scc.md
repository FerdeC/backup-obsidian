---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/scc
- monster/cr/1
- monster/size/small
- monster/type/construct
aliases: ["Strixhaven Campus Guide"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Strixhaven: A Curriculum of Chaos p. 217
---
# [Strixhaven Campus Guide](2-Mechanics\CLI\bestiary\construct/strixhaven-campus-guide-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 217*  

With cheerful dispositions and a knack for walking backward, Strixhaven campus guides lead gaggles of prospective students on tours. The guides' gold and silver chassis are built in shapes reminiscent of the star arches surrounding Strixhaven. Embedded in their chests are holographic maps of the university's campuses, which the guides use to provide directions. However, it's rare for a campus guide to need its own maps, as these gregarious automatons have a gift for finding things on campus, often popping up at the most inopportune times.

```statblock
"name": "Strixhaven Campus Guide (SCC)"
"size": "Small"
"type": "construct"
"alignment": "typically  Lawful Good"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "31"
"hit_dice": "7d6 + 7"
"stats":
- !!int "15"
- !!int "14"
- !!int "13"
- !!int "10"
- !!int "12"
- !!int "12"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "4"
"skillsaves":
  "Insight": !!int "3"
  "Persuasion": !!int "3"
"damage_immunities": "poison"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened), [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 60 ft., passive Perception 11"
"languages": "Common plus any three languages"
"cr": "1"
"traits":
- "desc": "While at Strixhaven, the guide can't become lost by magical or nonmagical\
    \ means. The guide also has advantage on ability checks made to locate creatures\
    \ or objects at Strixhaven."
  "name": "Campus Knowledge"
- "desc": "When the guide speaks, any creature that knows at least one language and\
    \ can hear the guide understands what it says."
  "name": "Univocal Speech"
- "desc": "The guide doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The guide makes two Slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) bludgeoning damage."
  "name": "Slam"
- "desc": "Each creature of the guide's choice that is within 30 feet of the guide\
    \ must succeed on a DC 11 Wisdom saving throw or be magically [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ by the guide for 1 hour.\n\nA [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ target must move on its turn toward the guide, trying to get within 5 feet of\
    \ the guide. The target doesn't move into obviously dangerous ground, such as\
    \ a fire or a pit. Whenever the [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ target takes damage, it can repeat the saving throw, ending the effect on itself\
    \ on a success.\n\nA target that successfully saves is immune to any guide's Smile\
    \ and Wave ability for the next 24 hours."
  "name": "Smile and Wave"
"bonus_actions":
- "desc": "The guide takes the Help action."
  "name": "Need Directions"
"source":
- "SCC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SCC/Strixhaven%20Campus%20Guide.webp"
```
^statblock

```encounter-table
name: Strixhaven Campus Guide
creatures:
 - 1: Strixhaven Campus Guide
```