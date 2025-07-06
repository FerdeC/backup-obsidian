---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/
- monster/size/medium
- monster/type/humanoid/tethyrian-human
aliases: ["Narth Tezrin"]
NoteIcon: monster
BestiaryType: humanoid (Tethyrian human)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 254
---
# [Narth Tezrin](2-Mechanics\CLI\bestiary\npc/narth-tezrin-skt.md)
*Source: Storm King's Thunder p. 254*  

Narth sells gear to adventurers, and he also has an adventurous spirit. The Lionshield Coster pays him well, but he longs to make a name for himself. At the same time, he runs a business with his partner Alaestra and knows she wouldn't forgive him if he ran off and never returned.

Ideal:"The bigger the risk, the greater the reward."

Bond:"I adore my colleague Alaestra, and I'd like to do something to impress her."

Flaw:"I'll risk life and limb to become a legend."

```statblock
"name": "Narth Tezrin (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Tethyrian human"
"alignment": "Chaotic Good"
"ac": !!int "12"
"hp": !!int "18"
"hit_dice": "4d8"
"stats":
- !!int "10"
- !!int "15"
- !!int "10"
- !!int "12"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Investigation": !!int "3"
  "Insight": !!int "4"
  "Perception": !!int "6"
  "Persuasion": !!int "5"
"senses": "passive Perception 16"
"languages": "Common, Dwarvish"
"traits":
- "desc": "On each of his turns, Narth can use a bonus action to take the Dash, Disengage,\
    \ or Hide action."
  "name": "Cunning Action"
- "desc": "Narth sells gear to adventurers, and he also has an adventurous spirit.\
    \ The Lionshield Coster pays him well, but he longs to make a name for himself.\
    \ At the same time, he runs a business with his partner Alaestra and knows she\
    \ wouldn't forgive him if he ran off and never returned.\n\nIdeal: \"The bigger\
    \ the risk, the greater the reward.\"\n\nBond: \"I adore my colleague Alestra,\
    \ and I'd like to do something to impress her.\"\n\nFlaw: \"I'll risk life and\
    \ limb to become a legend.-\""
  "name": "Roleplaying Information"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit:\
    \ 5 (1d6 + 2) piercing damage. Narth carries twenty crossbow bolts."
  "name": "Hand Crossbow"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Narth%20Tezrin.webp"
```
^statblock

```encounter-table
name: Narth Tezrin
creatures:
 - 1: Narth Tezrin
```