---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mot
- monster/cr/15
- monster/size/huge
- monster/type/giant
aliases: ["Hundred-Handed One"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Mythic Odysseys of Theros p. 225
---
# [Hundred-Handed One](2-Mechanics\CLI\bestiary\giant/hundred-handed-one-mot.md)
*Source: Mythic Odysseys of Theros p. 225*  

Extra pairs of arms magically orbit the bodies of the titanic, nearly forgotten artisans known as hundred-handed ones. These giants often dwell in remote mountains and seaside cliffs, where they carve their memories into the ancient stone, covering their territories with intricate reliefs and massive statues of bygone ages. Some linger near ancient temples and palaces, ruins they once raised to the gods or archons of old.

```statblock
"name": "Hundred-Handed One (MOT)"
"size": "Huge"
"type": "giant"
"alignment": "Lawful Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "243"
"hit_dice": "18d12 + 126"
"stats":
- !!int "26"
- !!int "15"
- !!int "25"
- !!int "14"
- !!int "16"
- !!int "16"
"speed": "40 ft."
"saves":
  "Wisdom": !!int "8"
  "Constitution": !!int "12"
"skillsaves":
  "Intimidation": !!int "8"
  "Perception": !!int "8"
"condition_immunities": "[frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "darkvision 120 ft., passive Perception 18"
"languages": "Giant"
"cr": "15"
"traits":
- "desc": "The giant can take one reaction on every turn in a combat."
  "name": "Reactive"
- "desc": "The giant can't be [surprised](/2-Mechanics/CLI/rules/conditions.md#surprised)."
  "name": "Vigilant"
"actions":
- "desc": "The giant makes four longsword attacks or two rock attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +13 to hit, reach 15 ft., one target. Hit: 21\
    \ (3d8 + 8) slashing damage."
  "name": "Longsword"
- "desc": "Ranged Weapon Attack: +13 to hit, range 60/240 ft., one target. Hit:\
    \ 30 (4d10 + 8) bludgeoning damage. If the target is a creature, it must succeed\
    \ on a DC 21 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Rock"
"reactions":
- "desc": "The giant adds 5 to its AC against one weapon attack that would hit it.\
    \ To do so, the giant must see the attacker and be wielding a melee weapon."
  "name": "Deflect Attack"
"source":
- "MOT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MOT/Hundred-Handed%20One.webp"
```
^statblock

```encounter-table
name: Hundred-Handed One
creatures:
 - 1: Hundred-Handed One
```