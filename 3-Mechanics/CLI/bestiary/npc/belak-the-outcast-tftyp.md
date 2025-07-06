---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Belak the Outcast"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 9
---
# [Belak the Outcast](2-Mechanics\CLI\bestiary\npc/belak-the-outcast-tftyp.md)
*Source: Tales from the Yawning Portal p. 9*  

```statblock
"name": "Belak the Outcast (TftYP)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Any alignment"
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
"senses": "passive Perception 14"
"languages": "Druidic plus any two languages"
"cr": "2"
"traits":
- "desc": "The druid is a 4th-level spellcaster. Its spellcasting ability is Wisdom\
    \ (spell save DC 12, +4 to hit with spell attacks). It has the following druid\
    \ spells prepared:\n\nCantrips (at will): [druidcraft](/2-Mechanics/CLI/spells/druidcraft.md),\
    \ [poison spray](/2-Mechanics/CLI/spells/poison-spray.md), [shillelagh](/2-Mechanics/CLI/spells/shillelagh.md)\n\
    \n1st level (4 slots): [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md),\
    \ [entangle](/2-Mechanics/CLI/spells/entangle.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md),\
    \ [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md)\n\n2nd level (3 slots):\
    \ [barkskin](/2-Mechanics/CLI/spells/barkskin.md), [flaming sphere](/2-Mechanics/CLI/spells/flaming-sphere.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit (+4 to hit with shillelagh), reach\
    \ 5 ft., one target. Hit: 3 (1d6) bludgeoning damage, or 6 (1d8 + 2) bludgeoning\
    \ damage with shillelagh or if wielded with two hands."
  "name": "Quarterstaff"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Belak%20the%20Outcast.webp"
```
^statblock

```encounter-table
name: Belak the Outcast
creatures:
 - 1: Belak the Outcast
```