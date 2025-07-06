---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/1-4
- monster/size/tiny
- monster/type/fiend/demon
aliases: ["Abyssal Chicken"]
NoteIcon: monster
BestiaryType: fiend (demon)
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 97
---
# [Abyssal Chicken](2-Mechanics\CLI\bestiary\fiend/abyssal-chicken-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 97*  

Abyssal chickens are carnivorous, temperamental, tasty bottom-feeders native to the Abyss. They beat their leathery wings to scare predators and to help them run faster, and they taste like fatty chicken.

With your permission, a character who casts the [find familiar](/2-Mechanics/CLI/spells/find-familiar.md) spell can henceforth choose to conjure an abyssal chicken instead of a raven.

```statblock
"name": "Abyssal Chicken (BGDIA)"
"size": "Tiny"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "10"
"hit_dice": "3d4 + 3"
"stats":
- !!int "6"
- !!int "14"
- !!int "13"
- !!int "4"
- !!int "9"
- !!int "5"
"speed": "30 ft., fly 30 ft. (see bad flier below)"
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "poison"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 30 ft. (blind beyond this radius), passive Perception 9"
"languages": "understands Abyssal but can't speak"
"cr": "1/4"
"traits":
- "desc": "The abyssal chicken falls at the end of a turn if it's airborne and the\
    \ only thing holding it aloft is its flying speed."
  "name": "Bad Flier"
"actions":
- "desc": "The abyssal chicken makes two attacks: one with its bite and one with its\
    \ claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 4\
    \ (1d4 + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) slashing damage."
  "name": "Claws"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Abyssal%20Chicken.webp"
```
^statblock

```encounter-table
name: Abyssal Chicken
creatures:
 - 1: Abyssal Chicken
```