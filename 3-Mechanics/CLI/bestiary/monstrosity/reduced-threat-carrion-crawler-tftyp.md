---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/2
- monster/size/large
- monster/type/monstrosity
aliases: ["Reduced-Threat Carrion Crawler"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 113
---
# [Reduced-Threat Carrion Crawler](2-Mechanics\CLI\bestiary\monstrosity/reduced-threat-carrion-crawler-tftyp.md)
*Source: Tales from the Yawning Portal p. 113*  

```statblock
"name": "Reduced-Threat Carrion Crawler (TftYP)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "25"
"hit_dice": "6d10 + 18"
"stats":
- !!int "14"
- !!int "13"
- !!int "16"
- !!int "1"
- !!int "12"
- !!int "5"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Perception": !!int "1"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": ""
"cr": "2"
"traits":
- "desc": "A reduced-threat monster takes a −2 penalty on attack rolls (included in\
    \ the stat block), ability checks (included in the stat block for skill proficiencies),\
    \ saving throws (included in the stat block for saving throw proficiencies), and\
    \ saving throw DCs (included in the stat block)."
  "name": "Reduced Threat"
- "desc": "The carrion crawler has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "The carrion crawler can climb difficult surfaces, including upside down\
    \ on ceilings, without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "The carrion crawler makes two attacks: one with its tentacles and one with\
    \ its bite."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one creature. Hit:\
    \ 4 (1d4 + 2) poison damage, and the target must succeed on a DC 11 Constitution\
    \ saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 minute. Until this poison ends, the target is [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed).\
    \ The target can repeat the saving throw at the end of each of its turns, ending\
    \ the poison on itself on a success."
  "name": "Tentacles"
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 7 (2d4\
    \ + 2) piercing damage."
  "name": "Bite"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Reduced-Threat%20Carrion%20Crawler.webp"
```
^statblock

```encounter-table
name: Reduced-Threat Carrion Crawler
creatures:
 - 1: Reduced-Threat Carrion Crawler
```