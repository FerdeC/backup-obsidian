---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/
- monster/size/medium
- monster/type/humanoid/turami-human
aliases: ["Markham Southwell"]
NoteIcon: monster
BestiaryType: humanoid (Turami human)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 248
---
# [Markham Southwell](2-Mechanics\CLI\bestiary\npc/markham-southwell-skt.md)
*Source: Storm King's Thunder p. 248*  

Sheriff Markham of Bryn Shander is a brawny, likable man of few words. Nothing is more important to him than protecting Icewind Dale. He judges others by their actions, not their words.

Ideal:"All people deserve to be treated with dignity."

Bond:"Duvessa is a natural leader, but she needs help. That's my job."

Flaw:"I bury my emotions and have no interest in small talk."

```statblock
"name": "Markham Southwell (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Turami human"
"alignment": "Lawful Good"
"ac": !!int "17"
"ac_class": "[splint armor](/2-Mechanics/CLI/items/splint-armor.md)"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"stats":
- !!int "15"
- !!int "13"
- !!int "14"
- !!int "11"
- !!int "16"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "5"
  "Survival": !!int "5"
"senses": "passive Perception 16"
"languages": "Common"
"traits":
- "desc": "Sheriff Markham of Bryn Shander is a brawny, likable man of few words.\
    \ Nothing is more important to him than protecting Icewind Dale. He judges others\
    \ by their actions, not their words.\n\nIdeal: \"All people deserve to be treated\
    \ with dignity.\"\n\nBond: \"Duvessa is a natural leader, but she needs help.\
    \ That's my job.\"\n\nFlaw: \"I bury my emotions and have no interest in small\
    \ talk.\""
  "name": "Roleplaying Information"
"actions":
- "desc": "Markham makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with two hands."
  "name": "Longsword"
- "desc": "Ranged Weapon Attack: +3 to hit, range 100/400 ft., one target. Hit:\
    \ 6 (1d10 + 1) piercing damage. Markham carries twenty crossbow bolts."
  "name": "Heavy Crossbow"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Markham%20Southwell.webp"
```
^statblock

```encounter-table
name: Markham Southwell
creatures:
 - 1: Markham Southwell
```