---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Sanbalet"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 252
---
# [Sanbalet](2-Mechanics\CLI\bestiary\npc/sanbalet-gos.md)
*Source: Ghosts of Saltmarsh p. 252*  

In The Sinister Secret of Saltmarsh, Sanbalet is the leader of the land-based half of a smuggling ring. He is a cunning narcissist with an interest in illusion and mind control. He defends the contraband stored in the caves under the haunted house.

```statblock
"name": "Sanbalet (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "11"
"hp": !!int "27"
"hit_dice": "6d8"
"stats":
- !!int "10"
- !!int "12"
- !!int "11"
- !!int "16"
- !!int "13"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Arcana": !!int "5"
"senses": "passive Perception 11"
"languages": "Common"
"cr": "1"
"traits":
- "desc": "Sanbalet is a 3rd-level spellcaster. His spellcasting ability is Intelligence\
    \ (spell save DC 13, +5 to hit with spell attacks). He has the following wizard\
    \ spells prepared:\n\nCantrips (at will): [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md),\
    \ [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md), [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md)\n\
    \n1st level (4 slots): [charm person](/2-Mechanics/CLI/spells/charm-person.md),\
    \ [color spray](/2-Mechanics/CLI/spells/color-spray.md), [magic missile](/2-Mechanics/CLI/spells/magic-missile.md),\
    \ [silent image](/2-Mechanics/CLI/spells/silent-image.md)\n\n2nd level (2 slots):\
    \ [magic mouth](/2-Mechanics/CLI/spells/magic-mouth.md), [scorching ray](/2-Mechanics/CLI/spells/scorching-ray.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 3 (1d4 + 1) piercing damage."
  "name": "Dagger"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Sanbalet.webp"
```
^statblock

```encounter-table
name: Sanbalet
creatures:
 - 1: Sanbalet
```