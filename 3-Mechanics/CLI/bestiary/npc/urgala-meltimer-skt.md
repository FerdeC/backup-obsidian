---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/
- monster/size/medium
- monster/type/humanoid/turami-human
aliases: ["Urgala Meltimer"]
NoteIcon: monster
BestiaryType: humanoid (Turami human)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 254
---
# [Urgala Meltimer](2-Mechanics\CLI\bestiary\npc/urgala-meltimer-skt.md)
*Source: Storm King's Thunder p. 254*  

A retired adventurer, Urgala owns a respectable inn, the Northshield House, and she doesn't want to see it or her neighbors' homes destroyed. She has no tolerance for monsters or bullies.

Ideal:"We live in a violent world, and sometimes violence is necessary for survival."

Bond:"My home is my life. Threaten it, and I'll hurt you."

Flaw:"I know how treacherous and greedy adventurers can be. I don't trust them-any of them."

```statblock
"name": "Urgala Meltimer (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Turami human"
"alignment": "Lawful Good"
"ac": !!int "12"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"stats":
- !!int "16"
- !!int "13"
- !!int "14"
- !!int "12"
- !!int "14"
- !!int "13"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "3"
  "Athletics": !!int "5"
"senses": "passive Perception 12"
"languages": "Common, Giant"
"traits":
- "desc": "Any weapon attack that Urgala makes against a giant deals an extra 7 (2d6)\
    \ damage on a hit."
  "name": "Giant Slayer"
- "desc": "A retired adventurer, Urgala owns a respectable inn, the North shield House,\
    \ and she doesn't want to see it or her neighbors' homes destroyed. She has no\
    \ tolerance for monsters or bullies.\n\nIdeal: \"We live in a violent world, and\
    \ sometimes violence is necessary for survival.\"\n\nBond: \"My home is my life.\
    \ Threaten it, and I'll hurt you.\"\n\nFlaw: \"I know how treacherous and greedy\
    \ adventurers can be. I don't trust them—any of them.\""
  "name": "Roleplaying Information"
"actions":
- "desc": "Urgala makes two attacks with her morningstar or her shortbow."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) piercing damage."
  "name": "Morningstar"
- "desc": "Ranged Weapon Attack: +3 to hit, range 80/320 ft., one target. Hit:\
    \ 5 (1d6 + 1) piercing damage. Urgala carries a quiver of twenty arrows."
  "name": "Shortbow"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Urgala%20Meltimer.webp"
```
^statblock

```encounter-table
name: Urgala Meltimer
creatures:
 - 1: Urgala Meltimer
```