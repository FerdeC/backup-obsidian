---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/sahuagin
aliases: ["Sahuagin Coral Smasher"]
NoteIcon: monster
BestiaryType: humanoid (sahuagin)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 249
---
# [Sahuagin Coral Smasher](2-Mechanics\CLI\bestiary\humanoid/sahuagin-coral-smasher-gos.md)
*Source: Ghosts of Saltmarsh p. 249*  

Employed as frontline brutes in The Final Enemy, coral smashers are drawn from the ranks of the strongest sahuagin warriors. Their physical strength overcomes the resistance of the water as they swing their hammers at structures and foes with equal zeal.

```statblock
"name": "Sahuagin Coral Smasher (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "sahuagin"
"alignment": "Lawful Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "16"
- !!int "12"
- !!int "12"
- !!int "12"
- !!int "13"
- !!int "9"
"speed": "30 ft., swim 40 ft."
"skillsaves":
  "Perception": !!int "5"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": "Sahuagin"
"cr": "1"
"traits":
- "desc": "The coral smasher has advantage on melee attack rolls against any creature\
    \ that doesn't have all its hit points."
  "name": "Blood Frenzy"
- "desc": "The coral smasher can breathe air and water, but it needs to be submerged\
    \ at least once every 4 hours to avoid suffocating."
  "name": "Limited Amphibiousness"
- "desc": "The coral smasher can magically command any shark within 120 feet of it,\
    \ using a limited telepathy."
  "name": "Shark Telepathy"
- "desc": "The coral smasher deals double damage to objects and structures."
  "name": "Siege Monster"
"actions":
- "desc": "The coral smasher makes two attacks with its warhammer, or one attack with\
    \ its bite and one with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) bludgeoning damage."
  "name": "Warhammer"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
    \ + 3) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
    \ + 3) slashing damage."
  "name": "Claws"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Sahuagin%20Coral%20Smasher.webp"
```
^statblock

```encounter-table
name: Sahuagin Coral Smasher
creatures:
 - 1: Sahuagin Coral Smasher
```