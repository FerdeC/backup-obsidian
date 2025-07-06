---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/hotdq
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Frulam Mondath"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Hoard of the Dragon Queen p. 90
---
# [Frulam Mondath](2-Mechanics\CLI\bestiary\npc/frulam-mondath-hotdq.md)
*Source: Hoard of the Dragon Queen p. 90*  

```statblock
"name": "Frulam Mondath (HotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "[chain mail](/2-Mechanics/CLI/items/chain-mail.md)"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"stats":
- !!int "14"
- !!int "10"
- !!int "13"
- !!int "11"
- !!int "18"
- !!int "15"
"speed": "30 ft."
"saves":
  "Charisma": !!int "4"
  "Wisdom": !!int "6"
"skillsaves":
  "Deception": !!int "4"
  "Religion": !!int "2"
  "History": !!int "2"
"senses": "passive Perception 14"
"languages": "Common, Draconic, Infernal"
"cr": "2"
"traits":
- "desc": "Frulam is a 5th-level spellcaster that uses Wisdom as her spellcasting\
    \ ability (spell save DC 14, +6 to hit with spell attacks). Frulam has the following\
    \ spells prepared from the cleric spell list:\n\nCantrips (at will): [light](/2-Mechanics/CLI/spells/light.md),\
    \ [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1st level (4 slots): [command](/2-Mechanics/CLI/spells/command.md), [cure\
    \ wounds](/2-Mechanics/CLI/spells/cure-wounds.md), [healing word](/2-Mechanics/CLI/spells/healing-word.md),\
    \ [sanctuary](/2-Mechanics/CLI/spells/sanctuary.md)\n\n2nd level (3 slots):\
    \ [calm emotions](/2-Mechanics/CLI/spells/calm-emotions.md), [hold person](/2-Mechanics/CLI/spells/hold-person.md),\
    \ [spiritual weapon](/2-Mechanics/CLI/spells/spiritual-weapon.md)\n\n3rd level\
    \ (2 slots): [mass healing word](/2-Mechanics/CLI/spells/mass-healing-word.md),\
    \ [spirit guardians](/2-Mechanics/CLI/spells/spirit-guardians.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Frulam attacks twice with her halberd."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 10 ft., one target. Hit: 7\
    \ (1d10 + 2) bludgeoning damage."
  "name": "Halberd"
"source":
- "HotDQ"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/HotDQ/Frulam%20Mondath.webp"
```
^statblock

```encounter-table
name: Frulam Mondath
creatures:
 - 1: Frulam Mondath
```