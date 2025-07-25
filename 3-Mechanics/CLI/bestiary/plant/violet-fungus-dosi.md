---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dosi
- monster/cr/1-4
- monster/size/medium
- monster/type/plant
aliases: ["Violet Fungus"]
NoteIcon: monster
BestiaryType: plant
SourceType: Bestiary
BookSource: Dragons of Stormwreck Isle p. 48
---
# [Violet Fungus](2-Mechanics\CLI\bestiary\plant/violet-fungus-dosi.md)
*Source: Dragons of Stormwreck Isle p. 48*  

This purplish mushroom uses root-like feelers growing from its base to creep across cavern floors. The four stalks protruding from a violet fungi's central mass are used to lash out at prey, rotting flesh with the slightest touch. Any creature killed by a violet fungus decomposes rapidly. A new violet fungus sprouts from the moldering corpse, growing to full size in `2d6` days.

## Fungi

With its sky of jagged stone and perpetual night, the Underdark is home to all manner of fungi. Taking the place of plants in the subterranean realm, fungi are vital to the survival of many underground species, providing nourishment and shelter in the unforgiving darkness.

Fungi spawn in organic matter, then break that matter down to consume it, feeding on filth and corpses. As they mature, fungi eject spores that drift on the lightest breeze to spawn new fungi.

Not needing sunlight or warmth to grow, fungi thrive in every corner and crevice of the Underdark. Transformed by the magic that permeates that underground realm, Underdark fungi often develop potent defensive mechanisms or abilities of mimicry and attack. The largest specimens can spread to create vast subterranean forests in which countless creatures live and feed.

```statblock
"name": "Violet Fungus (DoSI)"
"size": "Medium"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "5"
"hp": !!int "18"
"hit_dice": "4d8"
"stats":
- !!int "3"
- !!int "1"
- !!int "10"
- !!int "1"
- !!int "3"
- !!int "1"
"speed": "5 ft."
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "blindsight 30 ft. (blind beyond this radius), passive Perception 6"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "If the violet fungus is motionless at the start of combat, it has advantage\
    \ on its initiative roll. Moreover, if a creature hasn't observed the fungus move\
    \ or act, that creature must succeed on a DC 18 Intelligence ([Investigation](/2-Mechanics/CLI/rules/skills.md#Investigation))\
    \ check to discern that the violet fungus isn't ordinary fungus."
  "name": "False Appearance"
"actions":
- "desc": "The fungus makes 1d4 Rotting Touch attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +2 to hit, reach 10 ft., one creature. Hit:\
    \ 4 (1d8) necrotic damage."
  "name": "Rotting Touch"
"source":
- "DoSI"
- "PaBTSO"
- "BMT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DoSI/Violet%20Fungus.webp"
```
^statblock

```encounter-table
name: Violet Fungus
creatures:
 - 1: Violet Fungus
```