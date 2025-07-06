---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/12
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Wyllow"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 70
---
# [Wyllow](2-Mechanics\CLI\bestiary\npc/wyllow-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 70*  

Wyllow is a moon elf druid with eyes as green as emeralds. Butterflies nest in her tangled black hair, and small critters gather around her feet.

```statblock
"name": "Wyllow (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "16"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "132"
"hit_dice": "24d8 + 24"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "12"
- !!int "20"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "9"
  "Intelligence": !!int "5"
"skillsaves":
  "Medicine": !!int "9"
  "Nature": !!int "5"
  "Perception": !!int "9"
"senses": "darkvision 60 ft., passive Perception 19"
"languages": "Common, Druidic, Elvish"
"cr": "12"
"traits":
- "desc": "Wyllow is an 18th-level spellcaster. Its spellcasting ability is Wisdom\
    \ (spell save DC 17, +9 to hit with spell attacks). It has the following druid\
    \ spells prepared:\n\nCantrips (at will): [druidcraft](/2-Mechanics/CLI/spells/druidcraft.md),\
    \ [mending](/2-Mechanics/CLI/spells/mending.md), [poison spray](/2-Mechanics/CLI/spells/poison-spray.md),\
    \ [produce flame](/2-Mechanics/CLI/spells/produce-flame.md)\n\n1st level (4\
    \ slots): [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md), [entangle](/2-Mechanics/CLI/spells/entangle.md),\
    \ [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md), [speak with animals](/2-Mechanics/CLI/spells/speak-with-animals.md)\n\
    \n2nd level (3 slots): [animal messenger](/2-Mechanics/CLI/spells/animal-messenger.md),\
    \ [beast sense](/2-Mechanics/CLI/spells/beast-sense.md), [hold person](/2-Mechanics/CLI/spells/hold-person.md)\n\
    \n3rd level (3 slots): [conjure animals](/2-Mechanics/CLI/spells/conjure-animals.md),\
    \ [meld into stone](/2-Mechanics/CLI/spells/meld-into-stone.md), [water breathing](/2-Mechanics/CLI/spells/water-breathing.md)\n\
    \n4th level (3 slots): [dominate beast](/2-Mechanics/CLI/spells/dominate-beast.md),\
    \ [locate creature](/2-Mechanics/CLI/spells/locate-creature.md), [stoneskin](/2-Mechanics/CLI/spells/stoneskin.md),\
    \ [wall of fire](/2-Mechanics/CLI/spells/wall-of-fire.md)\n\n5th level (3 slots):\
    \ [commune with nature](/2-Mechanics/CLI/spells/commune-with-nature.md), [mass\
    \ cure wounds](/2-Mechanics/CLI/spells/mass-cure-wounds.md), [tree stride](/2-Mechanics/CLI/spells/tree-stride.md)\n\
    \n6th level (1 slots): [heal](/2-Mechanics/CLI/spells/heal.md), [heroes' feast](/2-Mechanics/CLI/spells/heroes-feast.md),\
    \ [sunbeam](/2-Mechanics/CLI/spells/sunbeam.md)\n\n7th level (1 slots): [fire\
    \ storm](/2-Mechanics/CLI/spells/fire-storm.md)\n\n8th level (1 slots): [animal\
    \ shapes](/2-Mechanics/CLI/spells/animal-shapes.md)\n\n9th level (1 slots):\
    \ [foresight](/2-Mechanics/CLI/spells/foresight.md)"
  "name": "Spellcasting"
- "desc": "Wyllow"
  "name": "Fey Ancestry"
- "desc": "Wyllow"
  "name": "Mask of the Wild"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) slashing damage."
  "name": "Scimitar"
- "desc": "Wyllow magically polymorphs into a beast or elemental with a challenge\
    \ rating of 6 or less, and can remain in this form for up to 9 hours. Wyllow can\
    \ choose whether its equipment falls to the ground, melds with its new form, or\
    \ is worn by the new form. Wyllow reverts to its true form if it dies or falls\
    \ [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious). Wyllow can\
    \ revert to its true form using a bonus action on its turn.\n\nWhile in a new\
    \ form, Wyllow retains its game statistics and ability to speak, but its AC, movement\
    \ modes, Strength, and Dexterity are replaced by those of the new form, and it\
    \ gains any special senses, proficiencies, traits, actions, and reactions (except\
    \ class features, legendary actions, and lair actions) that the new form has but\
    \ that it lacks. It can cast its spells with verbal or somatic components in its\
    \ new form.\n\nThe new form's attacks count as magical for the purpose of overcoming\
    \ resistances and immunity to nonmagical attacks."
  "name": "Change Shape (2/Day)"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Wyllow.webp"
```
^statblock

```encounter-table
name: Wyllow
creatures:
 - 1: Wyllow
```