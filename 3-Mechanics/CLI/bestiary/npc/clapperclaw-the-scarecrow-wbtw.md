---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wbtw
- monster/cr/1-2
- monster/size/small
- monster/type/construct
aliases: ["Clapperclaw the Scarecrow"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: The Wild Beyond the Witchlight p. 78
---
# [Clapperclaw the Scarecrow](2-Mechanics\CLI\bestiary\npc/clapperclaw-the-scarecrow-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 78*  

Clapperclaw the scarecrow is 3 feet tall. Created by Granny Nightshade using a tormented child's soul she found in Gehenna, it ran away from home so that it wouldn't have to perform evil tasks for her. After fleeing Thither, Clapperclaw was waylaid by Agdon Longscarf and his harengon brigands, who stole its head, which the scarecrow describes as a most glorious stag skull. It desperately wants its head back, and it's a bit self-conscious about its replacement head: a hollow gourd that now sits askew on its shoulders. Eight copper coins are sealed inside the gourd, causing the head to rattle whenever Clapperclaw nods, turns, or shakes its head.

```statblock
"name": "Clapperclaw the Scarecrow (WBtW)"
"size": "Small"
"type": "construct"
"alignment": "Lawful Neutral"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "14"
"hit_dice": "4d6"
"stats":
- !!int "14"
- !!int "13"
- !!int "11"
- !!int "7"
- !!int "10"
- !!int "10"
"speed": "25 ft."
"skillsaves":
  "Stealth": !!int "3"
  "Survival": !!int "2"
"damage_vulnerabilities": "fire"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned),\
  \ [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Sylvan"
"cr": "1/2"
"traits":
- "desc": "Clapperclaw doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (2d4\
    \ + 2) slashing damage."
  "name": "Claws"
- "desc": "Clapperclaw stuffs straw or other dead plant matter into itself and regains\
    \ 2d4 + 2 hit points. Roll a d6; on a 1 or 2, Clapperclaw runs out of stuffing\
    \ and must spend 8 hours foraging for more before it can use this action again."
  "name": "Stuffing"
"bonus_actions":
- "desc": "Clapperclaw targets one creature it can see within 15 feet of it. The target\
    \ must succeed on a DC 11 Wisdom saving throw or be magically [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ until the end of Clapperclaw's next turn."
  "name": "Unsettling Presence (Recharge 6)"
"source":
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WBtW/Clapperclaw%20the%20Scarecrow.webp"
```
^statblock

```encounter-table
name: Clapperclaw the Scarecrow
creatures:
 - 1: Clapperclaw the Scarecrow
```