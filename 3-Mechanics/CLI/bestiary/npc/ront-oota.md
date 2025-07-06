---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/orc
aliases: ["Ront"]
NoteIcon: monster
BestiaryType: humanoid (orc)
SourceType: Bestiary
BookSource: Out of the Abyss p. 7
---
# [Ront](2-Mechanics\CLI\bestiary\npc/ront-oota.md)
*Source: Out of the Abyss p. 7*  

```statblock
"name": "Ront (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "orc"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "15"
"hit_dice": "2d8 + 6"
"stats":
- !!int "16"
- !!int "12"
- !!int "16"
- !!int "7"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "2"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Orc"
"cr": "1/2"
"traits":
- "desc": "As a bonus action, Ront can move up to its speed toward a hostile creature\
    \ that it can see."
  "name": "Aggressive"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 9 (1d12\
    \ + 3) slashing damage."
  "name": "Greataxe"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 6 (1d6 + 3) piercing damage."
  "name": "Javelin"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Ront.webp"
```
^statblock

```encounter-table
name: Ront
creatures:
 - 1: Ront
```