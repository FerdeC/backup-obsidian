---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Cudgel Ironsmile"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 58
---
# [Cudgel Ironsmile](2-Mechanics\CLI\bestiary\npc/cudgel-ironsmile-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 58*  

```statblock
"name": "Cudgel Ironsmile (DSotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral"
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
- "desc": "Cudgel"
  "name": "Dwarven Resilience"
"actions":
- "desc": "Cudgel makes two longsword attacks. If it has a shortsword drawn, it can\
    \ also make a shortsword attack."
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
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Cudgel%20Ironsmile.webp"
```
^statblock

```encounter-table
name: Cudgel Ironsmile
creatures:
 - 1: Cudgel Ironsmile
```