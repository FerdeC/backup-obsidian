---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/scc
- monster/cr/2
- monster/size/small-or-medium
- monster/type/humanoid/druid
aliases: ["Witherbloom Apprentice"]
NoteIcon: monster
BestiaryType: humanoid (druid)
SourceType: Bestiary
BookSource: Strixhaven: A Curriculum of Chaos p. 221
---
# [Witherbloom Apprentice](2-Mechanics\CLI\bestiary\humanoid/witherbloom-apprentice-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 221*  

Deep in the fog and muck of the swamp, the students of Witherbloom College—first as apprentices and then as pledgemages—study the cycle of life and death. Their magic is fueled by what they call life essence: the ubiquitous energy that runs through living things.

Witherbloom students learn how to concoct magical potions and talismans, in addition to their spellcasting studies. Their magic ranges from necrotic shadows and withering bursts of poison to flourishing bursts of plant life.

## Witherbloom Scholars

Witherbloom College studies the magic inherent in the natural cycle of life and death. Witherbloom professors approach the philosophy from different directions, with one methodology focusing on decay and the other dealing with growth.

```statblock
"name": "Witherbloom Apprentice (SCC)"
"size": "Small or Medium"
"type": "humanoid"
"subtype": "druid"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"stats":
- !!int "10"
- !!int "14"
- !!int "13"
- !!int "12"
- !!int "15"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
  "Constitution": !!int "3"
"skillsaves":
  "Medicine": !!int "4"
  "Nature": !!int "5"
  "Perception": !!int "6"
"senses": "passive Perception 16"
"languages": "Common plus any two languages"
"cr": "2"
"traits":
- "desc": "The apprentice casts one of the following spells, requiring no material\
    \ components and using Wisdom as the spellcasting ability:\n\nAt will: [druidcraft](/2-Mechanics/CLI/spells/druidcraft.md),\
    \ [spare the dying](/2-Mechanics/CLI/spells/spare-the-dying.md)\n\n1/day each:\
    \ [pass without trace](/2-Mechanics/CLI/spells/pass-without-trace.md)"
  "name": "Spellcasting"
- "desc": "The apprentice regains 5 hit points at the start of its turn if it has\
    \ at least 1 hit point."
  "name": "Regeneration"
- "desc": "At the end of a 10-minute ritual, the apprentice can touch one willing\
    \ creature (including itself) and bestow upon it a small talisman imbued with\
    \ magic. Upon receiving the talisman, the creature gains 10 temporary hit points,\
    \ and it can add 1d6 to its initiative rolls while it wears the talisman. These\
    \ benefits last for 1 hour or until the apprentice conducts another ritual to\
    \ bestow another talisman. When the benefits expire, the talisman crumbles to\
    \ dust."
  "name": "Verdant Talisman"
"actions":
- "desc": "Melee Spell Attack: +4 to hit, reach 15 ft., one target. Hit: 7 (1d10\
    \ + 2) piercing damage plus 9 (2d8) poison damage. If the target is a Large\
    \ or smaller creature, the apprentice can pull it up to 10 feet closer to itself."
  "name": "Briar Vine"
"reactions":
- "desc": "When the apprentice sees a creature within 30 feet of itself drop to 0\
    \ hit points, the apprentice channels the expended life essence and targets another\
    \ creature it can see within 30 feet of itself. The target must succeed on a DC\
    \ 12 Constitution saving throw or become [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 minute. While [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ in this way, the target takes 3 (1d6) poison damage at the start of each of\
    \ its turns. The target can repeat the save at the end of each of its turns, ending\
    \ the effect on itself on a success."
  "name": "Wither Burst"
"source":
- "SCC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SCC/Witherbloom%20Apprentice.webp"
```
^statblock

```encounter-table
name: Witherbloom Apprentice
creatures:
 - 1: Witherbloom Apprentice
```