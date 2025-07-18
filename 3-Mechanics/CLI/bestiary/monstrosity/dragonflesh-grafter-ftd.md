---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/ftd
- monster/cr/3
- monster/size/large
- monster/type/monstrosity
aliases: ["Dragonflesh Grafter"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Fizban's Treasury of Dragons p. 186
---
# [Dragonflesh Grafter](2-Mechanics\CLI\bestiary\monstrosity/dragonflesh-grafter-ftd.md)
*Source: Fizban's Treasury of Dragons p. 186*  

An ordinary dragonflesh grafter is a hulking fusion of draconic and bipedal characteristics, standing between 8 and 12 feet tall. As its original nature wanes, its draconic powers grow, giving it a thick layer of dragon scale armor that covers the grafted areas of its body. A dragonflesh grafter can belch forth a gout of corrosive acid in a mockery of dragon breath.

As a universal effect of their experimentation, grafters become obsessed with treasure. Their greed compels them to gather any gold or gems they can. After taking this treasure back to their lairs, they gaze for hours on end at their glittering trinkets and golden baubles.

## Dragonflesh Grafters

Dragonflesh grafters practice forbidden rituals and risky experiments on themselves, modifying their bodies and minds to emulate the dragons they revere. They collect dragon parts—scales, teeth, skin, flesh, wings, and bones—that they scavenge from around dragon lairs, take from dragon corpses, or buy from merchants and adventurers. They stitch on, implant, or ingest these dragon parts, attempting to incorporate them into their own bodies and absorb the latent magic that lingers in a draconic corpse.

While most would-be grafters wind up hideously scarred or dead, a few survive as wretched horrors. Their minds become twisted by magical malevolence, with only a shadow of their former selves remaining. In the most extreme cases, the resulting abomination holds no remnant of the person it once was and is utterly ruled by a dragon's lust for treasure.

```statblock
"name": "Dragonflesh Grafter (FTD)"
"size": "Large"
"type": "monstrosity"
"alignment": "typically  Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "52"
"hit_dice": "7d10 + 14"
"stats":
- !!int "16"
- !!int "11"
- !!int "14"
- !!int "10"
- !!int "10"
- !!int "6"
"speed": "30 ft."
"saves":
  "Strength": !!int "5"
  "Constitution": !!int "4"
"senses": "passive Perception 10"
"languages": "Common, Draconic"
"cr": "3"
"actions":
- "desc": "The grafter makes one Claw attack and one Greatclub attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 10 ft., one target. Hit: 7\
    \ (1d8 + 3) slashing damage plus 5 (1d10) poison damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +5 to hit, reach 10 ft., one target. Hit: 12\
    \ (2d8 + 3) bludgeoning damage."
  "name": "Greatclub"
- "desc": "The grafter retches forth a spray of acidic bile in a 30-foot cone. Each\
    \ creature in that area must make a DC 12 Dexterity saving throw, taking 14 (4d6)\
    \ acid damage on a failed save, or half as much damage on a successful one."
  "name": "Acid Retch (Recharge 5-6)"
"source":
- "FTD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/FTD/Dragonflesh%20Grafter.webp"
```
^statblock

```encounter-table
name: Dragonflesh Grafter
creatures:
 - 1: Dragonflesh Grafter
```