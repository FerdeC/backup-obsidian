---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/ftd
- monster/cr/2
- monster/size/small
- monster/type/humanoid
aliases: ["Dragon Speaker"]
NoteIcon: monster
BestiaryType: humanoid
SourceType: Bestiary
BookSource: Fizban's Treasury of Dragons p. 189
---
# [Dragon Speaker](2-Mechanics\CLI\bestiary\humanoid/dragon-speaker-ftd.md)
*Source: Fizban's Treasury of Dragons p. 189*  

Dragon speakers are charismatic and persuasive orators who serve as a dragon's ambassadors among other folk. Dragon speakers have loud and authoritative voices, which they use to gain valuable resources, diplomatic connections, and donations of treasure and magic for their dragons—as well as to weave magic both subtle and thundering. They use their commanding presence to instill awe and fear into the hearts of friends and foes alike.

## Dragon Followers

Dragons boast many minions, students, employees, acolytes, and thralls. Dragon followers are those servitors whose devotion to a dragon approaches fanatical reverence and who receive magical power from the dragon in return.

Dragon followers might serve and revere any kind of dragon, and their behavior and beliefs reflect the ethos of the dragon they follow. Many dragon followers have personal stories of benevolent dragons sharing great knowledge, protecting their towns, or sparing their lives during some foolhardy adventure. Other followers seek to uncover the mysteries of draconic nature and live a life worthy of their dragon's reward, and they dream of a world where dragons can live among them as their rulers.

```statblock
"name": "Dragon Speaker (FTD)"
"size": "Small"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "36"
"hit_dice": "8d6 + 8"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "13"
- !!int "11"
- !!int "17"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Dexterity": !!int "4"
"skillsaves":
  "Religion": !!int "3"
  "Persuasion": !!int "5"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Draconic, and any two languages"
"cr": "2"
"traits":
- "desc": "The speaker casts one of the following spells, using Charisma as the spellcasting\
    \ ability (spell save DC 13):\n\nAt will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\
    \n1/day each: [calm emotions](/2-Mechanics/CLI/spells/calm-emotions.md), [charm\
    \ person](/2-Mechanics/CLI/spells/charm-person.md), [command](/2-Mechanics/CLI/spells/command.md),\
    \ [comprehend languages](/2-Mechanics/CLI/spells/comprehend-languages.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The speaker makes two Thunder Bolt attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 60 ft.,\
    \ one target. Hit: 13 (3d8) thunder damage, and the target is pushed horizontally\
    \ up to 10 feet away from the speaker."
  "name": "Thunder Bolt"
"reactions":
- "desc": "When a creature the speaker can see within 60 feet of it makes a damage\
    \ roll, the speaker can roll a d6 and subtract the number rolled from that damage\
    \ roll."
  "name": "Disarming Words (3/Day)"
"source":
- "FTD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/FTD/Dragon%20Speaker.webp"
```
^statblock

```encounter-table
name: Dragon Speaker
creatures:
 - 1: Dragon Speaker
```