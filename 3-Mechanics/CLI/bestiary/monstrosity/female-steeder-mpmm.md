---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/1
- monster/environment/underdark
- monster/size/large
- monster/type/monstrosity
aliases: ["Female Steeder"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 231, Mordenkainen's Tome of Foes p. 238
---
# [Female Steeder](2-Mechanics\CLI\bestiary\monstrosity/female-steeder-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 231, Mordenkainen's Tome of Foes p. 238*  

## Steeders

> [!quote]- A quote from Mordenkainen  
> 
> Steeders resemble spiders as much as worgs resemble wolves. The creatures may appear similar, but steeders are more than mere vermin.

Giant hunting spiders, steeders prowl the depths of the Underdark. Female steeders grow larger and stronger than males, and the female often devours the male after breeding. Numerous Underdark folk domesticate steeders, particularly duergar (also in this book). Typically the females serve as steeds in battle, while the males are used as draft animals.

Steeders attempt to tear apart perceived threats—and consider even other steeders enemies. When they're put to work, their handlers must stable them separately from one another and place blinders on them to keep them from attacking each other.

Steeders are intelligent enough to learn simple hand signals and vocal commands, but even a domesticated steeder might turn against its handler. Training a steeder requires a rider to bond with it, a process that begins shortly after the steeder hatches. As it grows, its rider works with it to direct its predatory instincts.

Rather than spinning webs, steeders excrete a viscous substance from their legs. This goo allows them to creep along walls and ceilings and to grapple prey.

```statblock
"name": "Female Steeder (MPMM)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "30"
"hit_dice": "4d10 + 8"
"stats":
- !!int "15"
- !!int "16"
- !!int "14"
- !!int "2"
- !!int "10"
- !!int "3"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "4"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": ""
"cr": "1"
"traits":
- "desc": "The distance of the steeder's long jumps is tripled; every foot of its\
    \ walking speed that it spends on the jump allows it to move 3 feet."
  "name": "Extraordinary Leap"
- "desc": "The steeder can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) piercing damage plus 9 (2d8) poison damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one Medium or smaller\
    \ creature. Hit: The target is stuck to the steeder's leg and [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 12). The steeder can have only one creature [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ at a time."
  "name": "Sticky Leg"
"source":
- "MPMM"
- "MTF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPMM/Female%20Steeder.webp"
```
^statblock

```encounter-table
name: Female Steeder
creatures:
 - 1: Female Steeder
```

## Environment

underdark