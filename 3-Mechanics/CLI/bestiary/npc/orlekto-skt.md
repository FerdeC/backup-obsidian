---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/13
- monster/size/huge
- monster/type/giant
aliases: ["Orlekto"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Storm King's Thunder p. 256
---
# [Orlekto](2-Mechanics\CLI\bestiary\npc/orlekto-skt.md)
*Source: Storm King's Thunder p. 256*  

```statblock
"name": "Orlekto (SKT)"
"size": "Huge"
"type": "giant"
"alignment": "Chaotic Evil"
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
  "Deception": !!int "14"
  "Perception": !!int "9"
"damage_resistances": "cold"
"damage_immunities": "lightning, thunder"
"senses": "passive Perception 19"
"languages": "Common, Giant"
"cr": "13"
"traits":
- "desc": "Orlekto casts one of the following spells, requiring no material spell\
    \ components and using Charisma as the spellcasting ability (spell save DC 17):\n\
    \nAt will: [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [levitate](/2-Mechanics/CLI/spells/levitate.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md)\n\n1/day each: [control weather](/2-Mechanics/CLI/spells/control-weather.md)\
    \ (cast as 1 action), [water breathing](/2-Mechanics/CLI/spells/water-breathing.md)"
  "name": "Spellcasting"
- "desc": "Orlekto is in love with Princess Mirran and wants to see her become Queen\
    \ of the Wyrmskull Throne. (If Mirran is dead, Orlekto aims to avenge her.) If\
    \ the opportunity to eliminate Hekaton or Serissa presents itself, Orlekto seizes\
    \ it. Until then, he conceals his treacherous nature.\n\nIdeal: \"Storm giants\
    \ should rule the world. Weak leaders have let dragons and others steal what the\
    \ gods gave to us!\"\n\nBond: \"I serve Princess Mirran and her alone.\"\n\nFlaw:\
    \ \"For Mirran's love or my revenge, I'd betray my king and my honor.\""
  "name": "Roleplaying Information"
- "desc": "Orlekto can breathe air and water."
  "name": "Amphibious"
"actions":
- "desc": "Orlekto makes two greatsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 30\
    \ (6d6 + 9) slashing damage."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +14 to hit, range 60/240 ft., one target. Hit:\
    \ 35 (4d12 + 9) bludgeoning damage."
  "name": "Rock"
- "desc": "Orlekto hurls a magical lightning bolt at a point it can see within 500\
    \ feet of it. Each creature within 10 feet of that point must make a DC 17 Dexterity\
    \ saving throw, taking 54 (12d8) lightning damage on a failed save, or half\
    \ as much damage on a successful one."
  "name": "Lightning Strike (Recharge 5-6)"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Orlekto.webp"
```
^statblock

```encounter-table
name: Orlekto
creatures:
 - 1: Orlekto
```