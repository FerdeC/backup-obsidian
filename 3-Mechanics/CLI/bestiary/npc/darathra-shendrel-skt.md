---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/
- monster/size/medium
- monster/type/humanoid/chondathan-human
aliases: ["Darathra Shendrel"]
NoteIcon: monster
BestiaryType: humanoid (Chondathan human)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 253
---
# [Darathra Shendrel](2-Mechanics\CLI\bestiary\npc/darathra-shendrel-skt.md)
*Source: Storm King's Thunder p. 253*  

As the Lord Protector of Triboar and a secret agent of the Harpers, Darathra has sworn an oath to defend the town. She takes her duty very seriously. In addition to her gear, Darathra has an unarmored warhorse named Buster.

Ideal:"Good people should be given every chance to prosper, free of tyranny."

Bond:"I'll lay down my life to protect Triboar and its citizens."

Flaw:"I refuse to back down. Push me, and I'll push back."

```statblock
"name": "Darathra Shendrel (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Chondathan human"
"alignment": "Lawful Good"
"ac": !!int "14"
"ac_class": "[breastplate](/2-Mechanics/CLI/items/breastplate.md)"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "16"
- !!int "11"
- !!int "14"
- !!int "11"
- !!int "11"
- !!int "15"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "4"
  "Investigation": !!int "2"
  "Perception": !!int "2"
  "History": !!int "2"
  "Persuasion": !!int "4"
"senses": "passive Perception 12"
"languages": "Common"
"traits":
- "desc": "Darathra has advantage on saving throws against being [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
  "name": "Brave"
- "desc": "As the Lord Protector of Triboar and a secret agent of the Harpers, Darathra\
    \ has sworn an oath to defend the town. She takes her duty very seriously. In\
    \ addition to her gear, Darathra has an unarmored warhorse named Buster.\n\nIdeal:\
    \ \"Good people should be given every chance to prosper, free of tyranny.\"\n\n\
    Bond: \"I'll lay down my life to protect Triboar and its citizens.\"\n\nFlaw:\
    \ \"I refuse to back down. Push me, and I'll push back.\""
  "name": "Roleplaying Information"
"actions":
- "desc": "Darthra makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) slashing damage"
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. Hit:\
    \ 5 (1d10) piercing damage. Darathra carries twenty crossbow bolts."
  "name": "Heavy Crossbow"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Darathra%20Shendrel.webp"
```
^statblock

```encounter-table
name: Darathra Shendrel
creatures:
 - 1: Darathra Shendrel
```