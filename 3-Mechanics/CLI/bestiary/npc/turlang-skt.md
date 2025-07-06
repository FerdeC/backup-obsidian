---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/9
- monster/size/huge
- monster/type/plant
aliases: ["Turlang"]
NoteIcon: monster
BestiaryType: plant
SourceType: Bestiary
BookSource: Storm King's Thunder p. 107
---
# [Turlang](2-Mechanics\CLI\bestiary\npc/turlang-skt.md)
*Source: Storm King's Thunder p. 107*  

```statblock
"name": "Turlang (SKT)"
"size": "Huge"
"type": "plant"
"alignment": "Chaotic Good"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "200"
"hit_dice": "12d12 + 60"
"stats":
- !!int "23"
- !!int "8"
- !!int "21"
- !!int "12"
- !!int "16"
- !!int "12"
"speed": "30 ft."
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing"
"senses": "passive Perception 13"
"languages": "Common, Druidic, Elvish, Sylvan"
"cr": "9"
"traits":
- "desc": "Turlang casts one of the following spells, requiring no material spell\
    \ components and using Wisdom as the spellcasting ability (spell save DC 15):\n\
    \nAt will: [druidcraft](/2-Mechanics/CLI/spells/druidcraft.md), [guidance](/2-Mechanics/CLI/spells/guidance.md),\
    \ [resistance](/2-Mechanics/CLI/spells/resistance.md), [speak with plants](/2-Mechanics/CLI/spells/speak-with-plants.md)\n\
    \n1/day each: [commune with nature](/2-Mechanics/CLI/spells/commune-with-nature.md)\
    \ (cast as 1 action), [conjure woodland beings](/2-Mechanics/CLI/spells/conjure-woodland-beings.md),\
    \ [hallucinatory terrain](/2-Mechanics/CLI/spells/hallucinatory-terrain.md) (cast\
    \ as 1 action)\n\n2/day each: [animal messenger](/2-Mechanics/CLI/spells/animal-messenger.md),\
    \ [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [entangle](/2-Mechanics/CLI/spells/entangle.md),\
    \ [goodberry](/2-Mechanics/CLI/spells/goodberry.md), [gust of wind](/2-Mechanics/CLI/spells/gust-of-wind.md),\
    \ [pass without trace](/2-Mechanics/CLI/spells/pass-without-trace.md), [speak\
    \ with animals](/2-Mechanics/CLI/spells/speak-with-animals.md)"
  "name": "Spellcasting"
- "desc": "While Turlang remains motionless, it is indistinguishable from a normal\
    \ tree."
  "name": "False Appearance"
- "desc": "The treant deals double damage to objects and structures."
  "name": "Siege Monster"
"actions":
- "desc": "The treant makes two slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 16\
    \ (3d6 + 6) bludgeoning damage."
  "name": "Slam"
- "desc": "Ranged Weapon Attack: +10 to hit, range 60/180 ft., one target. Hit:\
    \ 28 (4d10 + 6) bludgeoning damage."
  "name": "Rock"
- "desc": "The treant magically animates one or two trees it can see within 60 feet\
    \ of it. These trees have the same statistics as a [treant](/2-Mechanics/CLI/bestiary/plant/treant.md),\
    \ except they have Intelligence and Charisma scores of 1, they can't speak, and\
    \ they have only the Slam action option. An animated tree acts as an ally of Turlang.\
    \ The tree remains animate for 1 day or until it dies; until Turlang dies or is\
    \ more than 120 feet from the tree; or until Turlang takes a bonus action to turn\
    \ it back into an inanimate tree. The tree then takes root if possible."
  "name": "Animate Trees (1/Day)"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Turlang.webp"
```
^statblock

```encounter-table
name: Turlang
creatures:
 - 1: Turlang
```