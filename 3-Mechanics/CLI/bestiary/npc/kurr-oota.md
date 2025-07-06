---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/4
- monster/size/medium
- monster/type/fiend/gnoll
aliases: ["Kurr"]
NoteIcon: monster
BestiaryType: fiend (gnoll)
SourceType: Bestiary
BookSource: Out of the Abyss p. 179
---
# [Kurr](2-Mechanics\CLI\bestiary\npc/kurr-oota.md)
*Source: Out of the Abyss p. 179*  

```statblock
"name": "Kurr (OotA)"
"size": "Medium"
"type": "fiend"
"subtype": "gnoll"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "17"
- !!int "15"
- !!int "15"
- !!int "10"
- !!int "11"
- !!int "13"
"speed": "30 ft."
"saves":
  "Charisma": !!int "3"
  "Wisdom": !!int "2"
  "Constitution": !!int "4"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Abyssal, Gnoll"
"cr": "4"
"traits":
- "desc": "When Kurr reduces a creature to 0 hit points with a melee attack on its\
    \ turn, Kurr can take a bonus action to move up to half its speed and make a bite\
    \ attack."
  "name": "Rampage"
"actions":
- "desc": "Kurr makes three attacks: one with its bite and two with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 6\
    \ (1d6 + 3) piercing damage, and the target must succeed on a DC 12 Constitution\
    \ saving throw or take 7 (2d6) poison damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage."
  "name": "Claw"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Kurr.webp"
```
^statblock

```encounter-table
name: Kurr
creatures:
 - 1: Kurr
```