---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dosi
- monster/cr/2
- monster/size/large
- monster/type/plant
aliases: ["Sinensa"]
NoteIcon: monster
BestiaryType: plant
SourceType: Bestiary
BookSource: Dragons of Stormwreck Isle p. 45
---
# [Sinensa](2-Mechanics\CLI\bestiary\npc/sinensa-dosi.md)
*Source: Dragons of Stormwreck Isle p. 45*  

Myconids are intelligent, mobile fungi that live in caves, seek enlightenment, and dislike violence. Adult myconids live and work together in colonies and practice a form of communal meditation called a meld, in which they seek to transcend mundane reality through shared hallucination.

Myconid leaders like Sinensa use their Hallucination Spores to help myconids create melds.

```statblock
"name": "Sinensa (DoSI)"
"size": "Large"
"type": "plant"
"alignment": "Lawful Neutral"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "60"
"hit_dice": "8d10 + 16"
"stats":
- !!int "12"
- !!int "10"
- !!int "14"
- !!int "13"
- !!int "15"
- !!int "10"
"speed": "30 ft."
"senses": "darkvision 120 ft., passive Perception 12"
"languages": ""
"cr": "2"
"traits":
- "desc": "When Sinensa takes damage, all other myconids within 240 feet of it can\
    \ sense its pain."
  "name": "Distress Spores"
- "desc": "While in sunlight, Sinensa has disadvantage on ability checks, attack rolls,\
    \ and saving throws. Sinensa dies if it spends more than 1 hour in direct sunlight."
  "name": "Sun Sickness"
"actions":
- "desc": "The myconid makes one Fist attack and uses its Hallucination Spores."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 8 (3d4\
    \ + 1) bludgeoning damage plus 7 (2d4) poison damage."
  "name": "Fist"
- "desc": "Sinensa ejects spores at one creature it can see within 5 feet of it. The\
    \ target must succeed on a DC 12 Constitution saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 minute. The [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ target is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ while it hallucinates. The target can repeat the saving throw at the end of\
    \ each of its turns, ending the effect on itself on a success."
  "name": "Hallucination Spores"
- "desc": "A 30-foot radius of spores extends from Sinensa. These spores can go around\
    \ corners and affect only creatures with an Intelligence of 2 or higher that aren't\
    \ undead, constructs, or elementals. Affected creatures can communicate telepathically\
    \ with one another while they are within 30 feet of each other. The effect lasts\
    \ for 1 hour."
  "name": "Rapport Spores"
"source":
- "DoSI"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DoSI/Sinensa.webp"
```
^statblock

```encounter-table
name: Sinensa
creatures:
 - 1: Sinensa
```