---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Pirate Deck Wizard"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 248
---
# [Pirate Deck Wizard](2-Mechanics\CLI\bestiary\humanoid/pirate-deck-wizard-gos.md)
*Source: Ghosts of Saltmarsh p. 248*  

These salt-encrusted practitioners of magic are at once learned and superstitious. The crews of pirate ships generally give their deck wizards a wide berth, as they magically step from place to place and unleash their briny magic against attackers. The ship Sea Ghost in The Sinister Secret of Saltmarsh is home to a pirate deck wizard named Punketah.

```statblock
"name": "Pirate Deck Wizard (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"stats":
- !!int "10"
- !!int "14"
- !!int "14"
- !!int "16"
- !!int "13"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "3"
  "Arcana": !!int "5"
"senses": "passive Perception 13"
"languages": "any one language (usually Common)"
"cr": "1"
"traits":
- "desc": "The deck wizard is a 4th-level spellcaster. Its spellcasting ability is\
    \ Intelligence (spell save DC 13, +5 to hit with spell attacks). It has the\
    \ following wizard spells prepared:\n\nCantrips (at will): [friends](/2-Mechanics/CLI/spells/friends.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md),\
    \ [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md)\n\n1st level (4 slots):\
    \ [disguise self](/2-Mechanics/CLI/spells/disguise-self.md), [fog cloud](/2-Mechanics/CLI/spells/fog-cloud.md),\
    \ [mage armor](/2-Mechanics/CLI/spells/mage-armor.md), [witch bolt](/2-Mechanics/CLI/spells/witch-bolt.md)\n\
    \n2nd level (3 slots): [gust of wind](/2-Mechanics/CLI/spells/gust-of-wind.md),\
    \ [Melf's acid arrow](/2-Mechanics/CLI/spells/melfs-acid-arrow.md), [misty step](/2-Mechanics/CLI/spells/misty-step.md)"
  "name": "Spellcasting"
- "desc": "The deck wizard has advantage on ability checks and saving throws to resist\
    \ being knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Sea Legs"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 3 (1d6)\
    \ bludgeoning damage."
  "name": "Quarterstaff"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Pirate%20Deck%20Wizard.webp"
```
^statblock

```encounter-table
name: Pirate Deck Wizard
creatures:
 - 1: Pirate Deck Wizard
```