---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Crushing Wave Priest"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 205
---
# [Crushing Wave Priest](2-Mechanics\CLI\bestiary\humanoid/crushing-wave-priest-pota.md)
*Source: Princes of the Apocalypse p. 205*  

Crushing Wave priests are the fanatical core of the cult. Gathering in secretive cabals, they perform dark rituals to glorify Olhydra as the embodiment of water's destructiveness. They believe that using water to kill their enemies, such as through ritual drowning, earns them Olhydra's favor.

```statblock
"name": "Crushing Wave Priest (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "[chain shirt](/2-Mechanics/CLI/items/chain-shirt.md)"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "15"
- !!int "11"
- !!int "14"
- !!int "10"
- !!int "11"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Stealth": !!int "2"
  "Religion": !!int "2"
"senses": "passive Perception 10"
"languages": "Aquan, Common"
"cr": "2"
"traits":
- "desc": "The priest is a 5th-level spellcaster. Its spellcasting ability is Charisma\
    \ (spell save DC 13, +5 to hit with spell attacks). It knows the following sorcerer\
    \ spells:\n\nCantrips (at will): [chill touch](/2-Mechanics/CLI/spells/chill-touch.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md), [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md)\n\
    \n1st level (4 slots): [expeditious retreat](/2-Mechanics/CLI/spells/expeditious-retreat.md),\
    \ [ice knife](/2-Mechanics/CLI/spells/ice-knife-xge.md), [magic missile](/2-Mechanics/CLI/spells/magic-missile.md),\
    \ [shield](/2-Mechanics/CLI/spells/shield.md)\n\n2nd level (3 slots): [blur](/2-Mechanics/CLI/spells/blur.md),\
    \ [hold person](/2-Mechanics/CLI/spells/hold-person.md)\n\n3rd level (2 slots):\
    \ [sleet storm](/2-Mechanics/CLI/spells/sleet-storm.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) bludgeoning damage."
  "name": "Quarterstaff"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Crushing%20Wave%20Priest.webp"
```
^statblock

```encounter-table
name: Crushing Wave Priest
creatures:
 - 1: Crushing Wave Priest
```