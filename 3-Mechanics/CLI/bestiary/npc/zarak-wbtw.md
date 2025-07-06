---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wbtw
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/orc
aliases: ["Zarak"]
NoteIcon: monster
BestiaryType: humanoid (orc)
SourceType: Bestiary
BookSource: The Wild Beyond the Witchlight p. 222
---
# [Zarak](2-Mechanics\CLI\bestiary\npc/zarak-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 222*  

Zarak is an assassin without honor or conscience. Unusually short of stature for someone of orcish heritage, he might pass for an ugly, beardless dwarf were it not for his rotting tusks and grayish pallor. The only thing he loves is money, and he wouldn't hesitate to stab allies in the back if they came between him and the riches he covets.

```statblock
"name": "Zarak (WBtW)"
"size": "Medium"
"type": "humanoid"
"subtype": "orc"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "37"
"hit_dice": "5d8 + 15"
"stats":
- !!int "13"
- !!int "16"
- !!int "16"
- !!int "11"
- !!int "15"
- !!int "6"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
  "Intelligence": !!int "2"
"skillsaves":
  "Stealth": !!int "7"
  "Insight": !!int "6"
  "Perception": !!int "6"
  "Acrobatics": !!int "7"
"senses": "darkvision 60, passive Perception 16"
"languages": "Common, Orc"
"cr": "2"
"traits":
- "desc": "Zarak carries a [potion of invisibility](/2-Mechanics/CLI/items/potion-of-invisibility.md)."
  "name": "Special Equipment"
"actions":
- "desc": "Zarak makes two Dagger attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage, plus an extra 5 (2d4)\
    \ piercing damage if the target is a creature and Zarak has at least 18 hit points."
  "name": "Dagger"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one Humanoid. Hit: 8\
    \ (2d4 + 3) slashing damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 11). Until this grapple ends, the target takes 8 (2d4 + 3) slashing\
    \ damage at the start of each of its turns, and Zarak can't grapple another creature\
    \ or use Assassin's Whim."
  "name": "Garrote"
"bonus_actions":
- "desc": "Zarak takes the Dash, Disengage, or Hide action."
  "name": "Assassin's Whim"
"reactions":
- "desc": "Zarak halves the damage he takes from an attack made against him, provided\
    \ he can see the attacker."
  "name": "Uncanny Dodge"
"source":
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WBtW/Zarak.webp"
```
^statblock

```encounter-table
name: Zarak
creatures:
 - 1: Zarak
```