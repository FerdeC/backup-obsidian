---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/6
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Preeta Kreepa"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 56
---
# [Preeta Kreepa](2-Mechanics\CLI\bestiary\npc/preeta-kreepa-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 56*  

Mages spend their lives in the study and practice of magic. Good-aligned mages offer counsel to nobles and others in power, while evil mages dwell in isolated sites to perform unspeakable experiments without interference.

Preeta served as an assistant to Arcturia, one of Halaster's apprentices, until Arcturia transformed her into a monstrous horror. Preeta looks like an old woman with two beholder eyestalks sprouting from her eye sockets. Her mouth, twice as large as it should be, is filled with sharp, pointed teeth. She wears the flayed, slippery, translucent skin of a kuo-toa as a cloak.

```statblock
"name": "Preeta Kreepa (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Neutral"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "40"
"hit_dice": "9d8"
"stats":
- !!int "9"
- !!int "14"
- !!int "11"
- !!int "17"
- !!int "12"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
  "Intelligence": !!int "6"
"skillsaves":
  "History": !!int "6"
  "Arcana": !!int "6"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Common, Dwarvish, Goblin, Undercommon"
"cr": "6"
"traits":
- "desc": "Preeta is a 9th-level spellcaster. Its spellcasting ability is Intelligence\
    \ (spell save DC 14, +6 to hit with spell attacks). Preeta has the following\
    \ wizard spells prepared:\n\nCantrips (at will): [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\n1st level\
    \ (4 slots): [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [mage\
    \ armor](/2-Mechanics/CLI/spells/mage-armor.md), [magic missile](/2-Mechanics/CLI/spells/magic-missile.md),\
    \ [shield](/2-Mechanics/CLI/spells/shield.md)\n\n2nd level (3 slots): [misty\
    \ step](/2-Mechanics/CLI/spells/misty-step.md), [suggestion](/2-Mechanics/CLI/spells/suggestion.md)\n\
    \n3rd level (3 slots): [counterspell](/2-Mechanics/CLI/spells/counterspell.md),\
    \ [fireball](/2-Mechanics/CLI/spells/fireball.md), [fly](/2-Mechanics/CLI/spells/fly.md)\n\
    \n4th level (3 slots): [greater invisibility](/2-Mechanics/CLI/spells/greater-invisibility.md),\
    \ [ice storm](/2-Mechanics/CLI/spells/ice-storm.md)\n\n5th level (1 slots):\
    \ [cone of cold](/2-Mechanics/CLI/spells/cone-of-cold.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"reactions":
- "desc": "As a bonus action or a reaction, Preeta can shoot one of the following\
    \ eye rays at one target she can see within 120 feet of her:\n\n- Fear Ray.\
    \ The target must succeed on a DC 15 Wisdom saving throw or be [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ for 1 minute. The target can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success.  \n- Paralyzing Ray. The\
    \ target must succeed on a DC 15 Constitution saving throw or be [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed)\
    \ for 1 minute. The target can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success.  "
  "name": "Eye Rays"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Preeta%20Kreepa.webp"
```
^statblock

```encounter-table
name: Preeta Kreepa
creatures:
 - 1: Preeta Kreepa
```