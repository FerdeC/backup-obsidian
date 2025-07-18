---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/dwarf
aliases: ["Hew Hackinstone"]
NoteIcon: monster
BestiaryType: humanoid (dwarf)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 33
---
# [Hew Hackinstone](2-Mechanics\CLI\bestiary\npc/hew-hackinstone-toa.md)
*Source: Tomb of Annihilation p. 33*  

Hailing from uncivilized lands, unpredictable berserkers come together in war parties and seek conflict wherever they can find it.

## Biography

Three years ago, Hew was part of a dwarven expedition seeking to reopen Wyrmheart Mine. The expedition encountered Tinder the red dragon. Hew alone escaped, and only after the dragon bit off his left arm. Hew wants to return to the mine and slay the dragon, but he needs a band of stout-hearted adventurers to help him. If the characters hire him as a guide, Hew says he can lead them wherever they want, but he'll only take them to Wyrmheart Mine.

```statblock
"name": "Hew Hackinstone (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"stats":
- !!int "16"
- !!int "12"
- !!int "17"
- !!int "9"
- !!int "11"
- !!int "9"
"speed": "30 ft."
"skillsaves":
  "Survival": !!int "4"
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "2"
"traits":
- "desc": "Hew has resistance to poison damage and advantage on saving throws against\
    \ being [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)."
  "name": "Dwarven Resilience"
- "desc": "At the start of his turn, Hew can gain advantage on all melee weapon attack\
    \ rolls during that turn, but attack rolls against him have advantage until the\
    \ start of his next turn."
  "name": "Reckless"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage."
  "name": "Battleaxe"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Hew%20Hackinstone.webp"
```
^statblock

```encounter-table
name: Hew Hackinstone
creatures:
 - 1: Hew Hackinstone
```