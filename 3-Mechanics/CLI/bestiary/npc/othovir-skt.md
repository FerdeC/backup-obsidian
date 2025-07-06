---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/
- monster/size/medium
- monster/type/humanoid/illuskan-human
aliases: ["Othovir"]
NoteIcon: monster
BestiaryType: humanoid (Illuskan human)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 255
---
# [Othovir](2-Mechanics\CLI\bestiary\npc/othovir-skt.md)
*Source: Storm King's Thunder p. 255*  

Othovir is a gifted harness-maker who doesn't talk about his family or where he came from. He cares about his business, his clients, and his good name.

Ideal:"Find what you do well, and do it to the best of your ability."

Bond:"I won't allow my name to be tarnished."

Flaw:"I get angry when others pry into my private life."

```statblock
"name": "Othovir (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Illuskan human"
"alignment": "Lawful Neutral"
"ac": !!int "10"
"ac_class": "13 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"stats":
- !!int "11"
- !!int "10"
- !!int "13"
- !!int "12"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Insight": !!int "4"
  "Persuasion": !!int "5"
"senses": "passive Perception 12"
"languages": "Common, Elvish"
"traits":
- "desc": "Othovir casts one of the following spells, using Charisma as the spellcasting\
    \ ability (spell save DC 13; +5 to hit with spell attacks):\n\nAt will:\
    \ [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md) (1d10 fire damage), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\
    \n1/day each: [mage armor](/2-Mechanics/CLI/spells/mage-armor.md), [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md),\
    \ [witch bolt](/2-Mechanics/CLI/spells/witch-bolt.md)"
  "name": "Spellcasting"
- "desc": "Othovir is a gifted harness-maker who doesn't talk about his family or\
    \ where he came from. He cares about his business, his clients, and his good name.\n\
    \nIdeal: \"Find what you do well, and do it to the best of your ability.\"\n\n\
    Bond: \"I won't allow my name to be tarnished.\"\n\nFlaw: \"I get angry when others\
    \ pry into my private life.\""
  "name": "Roleplaying Information"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 4 (1d8)\
    \ piercing damage."
  "name": "Rapier"
"reactions":
- "desc": "Othovir adds 2 to its AC against one melee attack that would hit him. To\
    \ do so, Othovir must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Othovir.webp"
```
^statblock

```encounter-table
name: Othovir
creatures:
 - 1: Othovir
```