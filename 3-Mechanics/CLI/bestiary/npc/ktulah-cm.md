---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cm
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/tabaxi
aliases: ["K'Tulah"]
NoteIcon: monster
BestiaryType: humanoid (tabaxi)
SourceType: Bestiary
BookSource: Candlekeep Mysteries p. 64
---
# [K'Tulah](2-Mechanics\CLI\bestiary\npc/ktulah-cm.md)
*Source: Candlekeep Mysteries p. 64*  

K'Tulah is a gregarious tabaxi, a catlike humanoid. She arrived at Candlekeep six days ago and received permission to use the library to conduct her research on regional forms of folk magic.

She is an animated talker whose exaggerated gesticulations while chatting annoy Varnyr, but the elf appreciates her academic expertise.

```statblock
"name": "K'Tulah (CM)"
"size": "Medium"
"type": "humanoid"
"subtype": "tabaxi"
"alignment": "Neutral Good"
"ac": !!int "11"
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
"languages": "Common, Druidic"
"cr": "2"
"traits":
- "desc": "K'Tulah is a 4th-level spellcaster. K'Tulah's spellcasting ability is Wisdom\
    \ (spell save DC 12, +4 to hit with spell attacks). K'Tulah has the following\
    \ druid spells prepared:\n\nCantrips (at will): [druidcraft](/2-Mechanics/CLI/spells/druidcraft.md),\
    \ [produce flame](/2-Mechanics/CLI/spells/produce-flame.md), [shillelagh](/2-Mechanics/CLI/spells/shillelagh.md)\n\
    \n1st level (4 slots): [entangle](/2-Mechanics/CLI/spells/entangle.md), [longstrider](/2-Mechanics/CLI/spells/longstrider.md),\
    \ [speak with animals](/2-Mechanics/CLI/spells/speak-with-animals.md), [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md)\n\
    \n2nd level (3 slots): [animal messenger](/2-Mechanics/CLI/spells/animal-messenger.md),\
    \ [barkskin](/2-Mechanics/CLI/spells/barkskin.md)"
  "name": "Spellcasting"
- "desc": "When K'Tulah moves on her turn in combat, she can double her speed until\
    \ the end of the turn. Once she uses this ability, K'Tulah can't use it again\
    \ until she moves 0 feet on one of her turns."
  "name": "Feline Agility"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit (+4 to hit with shillelagh), reach\
    \ 5 ft., one target. Hit: 3 (1d6) bludgeoning damage, 4 (1d8) bludgeoning\
    \ damage if wielded with two hands, or 6 (1d8 + 2) bludgeoning damage with shillelagh."
  "name": "Quarterstaff"
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d4)\
    \ slashing damage."
  "name": "Claws"
"source":
- "CM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CM/K%27Tulah.webp"
```
^statblock

```encounter-table
name: K'Tulah
creatures:
 - 1: K'Tulah
```