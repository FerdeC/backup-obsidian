---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Reghed Shaman"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 152
---
# [Reghed Shaman](2-Mechanics\CLI\bestiary\humanoid/reghed-shaman-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 152*  

In public, the shaman dons a wooden mask carved in the likeness of a bear, an elk, a tiger, or a wolf, as befits the tribe.

```statblock
"name": "Reghed Shaman (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
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
"languages": "Common, Druidic"
"cr": "2"
"traits":
- "desc": "The shaman is a 4th-level spellcaster. Its spellcasting ability is Wisdom\
    \ (spell save DC 12, +4 to hit with spell attacks). It has the following shaman\
    \ spells prepared:\n\nCantrips (at will): [druidcraft](/2-Mechanics/CLI/spells/druidcraft.md),\
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
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Reghed%20Shaman.webp"
```
^statblock

```encounter-table
name: Reghed Shaman
creatures:
 - 1: Reghed Shaman
```