---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/3
- monster/environment/underdark
- monster/environment/urban
- monster/size/large
- monster/type/elemental
aliases: ["Water Weird"]
NoteIcon: monster
BestiaryType: elemental
SourceType: Bestiary
BookSource: Monster Manual p. 299, Princes of the Apocalypse, Tales from the Yawning Portal, Mythic Odysseys of Theros, Icewind Dale: Rime of the Frostmaiden, Candlekeep Mysteries, Journeys through the Radiant Citadel, Dragonlance: Shadow of the Dragon Queen
---
# [Water Weird](2-Mechanics\CLI\bestiary\elemental/water-weird.md)
*Source: Monster Manual p. 299, Princes of the Apocalypse, Tales from the Yawning Portal, Mythic Odysseys of Theros, Icewind Dale: Rime of the Frostmaiden, Candlekeep Mysteries, Journeys through the Radiant Citadel, Dragonlance: Shadow of the Dragon Queen*  

A water weird is an elemental guardian bound to a specific water-filled location, such as a pool or fountain.

Invisible while immersed in water, its serpentine shape becomes clear only when it emerges to attack, using its coils to crush any creature other than its summoner and those its summoner declares as off limits. When slain, a water weird becomes an inanimate pool of water.

## Good and Evil Weirds

Like most elementals, a water weird has no concept of good or evil. However, a water weird bound to a sacred or befouled source of water begins to take on the nature of that site, becoming neutral good or neutral evil.

A neutral good water weird tries to frighten away interlopers rather than kill them, while a neutral evil water weird kills its victims for pleasure and might turn against its summoner. A water weird loses its evil alignment if its waters are cleansed with a [purify food and drink](/2-Mechanics/CLI/spells/purify-food-and-drink.md) spell.

## Elemental Nature

A water weird doesn't require air, food, drink, or sleep.

> [!quote]- A quote from X the Mystic's 2nd rule of dungeon survival  
> 
> Before you drink from a fountain or pool, toss a copper coin into it. It's a small price to pay for your life.


```statblock
"name": "Water Weird"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "58"
"hit_dice": "9d10 + 9"
"stats":
- !!int "17"
- !!int "16"
- !!int "13"
- !!int "11"
- !!int "10"
- !!int "10"
"speed": "0 ft., swim 60 ft."
"damage_resistances": "fire; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned), [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone), [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)"
"senses": "blindsight 30 ft., passive Perception 10"
"languages": "understands Aquan but doesn't speak"
"cr": "3"
"traits":
- "desc": "The water weird is [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ while fully immersed in water."
  "name": "Invisible in Water"
- "desc": "The water weird dies if it leaves the water to which it is bound or if\
    \ that water is destroyed."
  "name": "Water Bound"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 10 ft., one creature. Hit:\
    \ 13 (3d6 + 3) bludgeoning damage. If the target is Medium or smaller, it is\
    \ [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled) (escape DC 13) and\
    \ pulled 5 feet toward the water weird. Until this grapple ends, the target is\
    \ [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained), the water weird\
    \ tries to drown it, and the water weird can't constrict another target."
  "name": "Constrict"
"source":
- "MM"
- "PotA"
- "TftYP"
- "DIP"
- "SLW"
- "MOT"
- "IDRotF"
- "CM"
- "JttRC"
- "DSotDQ"
- "PaBTSO"
- "LK"
- "VEoR"
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Water%20Weird.webp"
```
^statblock

```encounter-table
name: Water Weird
creatures:
 - 1: Water Weird
```

## Environment

underdark, urban