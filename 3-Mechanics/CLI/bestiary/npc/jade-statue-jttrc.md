---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/jttrc
- monster/cr/10
- monster/size/large
- monster/type/construct
aliases: ["Jade Statue"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Journeys through the Radiant Citadel p. 195
---
# [Jade Statue](2-Mechanics\CLI\bestiary\npc/jade-statue-jttrc.md)
*Source: Journeys through the Radiant Citadel p. 195*  

```statblock
"name": "Jade Statue (JttRC)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "178"
"hit_dice": "17d10 + 85"
"stats":
- !!int "22"
- !!int "9"
- !!int "20"
- !!int "3"
- !!int "11"
- !!int "1"
"speed": "30 ft."
"damage_immunities": "poison; psychic; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't adamantine"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "10"
"traits":
- "desc": "The statue is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
- "desc": "The statue has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The statue's weapon attacks are magical."
  "name": "Magic Weapons"
"actions":
- "desc": "The statue makes two slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 19\
    \ (3d8 + 6) bludgeoning damage."
  "name": "Slam"
- "desc": "The statue targets one or more creatures it can see within 10 feet of it.\
    \ Each target must make a DC 17 Wisdom saving throw against this magic. On a failed\
    \ save, a target can't use reactions, its speed is halved, and it can't make more\
    \ than one attack on its turn. In addition, the target can take either an action\
    \ or a bonus action on its turn, not both. These effects last for 1 minute. A\
    \ target can repeat the saving throw at the end of each of its turns, ending the\
    \ effect on itself on a success."
  "name": "Slow (Recharge 5-6)"
"source":
- "JttRC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/JttRC/Jade%20Statue.webp"
```
^statblock

```encounter-table
name: Jade Statue
creatures:
 - 1: Jade Statue
```