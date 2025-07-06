---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/dwarf
aliases: ["Grandolpha Muzgardt"]
NoteIcon: monster
BestiaryType: humanoid (dwarf)
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 176
---
# [Grandolpha Muzgardt](2-Mechanics\CLI\bestiary\npc/grandolpha-muzgardt-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 176*  

Grandolpha Muzgardt, the grand dame of the Muzgardt duergar clan, has recently arrived at the fortress after being invited here by Xardorok. The Muzgardts are based in Gracklstugh, a duergar city in the Underdark. They mass-produce and distribute a filthy duergar ale made from mushrooms. Xardorok has been eager to take a fourth wife and has had his eye on Grandolpha Muzgardt for many years. He asked Grandolpha to his fortress to give her a gift—a pseudodragon made of chardalyn (a pseudo-pseudodragon, if you will)—and make her an offer she can't refuse. Once he conquers Icewind Dale, he wants the Muzgardts to control the ale trade throughout his sunless surface kingdom.

Grandolpha, for her part, is too canny and jaded to fall for Xardorok's blunt attempt at seduction. She has begun plotting with disenfranchised advisors and warriors in his ranks to overthrow him when the moment is right. Ironically, despite his paranoia, Xardorok is too blinded by his admiration for Grandolpha to foresee her treachery.

Before entering combat, Grandolpha casts [stoneskin](/2-Mechanics/CLI/spells/stoneskin.md) on herself. Once her guards come to her rescue, she withdraws from combat and uses her [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md) spell to make enemies easier for her guards to hit. The chardalyn pseudodragon defends Grandolpha to the death.

```statblock
"name": "Grandolpha Muzgardt (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Lawful Evil"
"ac": !!int "9"
"hp": !!int "59"
"hit_dice": "7d8 + 28"
"stats":
- !!int "14"
- !!int "9"
- !!int "18"
- !!int "13"
- !!int "17"
- !!int "16"
"speed": "25 ft."
"damage_resistances": "poison"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Common, Dwarvish, Undercommon"
"cr": "2"
"traits":
- "desc": "Grandolpha's innate spellcasting ability is Wisdom (spell save DC 13).\
    \ She can innately cast the following spells, requiring no material components:\n\
    \nAt will: [druidcraft](/2-Mechanics/CLI/spells/druidcraft.md), [mending](/2-Mechanics/CLI/spells/mending.md),\
    \ [poison spray](/2-Mechanics/CLI/spells/poison-spray.md) (see \"Actions\" below)\n\
    \n3/day each: [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [enlarge/reduce](/2-Mechanics/CLI/spells/enlarge-reduce.md)\
    \ (self only), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md), [invisibility](/2-Mechanics/CLI/spells/invisibility.md)\
    \ (self only), [polymorph](/2-Mechanics/CLI/spells/polymorph.md), [stoneskin](/2-Mechanics/CLI/spells/stoneskin.md)\
    \ (self only)"
  "name": "Innate Spellcasting (Psionics)"
- "desc": "Grandolpha has advantage on saving throws against poison, spells, and illusions,\
    \ as well as to resist being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed)."
  "name": "Duergar Resilience"
- "desc": "While in sunlight, Grandolpha has disadvantage on attack rolls, as well\
    \ as on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Grandolpha extends her hand toward a creature she can see within 10 feet\
    \ of her and projects a puff of noxious gas from her palm. The creature must succeed\
    \ on a DC 13 Constitution saving throw or take 13 (2d12) poison damage."
  "name": "Poison Spray (Cantrip)"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Grandolpha%20Muzgardt.webp"
```
^statblock

```encounter-table
name: Grandolpha Muzgardt
creatures:
 - 1: Grandolpha Muzgardt
```