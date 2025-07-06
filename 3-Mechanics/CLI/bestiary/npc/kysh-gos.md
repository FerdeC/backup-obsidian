---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/triton
aliases: ["Kysh"]
NoteIcon: monster
BestiaryType: humanoid (triton)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 240
---
# [Kysh](2-Mechanics\CLI\bestiary\npc/kysh-gos.md)
*Source: Ghosts of Saltmarsh p. 240*  

A prisoner of the sahuagin in The Final Enemy, Kysh is a defender of the deep sea realms who is ready to join the party in their struggle. Tritons are folk of the Elemental Plane of Water who journeyed to the Material Plane to watch over the dark places of the ocean depths. They stand guard over portals, deep sea chasms, and other places where foul monsters might emerge. When such threats appear, the tritons take up arms to drive them from the world.

```statblock
"name": "Kysh (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "triton"
"alignment": "Lawful Good"
"ac": !!int "13"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "14"
- !!int "16"
- !!int "12"
- !!int "10"
- !!int "13"
- !!int "14"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Survival": !!int "3"
  "Persuasion": !!int "4"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Primordial"
"cr": "1"
"traits":
- "desc": "Kysh's spellcasting ability is Charisma (spell save DC 12, +4 to hit\
    \ with spell attacks). He can cast the following spell, requiring only verbal\
    \ components:\n\n1/day: [fog cloud](/2-Mechanics/CLI/spells/fog-cloud.md)"
  "name": "Innate Spellcasting"
- "desc": "Kysh can breathe air and water."
  "name": "Amphibious"
- "desc": "Kysh can communicate simple ideas with amphibious and water-breathing beasts.\
    \ They understand the meaning of his words, but he cannot understand them in return."
  "name": "Emissary of the Sea"
"actions":
- "desc": "Kysh makes two melee attacks with his spear."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft, one target. Hit: 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Spear"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Kysh.webp"
```
^statblock

```encounter-table
name: Kysh
creatures:
 - 1: Kysh
```