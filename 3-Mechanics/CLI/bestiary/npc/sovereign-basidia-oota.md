---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/2
- monster/size/large
- monster/type/plant
aliases: ["Sovereign Basidia"]
NoteIcon: monster
BestiaryType: plant
SourceType: Bestiary
BookSource: Out of the Abyss p. 88
---
# [Sovereign Basidia](2-Mechanics\CLI\bestiary\npc/sovereign-basidia-oota.md)
*Source: Out of the Abyss p. 88*  

```statblock
"name": "Sovereign Basidia (OotA)"
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
- "desc": "When Basidia takes damage, all other myconids within 240 feet of it can\
    \ sense its pain."
  "name": "Distress Spores"
- "desc": "While in sunlight, Basidia has disadvantage on ability checks, attack rolls,\
    \ and saving throws. Basidia dies if it spends more than 1 hour in direct sunlight."
  "name": "Sun Sickness"
"actions":
- "desc": "Basidia uses either its Hallucination Spores or its Pacifying Spores, then\
    \ makes a fist attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 8 (3d4\
    \ + 1) bludgeoning damage plus 7 (3d4) poison damage."
  "name": "Fist"
- "desc": "Basidia targets one corpse of a humanoid or a Large or smaller beast within\
    \ 5 feet of it and releases spores at the corpse. In 24 hours, the corpse rises\
    \ as a spore servant. The corpse stays animated for 1d4 + 1 weeks or until destroyed,\
    \ and it can't be animated again in this way."
  "name": "Animating Spores (3/Day)"
- "desc": "Basidia ejects spores at one creature it can see within 5 feet of it. The\
    \ target must succeed on a DC 12 Constitution saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 minute. The [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ target is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ while it hallucinates. The target can repeat the saving throw at the end of\
    \ each of its turns, ending the effect on itself on a success."
  "name": "Hallucination Spores"
- "desc": "Basidia ejects spores at one creature it can see within 5 feet of it. The\
    \ target must succeed on a DC 12 Constitution saving throw or be [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)\
    \ for 1 minute. The target can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success."
  "name": "Pacifying Spores"
- "desc": "A 30-foot radius of spores extends from Basidia. These spores can go around\
    \ corners and affect only creatures with an Intelligence of 2 or higher that aren't\
    \ undead, constructs, or elementals. Affected creatures can communicate telepathically\
    \ with one another while they are within 30 feet of each other. The effect lasts\
    \ for 1 hour."
  "name": "Rapport Spores"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Sovereign%20Basidia.webp"
```
^statblock

```encounter-table
name: Sovereign Basidia
creatures:
 - 1: Sovereign Basidia
```