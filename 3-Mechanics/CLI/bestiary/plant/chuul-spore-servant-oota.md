---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/4
- monster/size/large
- monster/type/plant
aliases: ["Chuul Spore Servant"]
NoteIcon: monster
BestiaryType: plant
SourceType: Bestiary
BookSource: Out of the Abyss p. 228
---
# [Chuul Spore Servant](2-Mechanics\CLI\bestiary\plant/chuul-spore-servant-oota.md)
*Source: Out of the Abyss p. 228*  

```statblock
"name": "Chuul Spore Servant (OotA)"
"size": "Large"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "93"
"hit_dice": "11d10 + 33"
"stats":
- !!int "19"
- !!int "10"
- !!int "16"
- !!int "2"
- !!int "6"
- !!int "1"
"speed": "30 ft., swim 30 ft."
"damage_immunities": "poison"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 30 ft. (blind beyond this radius), passive Perception 8"
"languages": ""
"cr": "4"
"actions":
- "desc": "The spore servant makes two pincer attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 11\
    \ (2d6 + 4) bludgeoning damage. The target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (Escape DC 14) if it is a Large or smaller creature and the spore servant doesn't\
    \ have two other creatures [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)."
  "name": "Pincer"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Chuul%20Spore%20Servant.webp"
```
^statblock

```encounter-table
name: Chuul Spore Servant
creatures:
 - 1: Chuul Spore Servant
```