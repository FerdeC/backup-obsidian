---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/rot
- monster/cr/6
- monster/size/large
- monster/type/monstrosity
aliases: ["Animated Tile Chimera"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: The Rise of Tiamat p. 42
---
# [Animated Tile Chimera](2-Mechanics\CLI\bestiary\monstrosity/animated-tile-chimera-rot.md)
*Source: The Rise of Tiamat p. 42*  

```statblock
"name": "Animated Tile Chimera (RoT)"
"size": "Large"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "114"
"hit_dice": "12d10 + 48"
"stats":
- !!int "19"
- !!int "11"
- !!int "19"
- !!int "3"
- !!int "14"
- !!int "10"
"speed": "30 ft., fly 60 ft."
"skillsaves":
  "Perception": !!int "8"
"damage_resistances": "piercing"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 18"
"languages": "understands Draconic but can't speak"
"cr": "6"
"traits":
- "desc": "If destroyed, the tile creature regains all its hit points and becomes\
    \ active again in 24 hours unless at least half its tiles are collected and kept\
    \ separate from the rest of the creature's tiles."
  "name": "Rejuvenation"
"actions":
- "desc": "The chimera makes three attacks: one with its bite, one with its horns,\
    \ and one with its claws. When its fire breath is available, it can use the breath\
    \ in place of its bite or horns."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 10\
    \ (1d12 + 4) bludgeoning damage."
  "name": "Horns"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) slashing damage."
  "name": "Claws"
- "desc": "The dragon head exhales fire in a 15-foot cone. Each creature in that area\
    \ must make a DC 15 Dexterity saving throw, taking 31 (7d8) fire damage on a\
    \ failed save, or half as much damage on a successful one."
  "name": "Fire Breath (Recharge 5-6)"
"reactions":
- "desc": "When targeted by a melee attack, the tile creature can take a reaction\
    \ to turn its narrowest aspect toward the attacker. The attacker has disadvantage\
    \ on the attack roll."
  "name": "Narrow Dodge"
"source":
- "RoT"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/RoT/Animated%20Tile%20Chimera.webp"
```
^statblock

```encounter-table
name: Animated Tile Chimera
creatures:
 - 1: Animated Tile Chimera
```