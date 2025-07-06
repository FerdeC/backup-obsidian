---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Bosco Daggerhand"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 68
---
# [Bosco Daggerhand](2-Mechanics\CLI\bestiary\npc/bosco-daggerhand-toa.md)
*Source: Tomb of Annihilation p. 68*  

```statblock
"name": "Bosco Daggerhand (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "11"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"stats":
- !!int "15"
- !!int "11"
- !!int "14"
- !!int "10"
- !!int "10"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "2"
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "1/2"
"traits":
- "desc": "Bosco wears a [ring of animal influence](/2-Mechanics/CLI/items/ring-of-animal-influence.md)."
  "name": "Special Equipment"
- "desc": "Bosco has advantage on an attack roll against a creature if at least one\
    \ of Bosco's allies is within 5 feet of the creature and the ally isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "Bosco makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 5\
    \ (1d6 + 2) bludgeoning damage."
  "name": "Mace"
- "desc": "Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. Hit:\
    \ 5 (1d10) piercing damage."
  "name": "Heavy Crossbow"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Bosco%20Daggerhand.webp"
```
^statblock

```encounter-table
name: Bosco Daggerhand
creatures:
 - 1: Bosco Daggerhand
```