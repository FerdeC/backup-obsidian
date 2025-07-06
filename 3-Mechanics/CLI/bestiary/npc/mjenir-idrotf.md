---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Mjenir"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 215
---
# [Mjenir](2-Mechanics\CLI\bestiary\npc/mjenir-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 215*  

With grand events having been set in motion, those sensitive to prophecy have begun to experience dreams and visions. One such person is Mjenir, a fifty-year-old shaman of the Reghed Elk Tribe, who received a vision about the characters' journey to the Reghed Glacier.

Druids dwell in forests and other secluded wilderness locations, where they protect the natural world from monsters and the encroachment of civilization. Some are tribal shamans who heal the sick, pray to animal spirits, and provide spiritual guidance.

```statblock
"name": "Mjenir (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral"
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
- "desc": "Mjenir is a 4th-level spellcaster. Its spellcasting ability is Wisdom (spell\
    \ save DC 12, +4 to hit with spell attacks). It has the following druid spells\
    \ prepared:\n\nCantrips (at will): [druidcraft](/2-Mechanics/CLI/spells/druidcraft.md),\
    \ [produce flame](/2-Mechanics/CLI/spells/produce-flame.md), [shillelagh](/2-Mechanics/CLI/spells/shillelagh.md)\n\
    \n1st level (4 slots): [entangle](/2-Mechanics/CLI/spells/entangle.md), [longstrider](/2-Mechanics/CLI/spells/longstrider.md),\
    \ [speak with animals](/2-Mechanics/CLI/spells/speak-with-animals.md), [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md)\n\
    \n2nd level (3 slots): [animal messenger](/2-Mechanics/CLI/spells/animal-messenger.md),\
    \ [barkskin](/2-Mechanics/CLI/spells/barkskin.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit (+4 to hit with shillelagh), reach\
    \ 5 ft., one target. Hit: 3 (1d6) bludgeoning damage, 4 (1d8) bludgeoning\
    \ damage if wielded with two hands, or 6 (1d8 + 2) bludgeoning damage with [shillelagh](/2-Mechanics/CLI/spells/shillelagh.md)."
  "name": "Quarterstaff"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Mjenir.webp"
```
^statblock

```encounter-table
name: Mjenir
creatures:
 - 1: Mjenir
```