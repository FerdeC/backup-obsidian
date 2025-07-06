---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/rot
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Mend-nets"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: The Rise of Tiamat p. 32
---
# [Mend-nets](2-Mechanics\CLI\bestiary\npc/mend-nets-rot.md)
*Source: The Rise of Tiamat p. 32*  

```statblock
"name": "Mend-nets (RoT)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "13"
- !!int "11"
- !!int "12"
- !!int "8"
- !!int "11"
- !!int "8"
"speed": "30 ft."
"senses": "passive Perception 10"
"languages": "any one language"
"cr": "1/8"
"traits":
- "desc": "The warrior has advantage on an attack roll against a creature if at least\
    \ one of the warrior's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d6 + 1) piercing damage, or 5 (1d8 + 1) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Spear"
"source":
- "RoT"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/RoT/Mend-nets.webp"
```
^statblock

```encounter-table
name: Mend-nets
creatures:
 - 1: Mend-nets
```