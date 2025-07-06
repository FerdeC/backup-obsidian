---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Amarith Coppervein"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Out of the Abyss p. 142
---
# [Amarith Coppervein](2-Mechanics\CLI\bestiary\npc/amarith-coppervein-oota.md)
*Source: Out of the Abyss p. 142*  

```statblock
"name": "Amarith Coppervein (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Good"
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
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "any one language (usually Common), Dwarvish"
"cr": "3"
"traits":
- "desc": "Amarith"
  "name": "Dwarven Resilience"
"actions":
- "desc": "Amarith makes two longsword attacks. If it has a shortsword drawn, it can\
    \ also make a shortsword attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) bludgeoning damage, or 8 (1d10 + 3) bludgeoning damage if used with\
    \ two hands."
  "name": "Warhammer"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +3 to hit, range 100/400 ft., one target. Hit:\
    \ 6 (1d10 + 1) piercing damage."
  "name": "Heavy Crossbow"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Amarith%20Coppervein.webp"
```
^statblock

```encounter-table
name: Amarith Coppervein
creatures:
 - 1: Amarith Coppervein
```