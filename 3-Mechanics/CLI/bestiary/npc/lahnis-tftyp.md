---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Lahnis"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 131
---
# [Lahnis](2-Mechanics\CLI\bestiary\npc/lahnis-tftyp.md)
*Source: Tales from the Yawning Portal p. 131*  

```statblock
"name": "Lahnis (TftYP)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"stats":
- !!int "9"
- !!int "14"
- !!int "12"
- !!int "17"
- !!int "12"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "5"
  "Intelligence": !!int "7"
"skillsaves":
  "History": !!int "7"
  "Arcana": !!int "7"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "9"
"traits":
- "desc": "Lahnis is a 12th-level spellcaster. Its spellcasting ability is Intelligence\
    \ (spell save DC 15, +7 to hit with spell attacks). Lahnis has the following\
    \ wizard spells prepared:\n\nCantrips (at will): [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md),\
    \ [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md)\n\n1st level (4 slots):\
    \ [burning hands](/2-Mechanics/CLI/spells/burning-hands.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md),\
    \ [magic missile](/2-Mechanics/CLI/spells/magic-missile.md)\n\n2nd level (3\
    \ slots): [mirror image](/2-Mechanics/CLI/spells/mirror-image.md), [misty step](/2-Mechanics/CLI/spells/misty-step.md),\
    \ [shatter](/2-Mechanics/CLI/spells/shatter.md)\n\n3rd level (3 slots): [counterspell](/2-Mechanics/CLI/spells/counterspell.md),\
    \ [fireball](/2-Mechanics/CLI/spells/fireball.md), [lightning bolt](/2-Mechanics/CLI/spells/lightning-bolt.md)\n\
    \n4th level (3 slots): [ice storm](/2-Mechanics/CLI/spells/ice-storm.md),\
    \ [stoneskin](/2-Mechanics/CLI/spells/stoneskin.md)\n\n5th level (2 slots):\
    \ [Bigby's hand](/2-Mechanics/CLI/spells/bigbys-hand.md), [cone of cold](/2-Mechanics/CLI/spells/cone-of-cold.md)\n\
    \n6th level (1 slots): [chain lightning](/2-Mechanics/CLI/spells/chain-lightning.md),\
    \ [wall of ice](/2-Mechanics/CLI/spells/wall-of-ice.md)\n\nEvocation spell"
  "name": "Spellcasting"
- "desc": "When Lahnis casts an evocation spell that forces other creatures it can\
    \ see to make a saving throw, it can choose a number of them equal to 1 + the\
    \ spell's level. These creatures automatically succeed on their saving throws\
    \ against the spell. If a successful save means a chosen creature would take half\
    \ damage from the spell, it instead takes no damage from it."
  "name": "Sculpt Spells"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 2 (1d6\
    \ - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two\
    \ hands."
  "name": "Quarterstaff"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Lahnis.webp"
```
^statblock

```encounter-table
name: Lahnis
creatures:
 - 1: Lahnis
```