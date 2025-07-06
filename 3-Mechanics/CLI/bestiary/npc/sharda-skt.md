---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/illuskan-human
aliases: ["Sharda"]
NoteIcon: monster
BestiaryType: humanoid (Illuskan human)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 103
---
# [Sharda](2-Mechanics\CLI\bestiary\npc/sharda-skt.md)
*Source: Storm King's Thunder p. 103*  

```statblock
"name": "Sharda (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Illuskan human"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "[breastplate](/2-Mechanics/CLI/items/breastplate.md)"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "11"
- !!int "14"
- !!int "12"
- !!int "10"
- !!int "13"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "4"
  "Religion": !!int "2"
  "Persuasion": !!int "4"
"senses": "passive Perception 11"
"languages": "Common, Terran"
"cr": "2"
"traits":
- "desc": "Sharda is a 4th-level spellcaster. Its spellcasting ability is Wisdom (spell\
    \ save DC 11, +3 to hit with spell attacks). Sharda has the following cleric\
    \ spells prepared:\n\nCantrips (at will): [light](/2-Mechanics/CLI/spells/light.md),\
    \ [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1st level (4 slots): [command](/2-Mechanics/CLI/spells/command.md), [inflict\
    \ wounds](/2-Mechanics/CLI/spells/inflict-wounds.md), [shield of faith](/2-Mechanics/CLI/spells/shield-of-faith.md)\n\
    \n2nd level (3 slots): [hold person](/2-Mechanics/CLI/spells/hold-person.md),\
    \ [spiritual weapon](/2-Mechanics/CLI/spells/spiritual-weapon.md)"
  "name": "Spellcasting"
- "desc": "Sharda has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Dark Devotion"
"actions":
- "desc": "Sharda makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 4\
    \ (1d4 + 2) bludgeoning damage."
  "name": "Club"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Sharda.webp"
```
^statblock

```encounter-table
name: Sharda
creatures:
 - 1: Sharda
```