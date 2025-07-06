---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/ftd
- monster/cr/7
- monster/size/medium
- monster/type/humanoid
aliases: ["Dragonborn of Tiamat"]
NoteIcon: monster
BestiaryType: humanoid
SourceType: Bestiary
BookSource: Fizban's Treasury of Dragons p. 185
---
# [Dragonborn of Tiamat](2-Mechanics\CLI\bestiary\humanoid/dragonborn-of-tiamat-ftd.md)
*Source: Fizban's Treasury of Dragons p. 185*  

Champions of the dragon queen are often called Talons of Tiamat. They work tirelessly to free their master from her imprisonment in Avernus, and Tiamat grants these pawns immense strength and a devastating breath weapon. Champions of Tiamat are sometimes associated with the Cult of the Dragon (described in chapter 3).

## Dragonborn Champions

The connection between dragonborn and their draconic ancestors manifests in a variety of ways. Some dragonborn identify with a particular kind of dragon and attempt to emulate such dragons' attitudes and behavior. Others consider their draconic heritage—chromatic, metallic, or gem—something like a large extended family. But for dragonborn champions, this bond is spiritual as much as biological, and they devote themselves to their divine ancestor. Dragonborn champions advance the cause of their dragon god among draconic creatures and other folk alike.

```statblock
"name": "Dragonborn of Tiamat (FTD)"
"size": "Medium"
"type": "humanoid"
"alignment": "typically  Chaotic Evil"
"ac": !!int "18"
"ac_class": "[plate](/2-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "85"
"hit_dice": "10d8 + 40"
"stats":
- !!int "20"
- !!int "11"
- !!int "18"
- !!int "10"
- !!int "12"
- !!int "16"
"speed": "30 ft."
"saves":
  "Charisma": !!int "6"
  "Wisdom": !!int "4"
  "Strength": !!int "8"
  "Constitution": !!int "7"
"skillsaves":
  "Intimidation": !!int "6"
  "Athletics": !!int "8"
  "Perception": !!int "4"
"condition_immunities": "[frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "passive Perception 14"
"languages": "Common, Draconic"
"cr": "7"
"traits":
- "desc": "If the dragonborn fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (1/Day)"
"actions":
- "desc": "The dragonborn makes two Greataxe attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 11\
    \ (1d12 + 5) slashing damage plus 13 (3d8) necrotic damage."
  "name": "Greataxe"
- "desc": "The dragonborn exhales shadowy fire in a 30-foot cone. Each creature in\
    \ that area must make a DC 15 Wisdom saving throw. On a failed save, the creature\
    \ takes 36 (8d8) necrotic damage and is [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ of the dragonborn for 1 minute. On a successful save, the creature takes half\
    \ as much damage and isn't [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened).\
    \ A [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened) creature can\
    \ repeat the saving throw at end of each of its turns, ending the effect on itself\
    \ on a success."
  "name": "Necrotic Breath (Recharge 6)"
"source":
- "FTD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/FTD/Dragonborn%20of%20Tiamat.webp"
```
^statblock

```encounter-table
name: Dragonborn of Tiamat
creatures:
 - 1: Dragonborn of Tiamat
```