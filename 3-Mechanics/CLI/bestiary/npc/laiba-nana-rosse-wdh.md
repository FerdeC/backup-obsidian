---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/tiefling
aliases: ["Laiba "Nana" Rosse"]
NoteIcon: monster
BestiaryType: humanoid (tiefling)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 116
---
# [Laiba "Nana" Rosse](2-Mechanics\CLI\bestiary\npc/laiba-nana-rosse-wdh.md)
*Source: Waterdeep: Dragon Heist p. 116*  

Laiba Rosse, better known as "Nana," is the caretaker and private tutor for Terenzio and Elzerina, and she does her best to keep track of their every move. Even so, the two often sneak away from her watchful eye. Nana dresses in flowing red robes. She relaxes in the twins' playroom (area C17) when she's not with the children.

```statblock
"name": "Laiba \"Nana\" Rosse (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "tiefling"
"alignment": "Lawful Evil"
"ac": !!int "13"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
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
"damage_resistances": "fire"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Infernal"
"cr": "2"
"traits":
- "desc": "Laiba's spellcasting ability is Charisma. She can innately cast the following\
    \ spells, requiring no material components:\n\nAt will: [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)"
  "name": "Innate Spellcasting"
- "desc": "Laiba is a 4th-level spellcaster. Her spellcasting ability is Wisdom. Laiba\
    \ has the following cleric spells prepared:\n\nCantrips (at will): [light](/2-Mechanics/CLI/spells/light.md),\
    \ [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1st level (4 slots): [command](/2-Mechanics/CLI/spells/command.md), [inflict\
    \ wounds](/2-Mechanics/CLI/spells/inflict-wounds.md), [shield of faith](/2-Mechanics/CLI/spells/shield-of-faith.md)\n\
    \n2nd level (3 slots): [hold person](/2-Mechanics/CLI/spells/hold-person.md),\
    \ [spiritual weapon](/2-Mechanics/CLI/spells/spiritual-weapon.md)"
  "name": "Spellcasting"
- "desc": "Laiba has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Dark Devotion"
"actions":
- "desc": "Laiba makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 4\
    \ (1d4 + 2) piercing damage. Or Ranged Weapon Attack: +4 to hit, range 20/60\
    \ ft., one creature. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "WDH"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDH/Laiba%20Nana%20Rosse.webp"
```
^statblock

```encounter-table
name: Laiba "Nana" Rosse
creatures:
 - 1: Laiba "Nana" Rosse
```