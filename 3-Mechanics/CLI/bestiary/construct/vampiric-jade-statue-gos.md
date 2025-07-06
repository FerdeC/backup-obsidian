---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/8
- monster/size/large
- monster/type/construct
aliases: ["Vampiric Jade Statue"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 256
---
# [Vampiric Jade Statue](2-Mechanics\CLI\bestiary\construct/vampiric-jade-statue-gos.md)
*Source: Ghosts of Saltmarsh p. 256*  

A large, exquisitely carved jade statue of a vampire guards the tunnels in Isle of the Abbey, having been brought to life by dark magic. Its stone fangs draw blood that it then uses to work a curse on its victims.

```statblock
"name": "Vampiric Jade Statue (GoS)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "114"
"hit_dice": "12d10 + 48"
"stats":
- !!int "16"
- !!int "14"
- !!int "18"
- !!int "6"
- !!int "10"
- !!int "5"
"speed": "30 ft."
"damage_vulnerabilities": "force"
"damage_immunities": "lightning, poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "8"
"traits":
- "desc": "The statue is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
- "desc": "If the statue fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
"actions":
- "desc": "The statue makes three attacks: one with its bite and two with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) piercing damage. If the target is a creature, that creature becomes\
    \ cursed by the statue. The curse lasts for 10 minutes. While the creature is\
    \ cursed, the statue has advantage on all attacks against it."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) slashing damage."
  "name": "Claws"
"legendary_actions":
- "desc": "The statue makes one bite attack."
  "name": "Bite"
- "desc": "All creatures currently cursed by the statue and within 20 feet of it take\
    \ 5 necrotic damage."
  "name": "Blood Reaper"
- "desc": "The statue moves up to its speed without provoking opportunity attacks."
  "name": "Move"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Vampiric%20Jade%20Statue.webp"
```
^statblock

```encounter-table
name: Vampiric Jade Statue
creatures:
 - 1: Vampiric Jade Statue
```