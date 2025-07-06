---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Skyweaver"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 191
---
# [Skyweaver](2-Mechanics\CLI\bestiary\humanoid/skyweaver-pota.md)
*Source: Princes of the Apocalypse p. 191*  

Skyweavers brim with rage and desire, which makes them perfect vessels for the wildly destructive magic of the Cult of the Howling Hatred. In contrast to their hurricane counterparts in the air cult, skyweavers embrace the worship of Elemental Evil for a quick path to power. With little experience wielding the might of the elements, skyweavers thrill with the rush of releasing raw elemental energy.

```statblock
"name": "Skyweaver (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"stats":
- !!int "8"
- !!int "14"
- !!int "12"
- !!int "11"
- !!int "10"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Persuasion": !!int "5"
"senses": "passive Perception 10"
"languages": "Auran, Common"
"cr": "3"
"traits":
- "desc": "The Skyweaver is a 6th-level spellcaster. Its spellcasting ability is Charisma\
    \ (spell save DC 13, +5 to hit with spell attacks). It knows the following sorcerer\
    \ spells:\n\nCantrips (at will): [blade ward](/2-Mechanics/CLI/spells/blade-ward.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md), [message](/2-Mechanics/CLI/spells/message.md),\
    \ [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md), [shocking grasp](/2-Mechanics/CLI/spells/shocking-grasp.md)\n\
    \n1st level (4 slots): [feather fall](/2-Mechanics/CLI/spells/feather-fall.md),\
    \ [mage armor](/2-Mechanics/CLI/spells/mage-armor.md), [witch bolt](/2-Mechanics/CLI/spells/witch-bolt.md)\n\
    \n2nd level (3 slots): [gust of wind](/2-Mechanics/CLI/spells/gust-of-wind.md),\
    \ [invisibility](/2-Mechanics/CLI/spells/invisibility.md)\n\n3rd level (3 slots):\
    \ [fly](/2-Mechanics/CLI/spells/fly.md), [lightning bolt](/2-Mechanics/CLI/spells/lightning-bolt.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 3 (1d4 + 1) piercing damage."
  "name": "Dagger"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Skyweaver.webp"
```
^statblock

```encounter-table
name: Skyweaver
creatures:
 - 1: Skyweaver
```