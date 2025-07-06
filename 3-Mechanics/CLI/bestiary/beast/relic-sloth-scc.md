---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/scc
- monster/cr/2
- monster/size/huge
- monster/type/beast
aliases: ["Relic Sloth"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Strixhaven: A Curriculum of Chaos p. 210
---
# [Relic Sloth](2-Mechanics\CLI\bestiary\beast/relic-sloth-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 210*  

For long expeditions, Lorehold mages often employ relic sloths to haul adventuring equipment and excavated artifacts—so long as their study isn't in any particular hurry. Relic sloths travel at an excruciatingly slow pace, deliberating every step and moving only when necessary. But this caution makes these hulking creatures perfect for traversing treacherous and crumbling ruins, where other beasts of burden would falter. The distinctive sickle-shaped claws on a relic sloth's forelimbs are primarily used for climbing, though they can fend off a hungry predator in a pinch.

```statblock
"name": "Relic Sloth (SCC)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "76"
"hit_dice": "8d12 + 24"
"stats":
- !!int "20"
- !!int "9"
- !!int "17"
- !!int "2"
- !!int "12"
- !!int "8"
"speed": "20 ft., climb 20 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "2"
"actions":
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 14\
    \ (2d8 + 5) slashing damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 15). The relic sloth can grapple no more than two targets at a time."
  "name": "Claws"
"reactions":
- "desc": "When the relic sloth is subjected to an effect that would move it out of\
    \ its current space or knock it [prone](/2-Mechanics/CLI/rules/conditions.md#prone),\
    \ it is neither moved nor knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Slow but Sturdy"
"source":
- "SCC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SCC/Relic%20Sloth.webp"
```
^statblock

```encounter-table
name: Relic Sloth
creatures:
 - 1: Relic Sloth
```