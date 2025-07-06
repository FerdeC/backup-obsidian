---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/13
- monster/size/huge
- monster/type/giant
aliases: ["Nym"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Storm King's Thunder p. 207
---
# [Nym](2-Mechanics\CLI\bestiary\npc/nym-skt.md)
*Source: Storm King's Thunder p. 207*  

```statblock
"name": "Nym (SKT)"
"size": "Huge"
"type": "giant"
"alignment": "Neutral Evil"
"ac": !!int "12"
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
  "Deception": !!int "9"
  "Perception": !!int "9"
  "History": !!int "8"
  "Performance": !!int "9"
  "Arcana": !!int "8"
"damage_resistances": "cold"
"damage_immunities": "lightning, thunder"
"senses": "passive Perception 19"
"languages": "Common, Giant"
"cr": "13"
"traits":
- "desc": "Nym's innate spellcasting ability is Charisma (spell save DC 17). It can\
    \ innately cast the following spells, requiring no material components:\n\nAt\
    \ will: [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [feather fall](/2-Mechanics/CLI/spells/feather-fall.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md), [light](/2-Mechanics/CLI/spells/light.md)\n\
    \n3/day each: [control weather](/2-Mechanics/CLI/spells/control-weather.md),\
    \ [water breathing](/2-Mechanics/CLI/spells/water-breathing.md)"
  "name": "Innate Spellcasting"
- "desc": "Nym can breathe air and water."
  "name": "Amphibious"
"actions":
- "desc": "Nym makes two greatsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 30\
    \ (6d6 + 9) slashing damage."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +14 to hit, range 60/240 ft., one target. Hit:\
    \ 35 (4d12 + 9) bludgeoning damage."
  "name": "Rock"
- "desc": "Nym hurls a magical lightning bolt at a point it can see within 500 feet\
    \ of it. Each creature within 10 feet of that point must make a DC 17 Dexterity\
    \ saving throw, taking 54 (12d8) lightning damage on a failed save, or half\
    \ as much damage on a successful one."
  "name": "Lightning Strike (Recharge 5-6)"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Nym.webp"
```
^statblock

```encounter-table
name: Nym
creatures:
 - 1: Nym
```