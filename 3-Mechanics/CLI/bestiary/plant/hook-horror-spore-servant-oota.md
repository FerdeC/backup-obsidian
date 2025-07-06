---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/3
- monster/size/medium
- monster/type/plant
aliases: ["Hook Horror Spore Servant"]
NoteIcon: monster
BestiaryType: plant
SourceType: Bestiary
BookSource: Out of the Abyss p. 68
---
# [Hook Horror Spore Servant](2-Mechanics\CLI\bestiary\plant/hook-horror-spore-servant-oota.md)
*Source: Out of the Abyss p. 68*  

```statblock
"name": "Hook Horror Spore Servant (OotA)"
"size": "Medium"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "75"
"hit_dice": "10d10 + 10"
"stats":
- !!int "18"
- !!int "10"
- !!int "15"
- !!int "2"
- !!int "6"
- !!int "1"
"speed": "20 ft., climb 20 ft."
"damage_resistances": "poison"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed)"
"senses": "blindsight 30 ft. (blind beyond this radius), passive Perception 8"
"languages": ""
"cr": "3"
"actions":
- "desc": "The spore servant makes two hook attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 11\
    \ (2d6 + 4) piercing damage."
  "name": "Hook"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Hook%20Horror%20Spore%20Servant.webp"
```
^statblock

```encounter-table
name: Hook Horror Spore Servant
creatures:
 - 1: Hook Horror Spore Servant
```