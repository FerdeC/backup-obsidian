---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/gnoll
aliases: ["Gash"]
NoteIcon: monster
BestiaryType: humanoid (gnoll)
SourceType: Bestiary
BookSource: Out of the Abyss p. 181
---
# [Gash](2-Mechanics\CLI\bestiary\npc/gash-oota.md)
*Source: Out of the Abyss p. 181*  

```statblock
"name": "Gash (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "gnoll"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "11"
"hit_dice": "5d8"
"stats":
- !!int "14"
- !!int "12"
- !!int "11"
- !!int "6"
- !!int "10"
- !!int "7"
"speed": "25 ft."
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Gnoll"
"cr": "1/2"
"traits":
- "desc": "When Gash reduces a creature to 0 hit points with a melee attack on its\
    \ turn, Gash can take a bonus action to move up to half its speed and make a bite\
    \ attack."
  "name": "Rampage"
- "desc": "Gash has disadvantage on Wisdom checks and Wisdom saving throws because\
    \ of the physical and mental abuse he has suffered. A [lesser restoration](/2-Mechanics/CLI/spells/lesser-restoration.md)\
    \ spell rids him of these effects."
  "name": "Wretched"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 4\
    \ (1d4 + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Spear"
- "desc": "Ranged Weapon Attack: +3 to hit, range 150/600 ft., one target. Hit:\
    \ 5 (1d8 + 1) piercing damage."
  "name": "Longbow"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Gash.webp"
```
^statblock

```encounter-table
name: Gash
creatures:
 - 1: Gash
```