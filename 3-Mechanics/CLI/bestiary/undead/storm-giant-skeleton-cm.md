---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cm
- monster/cr/16
- monster/size/huge
- monster/type/undead
aliases: ["Storm Giant Skeleton"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Candlekeep Mysteries p. 208
---
# [Storm Giant Skeleton](2-Mechanics\CLI\bestiary\undead/storm-giant-skeleton-cm.md)
*Source: Candlekeep Mysteries p. 208*  

```statblock
"name": "Storm Giant Skeleton (CM)"
"size": "Huge"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "armor scraps"
"hp": !!int "204"
"hit_dice": "24d12 + 48"
"stats":
- !!int "29"
- !!int "14"
- !!int "15"
- !!int "3"
- !!int "8"
- !!int "1"
"speed": "50 ft."
"saves":
  "Strength": !!int "14"
  "Constitution": !!int "7"
"skillsaves":
  "Perception": !!int "4"
"damage_vulnerabilities": "bludgeoning"
"damage_resistances": "cold"
"damage_immunities": "lightning, poison, thunder"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": ""
"cr": "16"
"actions":
- "desc": "The giant makes two attacks with its greatsword or hurls two rocks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 30\
    \ (6d6 + 9) slashing damage plus 18 (4d8) necrotic damage."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +14 to hit, reach 60/240 ft., one target. Hit:\
    \ 35 (4d12 + 9) bludgeoning damage."
  "name": "Rock"
- "desc": "The giant hurls a magical lightning bolt at a point it can see within 500\
    \ feet of it. Each creature within 10 feet of that point must make a DC 15 Dexterity\
    \ saving throw, taking 54 (12d8) lightning damage on a failed save, or half\
    \ as much damage on a successful one."
  "name": "Lightning Strike (Recharge 5-6)"
"source":
- "CM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CM/Storm%20Giant%20Skeleton.webp"
```
^statblock

```encounter-table
name: Storm Giant Skeleton
creatures:
 - 1: Storm Giant Skeleton
```