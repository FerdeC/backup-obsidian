---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/hotdq
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/half-dragon
aliases: ["Langdedrosa Cyanwrath"]
NoteIcon: monster
BestiaryType: humanoid (half-dragon)
SourceType: Bestiary
BookSource: Hoard of the Dragon Queen p. 91
---
# [Langdedrosa Cyanwrath](2-Mechanics\CLI\bestiary\npc/langdedrosa-cyanwrath-hotdq.md)
*Source: Hoard of the Dragon Queen p. 91*  

```statblock
"name": "Langdedrosa Cyanwrath (HotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-dragon"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "[splint armor](/2-Mechanics/CLI/items/splint-armor.md)"
"hp": !!int "57"
"hit_dice": "6d12 + 18"
"stats":
- !!int "19"
- !!int "13"
- !!int "16"
- !!int "10"
- !!int "14"
- !!int "12"
"speed": "30 ft."
"saves":
  "Strength": !!int "6"
  "Constitution": !!int "5"
"skillsaves":
  "Intimidation": !!int "3"
  "Athletics": !!int "6"
  "Perception": !!int "4"
"damage_resistances": "lightning"
"senses": "blindsight 10 ft., darkvision 60 ft., passive Perception 14"
"languages": "Common, Draconic"
"cr": "4"
"traits":
- "desc": "On his turn, Langdedrosa can take one additional action."
  "name": "Action Surge (Recharges on a Short or Long Rest)"
- "desc": "Langdedrosa's weapon attacks score a critical hit on a roll of 19 or 20."
  "name": "Improved Critical"
"actions":
- "desc": "Langdedrosa attacks twice, either with his greatsword or spear."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) slashing damage."
  "name": "Greatsword"
- "desc": "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or ranged 20/60\
    \ ft., one target. Hit: 7 (1d6 + 4) piercing damage."
  "name": "Spear"
- "desc": "Langdedrosa breathes lightning in a 30-foot line that is 5 feet wide. Each\
    \ creature in the line must make a DC 13 Dexterity saving throw, taking 22 (4d10)\
    \ lightning damage on a failed save, or half as much damage on a successful one."
  "name": "Lightning Breath (Recharge 5-6)"
"source":
- "HotDQ"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/HotDQ/Langdedrosa%20Cyanwrath.webp"
```
^statblock

```encounter-table
name: Langdedrosa Cyanwrath
creatures:
 - 1: Langdedrosa Cyanwrath
```