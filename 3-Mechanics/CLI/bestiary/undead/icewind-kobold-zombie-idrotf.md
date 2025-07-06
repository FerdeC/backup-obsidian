---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/1-8
- monster/size/small
- monster/type/undead
aliases: ["Icewind Kobold Zombie"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 297
---
# [Icewind Kobold Zombie](2-Mechanics\CLI\bestiary\undead/icewind-kobold-zombie-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 297*  

The necromancer Vellynne Harpell has Icewind kobold guides in her employ, including a pair that died and were turned into zombies using [animate dead](/2-Mechanics/CLI/spells/animate-dead.md) spells. The cold climate helps to preserve their dead flesh.

```statblock
"name": "Icewind Kobold Zombie (IDRotF)"
"size": "Small"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "9"
"ac_class": "scraps of hide armor"
"hp": !!int "19"
"hit_dice": "3d6 + 9"
"stats":
- !!int "8"
- !!int "6"
- !!int "16"
- !!int "3"
- !!int "6"
- !!int "3"
"speed": "20 ft."
"saves":
  "Wisdom": !!int "0"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 8"
"languages": "understands Common and Draconic but can't speak"
"cr": "1/8"
"traits":
- "desc": "If damage reduces the zombie to 0 hit points, it must make a Constitution\
    \ saving throw with a DC of 5 + the damage taken, unless the damage is radiant\
    \ or from a critical hit. On a success, the zombie drops to 1 hit point instead."
  "name": "Undead Fortitude"
- "desc": "The zombie doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "Melee Weapon Attack: +1 to hit, reach 5 ft., one target. Hit: 2 (1d6\
    \ - 1) piercing damage."
  "name": "Javelin"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Icewind%20Kobold%20Zombie.webp"
```
^statblock

```encounter-table
name: Icewind Kobold Zombie
creatures:
 - 1: Icewind Kobold Zombie
```