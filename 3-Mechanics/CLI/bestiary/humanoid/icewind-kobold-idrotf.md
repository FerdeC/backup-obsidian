---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/1-8
- monster/size/small
- monster/type/humanoid/kobold
aliases: ["Icewind Kobold"]
NoteIcon: monster
BestiaryType: humanoid (kobold)
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 296
---
# [Icewind Kobold](2-Mechanics\CLI\bestiary\humanoid/icewind-kobold-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 296*  

Kobolds can be found anywhere dragons are known to dwell, and those that live in the mountains and hills of Icewind Dale are among the hardiest of their kind. Drawn to the north by a desire to find and serve white dragons, these kobolds adapted as best they can to the hostile climate. Their sensitive eyes appreciate sunless days and long, dark nights. They use wooden javelins as tools to test the snow ahead of them.

Kobolds native to Icewind Dale frequently wander into Ten-Towns to escape the dreadful cold, hoping to trade what few skills they have for some warm soup and shelter. The people of Ten-Towns, accustomed to the presence of strange outlanders, allow these kobolds to dwell among them for the most part. When the kobolds don't feel safe, they acquire heavy winter clothing and disguise themselves as humans by standing on one another's shoulders. Three kobolds in cold weather gear can pass themselves off as a clumsy human with a successful group Charisma (Deception) check, the DC of which equals the onlooker's Wisdom (Insight) check result.

```statblock
"name": "Icewind Kobold (IDRotF)"
"size": "Small"
"type": "humanoid"
"subtype": "kobold"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "9"
"hit_dice": "2d6 + 2"
"stats":
- !!int "7"
- !!int "15"
- !!int "12"
- !!int "8"
- !!int "8"
- !!int "8"
"speed": "30 ft., climb 20 ft."
"saves":
  "Dexterity": !!int "4"
  "Constitution": !!int "3"
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "1"
  "Survival": !!int "1"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Draconic"
"cr": "1/8"
"traits":
- "desc": "The kobold has advantage on an attack roll against a creature if at least\
    \ one of the kobold's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
- "desc": "While in sunlight, the kobold has disadvantage on attack rolls, as well\
    \ as on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
- "desc": "Melee or Ranged Weapon Attack: +0 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 1 (1d6 - 2) piercing damage."
  "name": "Javelin"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Icewind%20Kobold.webp"
```
^statblock

```encounter-table
name: Icewind Kobold
creatures:
 - 1: Icewind Kobold
```