---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/12
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Drivvin Freth"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 169
---
# [Drivvin Freth](2-Mechanics\CLI\bestiary\npc/drivvin-freth-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 169*  

```statblock
"name": "Drivvin Freth (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "99"
"hit_dice": "18d8 + 18"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "20"
- !!int "15"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Intelligence": !!int "9"
"skillsaves":
  "History": !!int "13"
  "Arcana": !!int "13"
"damage_resistances": "damage from spells; nonmagical bludgeoning, piercing, slashing\
  \ (from stoneskin)"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "Abyssal, Common, Dwarvish, Elvish, Goblin, Undercommon"
"cr": "12"
"traits":
- "desc": "Drivvin is an 18th-level spellcaster. Its spellcasting ability is Intelligence\
    \ (spell save DC 17, +9 to hit with spell attacks). Drivvin can cast [disguise\
    \ self](/2-Mechanics/CLI/spells/disguise-self.md) and [invisibility](/2-Mechanics/CLI/spells/invisibility.md)\
    \ at will and has the following wizard spells prepared:\n\nAt will: [disguise\
    \ self](/2-Mechanics/CLI/spells/disguise-self.md), [invisibility](/2-Mechanics/CLI/spells/invisibility.md)\n\
    \nCantrips (at will): [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md), [light](/2-Mechanics/CLI/spells/light.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md),\
    \ [shocking grasp](/2-Mechanics/CLI/spells/shocking-grasp.md)\n\n1st level (4\
    \ slots): [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [identify](/2-Mechanics/CLI/spells/identify.md),\
    \ [mage armor](/2-Mechanics/CLI/spells/mage-armor.md), [magic missile](/2-Mechanics/CLI/spells/magic-missile.md)\n\
    \n2nd level (3 slots): [detect thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md),\
    \ [mirror image](/2-Mechanics/CLI/spells/mirror-image.md), [misty step](/2-Mechanics/CLI/spells/misty-step.md)\n\
    \n3rd level (3 slots): [counterspell](/2-Mechanics/CLI/spells/counterspell.md),\
    \ [fly](/2-Mechanics/CLI/spells/fly.md), [lightning bolt](/2-Mechanics/CLI/spells/lightning-bolt.md)\n\
    \n4th level (3 slots): [banishment](/2-Mechanics/CLI/spells/banishment.md),\
    \ [fire shield](/2-Mechanics/CLI/spells/fire-shield.md), [stoneskin](/2-Mechanics/CLI/spells/stoneskin.md)\n\
    \n5th level (3 slots): [cone of cold](/2-Mechanics/CLI/spells/cone-of-cold.md),\
    \ [scrying](/2-Mechanics/CLI/spells/scrying.md), [wall of force](/2-Mechanics/CLI/spells/wall-of-force.md)\n\
    \n6th level (1 slots): [globe of invulnerability](/2-Mechanics/CLI/spells/globe-of-invulnerability.md)\n\
    \n7th level (1 slots): [teleport](/2-Mechanics/CLI/spells/teleport.md)\n\n\
    8th level (1 slots): [mind blank](/2-Mechanics/CLI/spells/mind-blank.md)\n\
    \n9th level (1 slots): [time stop](/2-Mechanics/CLI/spells/time-stop.md)\n\
    \nDrivvin casts these spells on itself before combat."
  "name": "Spellcasting"
- "desc": "Drivvin\n\nAt will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\
    \n1/day each: [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md)"
  "name": "Innate Spellcasting"
- "desc": "Drivvin has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Drivvin"
  "name": "Fey Ancestry"
- "desc": "Drivvin"
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
- "desc": "Drivvin magically summons a demon of challenge rating 6 or lower. The summoned\
    \ demon appears in an unoccupied space within 60 feet of him, acts as his ally,\
    \ and can't summon other demons. The summoned demon remains until Drivvin dismisses\
    \ it as an action or until the demon is reduced to 0 hit points."
  "name": "Summon Demon (1/Day)"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Drivvin%20Freth.webp"
```
^statblock

```encounter-table
name: Drivvin Freth
creatures:
 - 1: Drivvin Freth
```