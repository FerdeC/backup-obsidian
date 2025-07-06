---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/scc
- monster/cr/1-4
- monster/size/small
- monster/type/construct
aliases: ["Fractal Mascot"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Strixhaven: A Curriculum of Chaos p. 192
---
# [Fractal Mascot](2-Mechanics\CLI\bestiary\construct/fractal-mascot-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 192*  

To an untrained eye, a fractal mascot looks like a creature made from facets of hard light. But arithmancers know that these fractals are actually living equations: artificial life forms created by extrapolating magic from the mathematical patterns in nature.

Because of their arithmetic basis, fractal mascots can alter both their size and density. Quandrix College has adopted the fractal as its mascot, and many a Quandrix student can be found playing fetch with a fractal companion in between lessons.

```statblock
"name": "Fractal Mascot (SCC)"
"size": "Small"
"type": "construct"
"alignment": "typically  Neutral"
"ac": !!int "12"
"hp": !!int "27"
"hit_dice": "6d6 + 6"
"stats":
- !!int "12"
- !!int "14"
- !!int "13"
- !!int "7"
- !!int "10"
- !!int "5"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "1/4"
"traits":
- "desc": "The fractal can move through creatures and objects as if they were difficult\
    \ terrain. It takes 5 (1d10) force damage if it ends its turn inside an object."
  "name": "Relative Density"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d4\
    \ + 1) force damage, or 6 (2d4 + 1) force damage if the fractal is Medium or\
    \ bigger."
  "name": "Quantum Strike"
"bonus_actions":
- "desc": "The fractal's size increases by one category. While the fractal is Medium\
    \ or bigger, it makes Strength checks and Strength saving throws with advantage.\
    \ The fractal can become no larger than Huge via this bonus action."
  "name": "Augment"
- "desc": "The fractal's size decreases by one category. While the fractal is Tiny,\
    \ it makes attack rolls, Dexterity checks, and Dexterity saving throws with advantage.\
    \ The fractal can become no smaller than 1 foot in height via this bonus action."
  "name": "Diminish"
"source":
- "SCC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SCC/Fractal%20Mascot.webp"
```
^statblock

```encounter-table
name: Fractal Mascot
creatures:
 - 1: Fractal Mascot
```