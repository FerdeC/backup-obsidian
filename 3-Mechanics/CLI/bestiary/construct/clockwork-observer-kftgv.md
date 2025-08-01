---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/0
- monster/size/tiny
- monster/type/construct
aliases: ["Clockwork Observer"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 85
---
# [Clockwork Observer](2-Mechanics\CLI\bestiary\construct/clockwork-observer-kftgv.md)
*Source: Keys from the Golden Vault p. 85*  

A clockwork observer serves as an aerial spy for its creator. It looks like a mechanical, grapefruit-sized orb suspended under softly humming propeller blades. Embedded in the orb are keenly perceptive crystal eyes that enable the observer to see in multiple directions at once. When it perceives something troubling, the observer sounds the alarm by emitting a shriek that can be heard within a range of 300 feet. The observer can also telepathically relay what it has discovered to its creator, provided the two are within 1 mile of each other.

```statblock
"name": "Clockwork Observer (KftGV)"
"size": "Tiny"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "7"
"hit_dice": "2d4 + 2"
"stats":
- !!int "1"
- !!int "16"
- !!int "13"
- !!int "3"
- !!int "15"
- !!int "1"
"speed": "0 ft., fly 30 ft. (hover)"
"skillsaves":
  "Perception": !!int "6"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "understands the languages of its creator but can't speak"
"cr": "0"
"traits":
- "desc": "The observer doesn't provoke opportunity attacks when it flies out of an\
    \ enemy's reach."
  "name": "Flyby"
- "desc": "While the observer is within 1 mile of its creator, it can magically convey\
    \ what it sees to its creator, and the two can communicate telepathically."
  "name": "Telepathic Bond"
- "desc": "The observer doesn't need air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The observer emits a mechanical shriek until the start of its next turn\
    \ or until it drops to 0 hit points. This shriek can be heard within a range of\
    \ 300 feet."
  "name": "Shriek"
"source":
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/KftGV/Clockwork%20Observer.webp"
```
^statblock

```encounter-table
name: Clockwork Observer
creatures:
 - 1: Clockwork Observer
```