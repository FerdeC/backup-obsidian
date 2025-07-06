---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/0
- monster/size/small
- monster/type/beast
aliases: ["Chimeric Baboon"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 246
---
# [Chimeric Baboon](2-Mechanics\CLI\bestiary\beast/chimeric-baboon-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 246*  

```statblock
"name": "Chimeric Baboon (IDRotF)"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "3"
"hit_dice": "1d6"
"stats":
- !!int "8"
- !!int "14"
- !!int "11"
- !!int "4"
- !!int "12"
- !!int "6"
"speed": "30 ft., climb 30 ft."
"senses": "passive Perception 11"
"languages": ""
"cr": "0"
"traits":
- "desc": "The baboon has advantage on an attack roll against a creature if at least\
    \ one of the baboon's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Weapon Attack: +1 to hit, reach 5 ft., one target. Hit: 1 (1d4\
    \ - 1) piercing damage, plus an extra 3 (1d6) poison damage."
  "name": "Bite"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Chimeric%20Baboon.webp"
```
^statblock

```encounter-table
name: Chimeric Baboon
creatures:
 - 1: Chimeric Baboon
```