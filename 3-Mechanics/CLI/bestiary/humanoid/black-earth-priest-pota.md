---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Black Earth Priest"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 195
---
# [Black Earth Priest](2-Mechanics\CLI\bestiary\humanoid/black-earth-priest-pota.md)
*Source: Princes of the Apocalypse p. 195*  

The priests of the Black Earth are the drivers and organizers of Ogrémoch's cult. They are the true believers, seeing Ogrémoch as a divine force, and they have developed a twisted dogma to explain how the evil of elemental earth is destined to remake the world and rule over all. The Black Earth priests form a cabal of leaders whose fanaticism and magical power serve as the backbone of the cult. Individuals of unusual power hold higher rank in the cult, but the priests provide the cult leader with his or her authority over the rest of Ogrémoch's followers.

```statblock
"name": "Black Earth Priest (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "[splint armor](/2-Mechanics/CLI/items/splint-armor.md)"
"hp": !!int "45"
"hit_dice": "7d8 + 14"
"stats":
- !!int "15"
- !!int "11"
- !!int "14"
- !!int "12"
- !!int "10"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "5"
  "Religion": !!int "3"
  "Persuasion": !!int "5"
"senses": "passive Perception 10"
"languages": "Common, Terran"
"cr": "3"
"traits":
- "desc": "The priest is a 5th-level spellcaster. Its spellcasting ability is Charisma\
    \ (spell save DC 13, +5 to hit with spell attacks). It knows the following sorcerer\
    \ spells:\n\nCantrips (at will): [acid splash](/2-Mechanics/CLI/spells/acid-splash.md),\
    \ [blade ward](/2-Mechanics/CLI/spells/blade-ward.md), [light](/2-Mechanics/CLI/spells/light.md),\
    \ [mending](/2-Mechanics/CLI/spells/mending.md), [mold earth](/2-Mechanics/CLI/spells/mold-earth-xge.md)\n\
    \n1st level (4 slots): [earth tremor](/2-Mechanics/CLI/spells/earth-tremor-xge.md),\
    \ [expeditious retreat](/2-Mechanics/CLI/spells/expeditious-retreat.md), [shield](/2-Mechanics/CLI/spells/shield.md)\n\
    \n2nd level (3 slots): [shatter](/2-Mechanics/CLI/spells/shatter.md), [spider\
    \ climb](/2-Mechanics/CLI/spells/spider-climb.md)\n\n3rd level (2 slots):\
    \ [slow](/2-Mechanics/CLI/spells/slow.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The priest makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 10 ft., one target. Hit: 7\
    \ (1d10 + 2) slashing damage."
  "name": "Glaive"
"reactions":
- "desc": "When the priest is subjected to an effect that would move it, knock it\
    \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone), or both, it can use its\
    \ reaction to be neither moved nor knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Unyielding"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Black%20Earth%20Priest.webp"
```
^statblock

```encounter-table
name: Black Earth Priest
creatures:
 - 1: Black Earth Priest
```