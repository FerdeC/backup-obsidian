---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/0
- monster/size/huge
- monster/type/beast
aliases: ["Haungharassk"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 258
---
# [Haungharassk](2-Mechanics\CLI\bestiary\npc/haungharassk-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 258*  

Haungharassk is a magical snail as large as an elephant, with a shell of gleaming gold.

```statblock
"name": "Haungharassk (WDMM)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "6"
"hp": !!int "52"
"hit_dice": "7d12 + 7"
"stats":
- !!int "20"
- !!int "3"
- !!int "13"
- !!int "3"
- !!int "10"
- !!int "3"
"speed": "10 ft., climb 10 ft."
"senses": "passive Perception 10"
"languages": ""
"cr": "0"
"traits":
- "desc": "A pound of salt thrown onto the snail's skin deals 1d6 acid damage to\
    \ the creature."
  "name": "Salt Sensitivity"
- "desc": "A creature that uses an action to touch the living snail gains 6 temporary\
    \ hit points that last for 24 hours. Any creature or object that touches the living\
    \ snail also gains the benefit of a [remove curse](/2-Mechanics/CLI/spells/remove-curse.md)\
    \ spell. The snail loses these magical properties if it dies."
  "name": "Magical Properties"
- "desc": "The snail can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Haungharassk.webp"
```
^statblock

```encounter-table
name: Haungharassk
creatures:
 - 1: Haungharassk
```