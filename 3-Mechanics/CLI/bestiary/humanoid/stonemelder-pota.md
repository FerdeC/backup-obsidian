---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Stonemelder"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 197
---
# [Stonemelder](2-Mechanics\CLI\bestiary\humanoid/stonemelder-pota.md)
*Source: Princes of the Apocalypse p. 197*  

Stonemelders are spellcasters who gain their power from Ogrémoch, using elemental earth magic to sheathe their bodies in carapaces of rock. They are elite champions of the cult and answer only to the cult leaders. Not even the Black Earth priests tell stonemelders what to do.

Each stonemelder carries a weapon known as a Black Earth rod. Such a rod is like an ordinary mace, but in the hands of a stonemelder, it serves as a conduit for Ogrémoch's wrath.

```statblock
"name": "Stonemelder (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "[splint armor](/2-Mechanics/CLI/items/splint-armor.md)"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"stats":
- !!int "15"
- !!int "10"
- !!int "16"
- !!int "12"
- !!int "11"
- !!int "17"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "5"
  "Perception": !!int "2"
"senses": "tremorsense 30 ft., passive Perception 12"
"languages": "Common, Terran"
"cr": "4"
"traits":
- "desc": "The Stonemelder is a 7th-level spellcaster. Its spellcasting ability is\
    \ Charisma (spell save DC 13, +5 to hit with spell attacks). It knows the following\
    \ sorcerer spells:\n\nCantrips (at will): [acid splash](/2-Mechanics/CLI/spells/acid-splash.md),\
    \ [blade ward](/2-Mechanics/CLI/spells/blade-ward.md), [light](/2-Mechanics/CLI/spells/light.md),\
    \ [mending](/2-Mechanics/CLI/spells/mending.md), [mold earth](/2-Mechanics/CLI/spells/mold-earth-xge.md)\n\
    \n1st level (4 slots): [expeditious retreat](/2-Mechanics/CLI/spells/expeditious-retreat.md),\
    \ [false life](/2-Mechanics/CLI/spells/false-life.md), [shield](/2-Mechanics/CLI/spells/shield.md)\n\
    \n2nd level (3 slots): [Maximilian's earthen grasp](/2-Mechanics/CLI/spells/maximilians-earthen-grasp-xge.md),\
    \ [shatter](/2-Mechanics/CLI/spells/shatter.md)\n\n3rd level (3 slots): [erupting\
    \ earth](/2-Mechanics/CLI/spells/erupting-earth-xge.md), [meld into stone](/2-Mechanics/CLI/spells/meld-into-stone.md)\n\
    \n4th level (1 slots): [stoneskin](/2-Mechanics/CLI/spells/stoneskin.md)"
  "name": "Spellcasting"
- "desc": "When the Stonemelder dies, it turns to stone and explodes in a burst of\
    \ rock shards, becoming a smoking pile of rubble. Each creature within 10 feet\
    \ of the exploding Stonemelder must make a DC 14 Dexterity saving throw, taking\
    \ 11 (2d10) bludgeoning damage on a failed save, or half as much damage on a\
    \ successful one."
  "name": "Death Burst"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage. The Stonemelder can also expend a spell slot to deal\
    \ extra damage, dealing 2d8 bludgeoning damage for a 1st level slot, plus an\
    \ additional 1d8 for each level of the slot above 1st."
  "name": "Black Earth Rod"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Stonemelder.webp"
```
^statblock

```encounter-table
name: Stonemelder
creatures:
 - 1: Stonemelder
```