---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Sea Elf"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 70
---
# [Sea Elf](2-Mechanics\CLI\bestiary\humanoid/sea-elf-skt.md)
*Source: Storm King's Thunder p. 70*  

```statblock
"name": "Sea Elf (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Chaotic Good"
"ac": !!int "11"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "10"
- !!int "13"
- !!int "12"
- !!int "11"
- !!int "11"
- !!int "12"
"speed": "10 ft., swim 40 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Elvish"
"cr": "1/8"
"traits":
- "desc": "The sea elf has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put the sea elf to sleep."
  "name": "Fey Ancestry"
- "desc": "The sea elf can breathe air and water."
  "name": "Amphibious"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +2 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 3 (1d6) piercing damage, or 4 (1d8) piercing damage\
    \ if used with two hands to make a melee attack."
  "name": "Spear"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Sea%20Elf.webp"
```
^statblock

```encounter-table
name: Sea Elf
creatures:
 - 1: Sea Elf
```