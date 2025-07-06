---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cos
- monster/cr/3
- monster/size/medium
- monster/type/undead
aliases: ["Phantom Warrior (Archer)"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Curse of Strahd p. 142
---
# [Phantom Warrior (Archer)](2-Mechanics\CLI\bestiary\undead/phantom-warrior-archer-cos.md)
*Source: Curse of Strahd p. 142*  

```statblock
"name": "Phantom Warrior (Archer) (CoS)"
"size": "Medium"
"type": "undead"
"alignment": "Any alignment"
"ac": !!int "16"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"stats":
- !!int "16"
- !!int "11"
- !!int "16"
- !!int "8"
- !!int "10"
- !!int "15"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "2"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "cold, necrotic, poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone), [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "any languages it knew in life"
"cr": "3"
"traits":
- "desc": "The phantom warrior can see 60 feet into the Ethereal Plane when it is\
    \ on the Material Plane, and vice versa."
  "name": "Ethereal Sight"
- "desc": "The phantom warrior can move through other creatures and objects as if\
    \ they were difficult terrain. It takes 5 (1d10) force damage if it ends its\
    \ turn inside an object."
  "name": "Incorporeal Movement"
- "desc": "The phantom warrior's AC accounts for its spectral armor and shield."
  "name": "Spectral Armor and Shield"
"actions":
- "desc": "The phantom warrior makes two attacks with its spectral longsword or spectral\
    \ longbow."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) force damage."
  "name": "Spectral Longsword"
- "desc": "The phantom warrior enters the Ethereal Plane from the Material Plane,\
    \ or vice versa. It is visible on the Material Plane while it is in the Border\
    \ Ethereal, and vice versa, yet it can't affect or be affected by anything on\
    \ the other plane."
  "name": "Etherealness"
- "desc": "Ranged Weapon Attack: +2 to hit, range 150/600 ft., one target. Hit:\
    \ 4 (1d8) force damage."
  "name": "Spectral Longbow"
"source":
- "CoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CoS/Phantom%20Warrior%20%28Archer%29.webp"
```
^statblock

```encounter-table
name: Phantom Warrior (Archer)
creatures:
 - 1: Phantom Warrior (Archer)
```