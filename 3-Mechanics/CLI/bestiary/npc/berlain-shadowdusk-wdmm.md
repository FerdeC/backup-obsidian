---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/12
- monster/size/medium
- monster/type/aberration
aliases: ["Berlain Shadowdusk"]
NoteIcon: monster
BestiaryType: aberration
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 283
---
# [Berlain Shadowdusk](2-Mechanics\CLI\bestiary\npc/berlain-shadowdusk-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 283*  

A little over a year ago, Berlain and her brother Korva briefly entered the Far Realm, whereupon they became fused into a single physical form. This merging obliterated most of Korva's body and personality, leaving Berlain with an extra mouth and an extra set of arms that once belonged to her brother. She also inherited a few of his internal organs and personality traits. She can speak using one or both of her mouths.

Berlain has dirty blonde hair, piercing dark eyes, and two mouths where one would normally be—one below the other, canted at an angle. Sprouting from her misshapen shoulders are two pairs of arms—her original limbs above those of her brother. She wears a poorly stitched robe made from other garments and designed to fit her mutated form.

```statblock
"name": "Berlain Shadowdusk (WDMM)"
"size": "Medium"
"type": "aberration"
"alignment": "Chaotic Evil"
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
"senses": "passive Perception 12"
"languages": "Common, Deep Speech, Grell, Undercommon"
"cr": "12"
"traits":
- "desc": "Berlain is an 18th-level spellcaster. Her spellcasting ability is Intelligence\
    \ (spell save DC 17, +9 to hit with spell attacks). Berlain can cast [disguise\
    \ self](/2-Mechanics/CLI/spells/disguise-self.md) and invisibility at will and\
    \ has the following wizard spells prepared:\n\nCantrips (at will): [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md), [shocking grasp](/2-Mechanics/CLI/spells/shocking-grasp.md)\n\
    \n1st level (4 slots): [detect magic](/2-Mechanics/CLI/spells/detect-magic.md),\
    \ [identify](/2-Mechanics/CLI/spells/identify.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md),\
    \ [magic missile](/2-Mechanics/CLI/spells/magic-missile.md)\n\n2nd level (3\
    \ slots): [detect thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md), [mirror\
    \ image](/2-Mechanics/CLI/spells/mirror-image.md), [misty step](/2-Mechanics/CLI/spells/misty-step.md)\n\
    \n3rd level (3 slots): [counterspell](/2-Mechanics/CLI/spells/counterspell.md),\
    \ [fly](/2-Mechanics/CLI/spells/fly.md), [lightning bolt](/2-Mechanics/CLI/spells/lightning-bolt.md)\n\
    \n4th level (3 slots): [polymorph](/2-Mechanics/CLI/spells/polymorph.md),\
    \ [fire shield](/2-Mechanics/CLI/spells/fire-shield.md), [stoneskin](/2-Mechanics/CLI/spells/stoneskin.md)\n\
    \n5th level (3 slots): [cone of cold](/2-Mechanics/CLI/spells/cone-of-cold.md),\
    \ [scrying](/2-Mechanics/CLI/spells/scrying.md), [wall of force](/2-Mechanics/CLI/spells/wall-of-force.md)\n\
    \n6th level (1 slots): [globe of invulnerability](/2-Mechanics/CLI/spells/globe-of-invulnerability.md)\n\
    \n7th level (1 slots): [teleport](/2-Mechanics/CLI/spells/teleport.md)\n\n\
    8th level (1 slots): [mind blank](/2-Mechanics/CLI/spells/mind-blank.md)\n\
    \n9th level (1 slots): [time stop](/2-Mechanics/CLI/spells/time-stop.md)\n\
    \nBerlain casts these spells on herself before combat."
  "name": "Spellcasting"
- "desc": "Berlain has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "As a bonus action, Berlain can use her extra mouth and arms to cast any\
    \ cantrip she has prepared."
  "name": "Extra Parts"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Berlain%20Shadowdusk.webp"
```
^statblock

```encounter-table
name: Berlain Shadowdusk
creatures:
 - 1: Berlain Shadowdusk
```