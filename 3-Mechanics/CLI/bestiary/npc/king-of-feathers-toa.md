---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/8
- monster/size/huge
- monster/type/monstrosity
aliases: ["King of Feathers"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 106
---
# [King of Feathers](2-Mechanics\CLI\bestiary\npc/king-of-feathers-toa.md)
*Source: Tomb of Annihilation p. 106*  

The monstrous tyrannosaurus known as the King of Feathers is the undisputed lord of Omu. Most other dwellers of the Forbidden City live in fear of its thunderous approach and steer well clear of the amphitheater, its lair.

```statblock
"name": "King of Feathers (ToA)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "200"
"hit_dice": "19d12 + 52"
"stats":
- !!int "25"
- !!int "10"
- !!int "19"
- !!int "2"
- !!int "12"
- !!int "9"
"speed": "50 ft."
"skillsaves":
  "Perception": !!int "4"
"senses": "passive Perception 14"
"languages": ""
"cr": "8"
"traits":
- "desc": "The King of Feathers's innate spellcasting ability is Wisdom. It can innately\
    \ cast the following spell, requiring no material components:\n\nAt will:\
    \ [misty step](/2-Mechanics/CLI/spells/misty-step.md)"
  "name": "Innate Spellcasting"
- "desc": "The King of Feathers can see [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ creatures and objects as if they were visible."
  "name": "Detect Invisibility"
- "desc": "If the King of Feathers fails a saving throw, it can choose to succeed\
    \ instead."
  "name": "Legendary Resistance (3/Day)"
"actions":
- "desc": "The King of Feathers makes two attacks: one with its bite and one with\
    \ its tail. It can't make both attacks against the same target."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 33\
    \ (4d12 + 7) piercing damage. If the target is a Medium or smaller creature,\
    \ it is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled) (escape DC 17).\
    \ Until this grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and the tyrannosaurus can't bite another target."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 20\
    \ (3d8 + 7) bludgeoning damage."
  "name": "Tail"
- "desc": "The King of Feathers exhales a [swarm of insects (wasps)](/2-Mechanics/CLI/bestiary/beast/swarm-of-wasps.md)\
    \ that forms in a space within 20 feet of it. The swarm acts as an ally of the\
    \ King of Feathers and takes its turn immediately after it. The swarm disperses\
    \ after 1 minute. It can't use the Summon Swarm action while it is grappling a\
    \ creature with its jaws."
  "name": "Summon Swarm (Recharge 5-6)"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/King%20of%20Feathers.webp"
```
^statblock

```encounter-table
name: King of Feathers
creatures:
 - 1: King of Feathers
```