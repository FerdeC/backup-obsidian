---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/1-8
- monster/size/medium
- monster/type/construct
aliases: ["Clockwork Mule"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Storm King's Thunder p. 162
---
# [Clockwork Mule](2-Mechanics\CLI\bestiary\construct/clockwork-mule-skt.md)
*Source: Storm King's Thunder p. 162*  

```statblock
"name": "Clockwork Mule (SKT)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "14"
- !!int "10"
- !!int "13"
- !!int "2"
- !!int "10"
- !!int "5"
"speed": "40 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "passive Perception 10"
"languages": ""
"cr": "1/8"
"traits":
- "desc": "Repairing 1 hit point of damage to the clockwork mule takes 1 hour and\
    \ requires replacement parts, which can be bought in a large city for 20 gp. If\
    \ the mule drops to 0 hit points, it is destroyed and unrepairable."
  "name": "Maintainable"
- "desc": "The mule is considered to be a Large animal for the purpose of determining\
    \ its carrying capacity."
  "name": "Beast of Burden"
- "desc": "The mule has advantage on Strength and Dexterity saving throws made against\
    \ effects that would knock it [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Sure-Footed"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) bludgeoning damage."
  "name": "Hooves"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Clockwork%20Mule.webp"
```
^statblock

```encounter-table
name: Clockwork Mule
creatures:
 - 1: Clockwork Mule
```