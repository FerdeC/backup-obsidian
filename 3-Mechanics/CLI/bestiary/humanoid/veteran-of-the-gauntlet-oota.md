---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Veteran of the Gauntlet"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Out of the Abyss p. 130
---
# [Veteran of the Gauntlet](2-Mechanics\CLI\bestiary\humanoid/veteran-of-the-gauntlet-oota.md)
*Source: Out of the Abyss p. 130*  

```statblock
"name": "Veteran of the Gauntlet (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Good"
"ac": !!int "17"
"ac_class": "[splint armor](/2-Mechanics/CLI/items/splint-armor.md)"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"stats":
- !!int "16"
- !!int "13"
- !!int "14"
- !!int "10"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "5"
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "Common, Dwarvish"
"cr": "3"
"actions":
- "desc": "The veteran makes two longsword attacks. If it has a shortsword drawn,\
    \ it can also make a shortsword attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands."
  "name": "Longsword"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +3 to hit, range 100/400 ft., one target. Hit:\
    \ 6 (1d10 + 1) piercing damage."
  "name": "Heavy Crossbow"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Veteran%20of%20the%20Gauntlet.webp"
```
^statblock

```encounter-table
name: Veteran of the Gauntlet
creatures:
 - 1: Veteran of the Gauntlet
```