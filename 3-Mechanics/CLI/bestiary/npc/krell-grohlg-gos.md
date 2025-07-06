---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Krell Grohlg"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 92
---
# [Krell Grohlg](2-Mechanics\CLI\bestiary\npc/krell-grohlg-gos.md)
*Source: Ghosts of Saltmarsh p. 92*  

```statblock
"name": "Krell Grohlg (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Evil"
"ac": !!int "11"
"ac_class": "16 with [barkskin](/2-Mechanics/CLI/spells/barkskin.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "18"
- !!int "12"
- !!int "13"
- !!int "12"
- !!int "15"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Medicine": !!int "4"
  "Nature": !!int "3"
  "Perception": !!int "4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Orc"
"cr": "2"
"traits":
- "desc": "Krell is a 4th-level spellcaster. Its spellcasting ability is Wisdom (spell\
    \ save DC 12, +4 to hit with spell attacks). It has the following druid spells\
    \ prepared:\n\nCantrips (at will): [druidcraft](/2-Mechanics/CLI/spells/druidcraft.md),\
    \ [produce flame](/2-Mechanics/CLI/spells/produce-flame.md), [shillelagh](/2-Mechanics/CLI/spells/shillelagh.md)\n\
    \n1st level (4 slots): [entangle](/2-Mechanics/CLI/spells/entangle.md), [longstrider](/2-Mechanics/CLI/spells/longstrider.md),\
    \ [speak with animals](/2-Mechanics/CLI/spells/speak-with-animals.md), [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md)\n\
    \n2nd level (3 slots): [flaming sphere](/2-Mechanics/CLI/spells/flaming-sphere.md),\
    \ [barkskin](/2-Mechanics/CLI/spells/barkskin.md)"
  "name": "Spellcasting"
- "desc": "Krell"
  "name": "Relentless Endurance"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit (+4 to hit with shillelagh), reach\
    \ 5 ft., one target. Hit: 7 (1d6 + 4) bludgeoning damage, 8 (1d8 + 4) bludgeoning\
    \ damage if wielded with two hands, or 6 (1d8 + 2) bludgeoning damage with [shillelagh](/2-Mechanics/CLI/spells/shillelagh.md)."
  "name": "Quarterstaff"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Krell%20Grohlg.webp"
```
^statblock

```encounter-table
name: Krell Grohlg
creatures:
 - 1: Krell Grohlg
```