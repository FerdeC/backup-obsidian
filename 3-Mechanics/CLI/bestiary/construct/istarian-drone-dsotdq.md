---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/6
- monster/size/medium
- monster/type/construct
aliases: ["Istarian Drone"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 202
---
# [Istarian Drone](2-Mechanics\CLI\bestiary\construct/istarian-drone-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 202*  

Istarian drones are ancient Constructs made of marble and gleaming metal inlaid with crystals that flash with sparks of electricity. Created to build the fantastic structures that once marked the glory of Istar, these drones resemble short, stout mantises. They have four scuttling insectile legs and barbed, scythe-shaped arms for carrying and placing building materials. The drones create a viscous gel that hardens into crystalline mortar, which they can repurpose to restrain attackers.

```statblock
"name": "Istarian Drone (DSotDQ)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "127"
"hit_dice": "15d8 + 60"
"stats":
- !!int "20"
- !!int "10"
- !!int "18"
- !!int "4"
- !!int "10"
- !!int "4"
"speed": "30 ft., climb 30 ft."
"damage_immunities": "lightning, poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 10"
"languages": "understands the languages spoken by its creator but can't speak"
"cr": "6"
"traits":
- "desc": "The drone can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
- "desc": "The drone doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The drone makes two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 9 (1d8\
    \ + 5) piercing damage plus 4 (1d8) lightning damage. If the target is a Medium\
    \ or smaller creature, it is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 15). The drone has two claws, each of which can grapple only one\
    \ target."
  "name": "Claw"
- "desc": "The drone spits crackling gel in a line 5 feet wide and 20 feet long. Each\
    \ creature in the line must make a DC 15 Dexterity saving throw. On a failed save,\
    \ the creature takes 14 (4d6) lightning damage and is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ by the gel, which hardens into crystal. The creature is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ until the crystal is destroyed. The crystal has AC 15, 15 hit points, immunity\
    \ to poison and psychic damage, and vulnerability to thunder damage. On a successful\
    \ save, the creature takes half as much damage and isn't [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)."
  "name": "Crystalline Spit (Recharge 5-6)"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Istarian%20Drone.webp"
```
^statblock

```encounter-table
name: Istarian Drone
creatures:
 - 1: Istarian Drone
```