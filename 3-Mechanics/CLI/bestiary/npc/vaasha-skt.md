---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/13
- monster/size/huge
- monster/type/giant
aliases: ["Vaasha"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Storm King's Thunder p. 256
---
# [Vaasha](2-Mechanics\CLI\bestiary\npc/vaasha-skt.md)
*Source: Storm King's Thunder p. 256*  

```statblock
"name": "Vaasha (SKT)"
"size": "Huge"
"type": "giant"
"alignment": "Neutral Good"
"ac": !!int "16"
"ac_class": "[scale mail](/2-Mechanics/CLI/items/scale-mail.md)"
"hp": !!int "230"
"hit_dice": "20d12 + 100"
"stats":
- !!int "29"
- !!int "14"
- !!int "20"
- !!int "16"
- !!int "18"
- !!int "18"
"speed": "50 ft., swim 50 ft."
"saves":
  "Charisma": !!int "9"
  "Wisdom": !!int "9"
  "Strength": !!int "14"
  "Constitution": !!int "10"
"skillsaves":
  "Athletics": !!int "14"
  "Perception": !!int "9"
  "Survival": !!int "9"
"damage_resistances": "cold"
"damage_immunities": "lightning, thunder"
"senses": "passive Perception 19"
"languages": "Common, Giant"
"cr": "13"
"traits":
- "desc": "Vaasha casts one of the following spells, requiring no material spell components\
    \ and using Charisma as the spellcasting ability (spell save DC 17):\n\nAt will:\
    \ [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [levitate](/2-Mechanics/CLI/spells/levitate.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md)\n\n1/day each: [control weather](/2-Mechanics/CLI/spells/control-weather.md)\
    \ (cast as 1 action), [water breathing](/2-Mechanics/CLI/spells/water-breathing.md)"
  "name": "Spellcasting"
- "desc": "Vaasha is a skilled hunter and tracker who doesn't charge into danger without\
    \ first assessing the risks. She's not afraid to speak her mind, even to her king.\
    \ To her, a worthy leader values the truth, no matter how painful it is.\n\nIdeal:\
    \ \"I want this conflict over with so that I can return to the quiet stillness\
    \ of the ocean depths.\"\n\nBond: \"I'll protect this beautiful world from the\
    \ ravages of evil with my dying breath.\"\n\nFlaw: \"I don't care if my words\
    \ hurt others' feelings.\""
  "name": "Roleplaying Information"
- "desc": "Vaasha can breathe air and water."
  "name": "Amphibious"
"actions":
- "desc": "Vaasha makes two greatsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 30\
    \ (6d6 + 9) slashing damage."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +14 to hit, range 60/240 ft., one target. Hit:\
    \ 35 (4d12 + 9) bludgeoning damage."
  "name": "Rock"
- "desc": "Vaasha hurls a magical lightning bolt at a point it can see within 500\
    \ feet of it. Each creature within 10 feet of that point must make a DC 17 Dexterity\
    \ saving throw, taking 54 (12d8) lightning damage on a failed save, or half\
    \ as much damage on a successful one."
  "name": "Lightning Strike (Recharge 5-6)"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Vaasha.webp"
```
^statblock

```encounter-table
name: Vaasha
creatures:
 - 1: Vaasha
```