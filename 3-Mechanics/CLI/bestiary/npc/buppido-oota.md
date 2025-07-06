---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1-4
- monster/size/small
- monster/type/humanoid/derro
aliases: ["Buppido"]
NoteIcon: monster
BestiaryType: humanoid (derro)
SourceType: Bestiary
BookSource: Out of the Abyss p. 6
---
# [Buppido](2-Mechanics\CLI\bestiary\npc/buppido-oota.md)
*Source: Out of the Abyss p. 6*  

```statblock
"name": "Buppido (OotA)"
"size": "Small"
"type": "humanoid"
"subtype": "derro"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "13"
"hit_dice": "3d6 + 3"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "11"
- !!int "5"
- !!int "9"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "4"
"senses": "darkvision 120 ft., passive Perception 7"
"languages": "Dwarvish, Undercommon"
"cr": "1/4"
"traits":
- "desc": "Buppido has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "While in sunlight, Buppido has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 3 (1d6)\
    \ piercing damage. If the target is Medium or smaller, Buppido can choose to deal\
    \ no damage and knock it [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Hooked Spear"
- "desc": "Ranged Weapon Attack: +4 to hit, range 80/320 ft., one target. Hit:\
    \ 6 (1d8 + 2) piercing damage."
  "name": "Light Crossbow"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Buppido.webp"
```
^statblock

```encounter-table
name: Buppido
creatures:
 - 1: Buppido
```