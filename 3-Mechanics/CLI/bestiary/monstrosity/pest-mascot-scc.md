---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/scc
- monster/cr/1-4
- monster/size/tiny
- monster/type/monstrosity
aliases: ["Pest Mascot"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Strixhaven: A Curriculum of Chaos p. 203
---
# [Pest Mascot](2-Mechanics\CLI\bestiary\monstrosity/pest-mascot-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 203*  

Grumpy, spiky, and generally irritating, pest mascots inhabit the muggy bayou of Sedgemoor. However, these ferret-sized swamp creatures hold deep wells of life essence, making them convenient fuel sources for the magic of Witherbloom mages. As such, many Witherbloom students have adopted pests from the bayou as pets, and pests, in all their spiny glory, have become the mascots of the college.

```statblock
"name": "Pest Mascot (SCC)"
"size": "Tiny"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "22"
"hit_dice": "4d4 + 12"
"stats":
- !!int "11"
- !!int "14"
- !!int "17"
- !!int "5"
- !!int "13"
- !!int "4"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The pest regains 5 hit points at the start of its turn if it has at least\
    \ 1 hit point. If it takes fire damage, this trait doesn't function at the start\
    \ of the pest's next turn."
  "name": "Regeneration"
- "desc": "At the start of each of its turns, the pest deals 2 (1d4) piercing damage\
    \ to any creature grappling it or that it is grappling."
  "name": "Spiny Hide"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage."
  "name": "Bite"
"source":
- "SCC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SCC/Pest%20Mascot.webp"
```
^statblock

```encounter-table
name: Pest Mascot
creatures:
 - 1: Pest Mascot
```