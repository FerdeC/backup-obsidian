---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/half-elf
aliases: ["Melannor Fellbranch"]
NoteIcon: monster
BestiaryType: humanoid (half-elf)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 36
---
# [Melannor Fellbranch](2-Mechanics\CLI\bestiary\npc/melannor-fellbranch-wdh.md)
*Source: Waterdeep: Dragon Heist p. 36*  

Melannor Fellbranch, the friendly but humorless groundskeeper of Phaulkonmere, a compound located one block south of Kolat Towers, is the characters' main contact in the Emerald Enclave

```statblock
"name": "Melannor Fellbranch (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-elf"
"alignment": "Chaotic Good"
"ac": !!int "11"
"ac_class": "16 with [barkskin](/2-Mechanics/CLI/spells/barkskin.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "10"
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
"languages": "Common, Elvish"
"cr": "2"
"traits":
- "desc": "Melannor is a 4th-level spellcaster. His spellcasting ability is Wisdom.\
    \ He has the following druid spells prepared:\n\nCantrips (at will): [druidcraft](/2-Mechanics/CLI/spells/druidcraft.md),\
    \ [produce flame](/2-Mechanics/CLI/spells/produce-flame.md), [shillelagh](/2-Mechanics/CLI/spells/shillelagh.md)\n\
    \n1st level (4 slots): [entangle](/2-Mechanics/CLI/spells/entangle.md), [longstrider](/2-Mechanics/CLI/spells/longstrider.md),\
    \ [speak with animals](/2-Mechanics/CLI/spells/speak-with-animals.md), [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md)\n\
    \n2nd level (3 slots): [animal messenger](/2-Mechanics/CLI/spells/animal-messenger.md),\
    \ [barkskin](/2-Mechanics/CLI/spells/barkskin.md)"
  "name": "Spellcasting"
- "desc": "Melannor has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put him to sleep."
  "name": "Fey Ancestry"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit or Melee Weapon Attack +4 to hit with\
    \ shillelagh, reach 5 ft., one target. Hit: 3 (1d6) bludgeoning damage, or\
    \ 6 (1d8 + 2) bludgeoning damage with shillelagh or if wielded with two hands."
  "name": "Quarterstaff"
"source":
- "WDH"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDH/Melannor%20Fellbranch.webp"
```
^statblock

```encounter-table
name: Melannor Fellbranch
creatures:
 - 1: Melannor Fellbranch
```