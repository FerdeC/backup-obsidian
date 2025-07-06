---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Phaia"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 132
---
# [Phaia](2-Mechanics\CLI\bestiary\npc/phaia-tftyp.md)
*Source: Tales from the Yawning Portal p. 132*  

```statblock
"name": "Phaia (TftYP)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
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
"damage_resistances": "necrotic"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "9"
"traits":
- "desc": "Phaia is a 12th-level spellcaster. Its spellcasting ability is Intelligence\
    \ (spell save DC 15, +7 to hit with spell attacks). Phaia has the following\
    \ wizard spells prepared:\n\nCantrips (at will): [chill touch](/2-Mechanics/CLI/spells/chill-touch.md),\
    \ [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [mending](/2-Mechanics/CLI/spells/mending.md)\n\n1st level (4 slots): [false\
    \ life](/2-Mechanics/CLI/spells/false-life.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md),\
    \ [ray of sickness](/2-Mechanics/CLI/spells/ray-of-sickness.md)\n\n2nd level\
    \ (3 slots): [blindness/deafness](/2-Mechanics/CLI/spells/blindness-deafness.md),\
    \ [ray of enfeeblement](/2-Mechanics/CLI/spells/ray-of-enfeeblement.md), [web](/2-Mechanics/CLI/spells/web.md)\n\
    \n3rd level (3 slots): [animate dead](/2-Mechanics/CLI/spells/animate-dead.md),\
    \ [bestow curse](/2-Mechanics/CLI/spells/bestow-curse.md), [vampiric touch](/2-Mechanics/CLI/spells/vampiric-touch.md)\n\
    \n4th level (3 slots): [blight](/2-Mechanics/CLI/spells/blight.md), [dimension\
    \ door](/2-Mechanics/CLI/spells/dimension-door.md), [stoneskin](/2-Mechanics/CLI/spells/stoneskin.md)\n\
    \n5th level (2 slots): [Bigby's hand](/2-Mechanics/CLI/spells/bigbys-hand.md),\
    \ [cloudkill](/2-Mechanics/CLI/spells/cloudkill.md)\n\n6th level (1 slots):\
    \ [circle of death](/2-Mechanics/CLI/spells/circle-of-death.md)\n\nNecromancy\
    \ spell of 1st level or higher"
  "name": "Spellcasting"
- "desc": "When necromancer kills a creature that is neither a construct nor undead\
    \ with a spell of 1st level or higher, Phaia regains hit points equal to twice\
    \ the spell's level, or three times if it is a necromancy spell."
  "name": "Grim Harvest (1/Turn)"
"actions":
- "desc": "Melee Spell Attack: +7 to hit, reach 5 ft., one creature. Hit: 5\
    \ (2d4) necrotic damage."
  "name": "Withering Touch"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Phaia.webp"
```
^statblock

```encounter-table
name: Phaia
creatures:
 - 1: Phaia
```