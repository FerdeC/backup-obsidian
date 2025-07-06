---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/2
- monster/size/large
- monster/type/construct
aliases: ["Maddgoth's Homunculus"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 96
---
# [Maddgoth's Homunculus](2-Mechanics\CLI\bestiary\npc/maddgoths-homunculus-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 96*  

```statblock
"name": "Maddgoth's Homunculus (WDMM)"
"size": "Large"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "55"
"hit_dice": "10d10"
"stats":
- !!int "15"
- !!int "15"
- !!int "11"
- !!int "10"
- !!int "10"
- !!int "7"
"speed": "20 ft., fly 40 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Abyssal, Common, Draconic, Gnomish but can't speak"
"cr": "2"
"traits":
- "desc": "While the homunculus is on the same plane of existence as its master, it\
    \ can magically convey what it senses to its master, and the two can communicate\
    \ telepathically."
  "name": "Telepathic Bond"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 2d6\
    \ + 2 piercing damage, and the target must succeed on a DC 10 Constitution saving\
    \ throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) for 1\
    \ minute. If the saving throw fails by 5 or more, the target is instead [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 5 (1d10) minutes and [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)\
    \ while [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) in this way."
  "name": "Bite"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Maddgoth%27s%20Homunculus.webp"
```
^statblock

```encounter-table
name: Maddgoth's Homunculus
creatures:
 - 1: Maddgoth's Homunculus
```