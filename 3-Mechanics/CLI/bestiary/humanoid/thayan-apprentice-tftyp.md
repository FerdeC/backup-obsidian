---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Thayan Apprentice"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 245
---
# [Thayan Apprentice](2-Mechanics\CLI\bestiary\humanoid/thayan-apprentice-tftyp.md)
*Source: Tales from the Yawning Portal p. 245*  

```statblock
"name": "Thayan Apprentice (TftYP)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Any Non-Good alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "15"
- !!int "13"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Arcana": !!int "4"
"senses": "passive Perception 11"
"languages": "Common, Thayan"
"cr": "2"
"traits":
- "desc": "The apprentice is a 4th-level spellcaster. Its spellcasting ability is\
    \ Intelligence (spell save DC 12, +4 to hit with spell attacks). It has the\
    \ following wizard spells prepared:\n\nCantrips (at will): [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md),\
    \ [shocking grasp](/2-Mechanics/CLI/spells/shocking-grasp.md)\n\n1st level (4\
    \ slots): [burning hands](/2-Mechanics/CLI/spells/burning-hands.md), [detect\
    \ magic](/2-Mechanics/CLI/spells/detect-magic.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md),\
    \ [shield](/2-Mechanics/CLI/spells/shield.md)\n\n2nd level (3 slots): [blur](/2-Mechanics/CLI/spells/blur.md),\
    \ [scorching ray](/2-Mechanics/CLI/spells/scorching-ray.md)"
  "name": "Spellcasting"
- "desc": "Within the Doomvault, the apprentice has advantage on saving throws against\
    \ being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed) or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Doomvault Devotion"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Thayan%20Apprentice.webp"
```
^statblock

```encounter-table
name: Thayan Apprentice
creatures:
 - 1: Thayan Apprentice
```