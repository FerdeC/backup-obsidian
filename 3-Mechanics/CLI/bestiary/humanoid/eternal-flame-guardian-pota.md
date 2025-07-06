---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Eternal Flame Guardian"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 200
---
# [Eternal Flame Guardian](2-Mechanics\CLI\bestiary\humanoid/eternal-flame-guardian-pota.md)
*Source: Princes of the Apocalypse p. 200*  

Eternal Flame guardians are dullards fascinated by the power of fire and eager to show the cult's enemies firsthand what it feels like to burn. They light things aflame to honor elemental fire and just for entertainment, but they don't always think ahead about what else nearby might catch fire.

```statblock
"name": "Eternal Flame Guardian (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"ac_class": "[breastplate](/2-Mechanics/CLI/items/breastplate.md), [shield](/2-Mechanics/CLI/items/shield.md);\
  \ 15 while using a crossbow"
"hp": !!int "45"
"hit_dice": "7d8 + 14"
"stats":
- !!int "15"
- !!int "13"
- !!int "14"
- !!int "8"
- !!int "11"
- !!int "13"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "3"
  "Perception": !!int "2"
"damage_resistances": "fire"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "2"
"traits":
- "desc": "As a bonus action, the guard can wreath one melee weapon it is wielding\
    \ in flame. The guard is unharmed by this fire, which lasts until the end of the\
    \ guard's next turn. While wreathed in flame, the weapon deals an extra 3 (1d6)\
    \ fire damage on a hit."
  "name": "Flaming Weapon (Recharges after a Short or Long Rest)"
"actions":
- "desc": "The guard makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) slashing damage."
  "name": "Longsword"
- "desc": "Ranged Weapon Attack: +3 to hit, range 100/400 ft., one target. Hit:\
    \ 6 (1d10 + 1) piercing damage."
  "name": "Heavy Crossbow"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Eternal%20Flame%20Guardian.webp"
```
^statblock

```encounter-table
name: Eternal Flame Guardian
creatures:
 - 1: Eternal Flame Guardian
```