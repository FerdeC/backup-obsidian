---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cos
- monster/cr/6
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Stanimir"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Curse of Strahd p. 20
---
# [Stanimir](2-Mechanics\CLI\bestiary\npc/stanimir-cos.md)
*Source: Curse of Strahd p. 20*  

```statblock
"name": "Stanimir (CoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Neutral"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "40"
"hit_dice": "9d8"
"stats":
- !!int "9"
- !!int "14"
- !!int "11"
- !!int "17"
- !!int "12"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
  "Intelligence": !!int "6"
"skillsaves":
  "History": !!int "6"
  "Arcana": !!int "6"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "6"
"traits":
- "desc": "Stanimir is a 9th-level spellcaster. Its spellcasting ability is Intelligence\
    \ (spell save DC 14, +6 to hit with spell attacks). Stanimir has the following\
    \ wizard spells prepared:\n\nCantrips (at will): [friends](/2-Mechanics/CLI/spells/friends.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\n1st level\
    \ (4 slots): [charm person](/2-Mechanics/CLI/spells/charm-person.md), [mage\
    \ armor](/2-Mechanics/CLI/spells/mage-armor.md), [shield](/2-Mechanics/CLI/spells/shield.md),\
    \ [sleep](/2-Mechanics/CLI/spells/sleep.md)\n\n2nd level (3 slots): [misty\
    \ step](/2-Mechanics/CLI/spells/misty-step.md), [suggestion](/2-Mechanics/CLI/spells/suggestion.md)\n\
    \n3rd level (3 slots): [bestow curse](/2-Mechanics/CLI/spells/bestow-curse.md),\
    \ [phantom steed](/2-Mechanics/CLI/spells/phantom-steed.md), [vampiric touch](/2-Mechanics/CLI/spells/vampiric-touch.md)\n\
    \n4th level (3 slots): [greater invisibility](/2-Mechanics/CLI/spells/greater-invisibility.md),\
    \ [stoneskin](/2-Mechanics/CLI/spells/stoneskin.md)\n\n5th level (1 slots):\
    \ [dominate person](/2-Mechanics/CLI/spells/dominate-person.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "CoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CoS/Stanimir.webp"
```
^statblock

```encounter-table
name: Stanimir
creatures:
 - 1: Stanimir
```