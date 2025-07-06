---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/lmop
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Evil Mage"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Lost Mine of Phandelver p. 57
---
# [Evil Mage](2-Mechanics\CLI\bestiary\humanoid/evil-mage-lmop.md)
*Source: Lost Mine of Phandelver p. 57*  

Evil mages (such as Iarno Albrek and Hamun Kost) hunger for arcane power and dwell in isolated places, where they can perform terrible magical experiments without interference.

```statblock
"name": "Evil Mage (LMoP)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "5d8"
"stats":
- !!int "9"
- !!int "14"
- !!int "11"
- !!int "17"
- !!int "12"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "3"
  "Intelligence": !!int "5"
"skillsaves":
  "History": !!int "5"
  "Arcana": !!int "5"
"senses": "passive Perception 11"
"languages": "Common, Draconic, Dwarvish, Elvish"
"cr": "1"
"traits":
- "desc": "The mage is a 4th-level spellcaster that uses Intelligence as its spellcasting\
    \ ability (spell save DC 13; +5 to hit with spell attacks). The mage knows the\
    \ following spells from the wizard's spell list:\n\nCantrips (at will): [light](/2-Mechanics/CLI/spells/light.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [shocking grasp](/2-Mechanics/CLI/spells/shocking-grasp.md)\n\
    \n1st level (4 slots): [charm person](/2-Mechanics/CLI/spells/charm-person.md),\
    \ [magic missile](/2-Mechanics/CLI/spells/magic-missile.md)\n\n2nd level (3\
    \ slots): [hold person](/2-Mechanics/CLI/spells/hold-person.md), [misty step](/2-Mechanics/CLI/spells/misty-step.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee Weapon Attack: +1 to hit, reach 5 ft., one target. Hit: 3 (1d8\
    \ - 1) bludgeoning damage."
  "name": "Quarterstaff"
"source":
- "LMoP"
- "RMBRE"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/LMoP/Evil%20Mage.webp"
```
^statblock

```encounter-table
name: Evil Mage
creatures:
 - 1: Evil Mage
```