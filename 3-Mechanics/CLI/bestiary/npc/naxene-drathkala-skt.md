---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/
- monster/size/medium
- monster/type/humanoid/turami-human
aliases: ["Naxene Drathkala"]
NoteIcon: monster
BestiaryType: humanoid (Turami human)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 252
---
# [Naxene Drathkala](2-Mechanics\CLI\bestiary\npc/naxene-drathkala-skt.md)
*Source: Storm King's Thunder p. 252*  

Goldenfields' crops are vital to Waterdeep's survival, which is why the Watchful Order of Magists and Protectors sent Naxene to make sure the temple-farm is adequately defended. At first she regarded the task as a punishment, but now she appreciates the peace and quiet.

Ideal:"There's no problem that can't be solved with magic."

Bond:"I have great respect for Lady Laeral Silverhand of Waterdeep. She and the Lords' Alliance are going to bring some much-needed order to this lawless land."

Flaw:"I'm too smart to be wrong about anything."

```statblock
"name": "Naxene Drathkala (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Turami human"
"alignment": "Neutral Good"
"ac": !!int "10"
"ac_class": "13 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "27"
"hit_dice": "6d8"
"stats":
- !!int "8"
- !!int "11"
- !!int "11"
- !!int "17"
- !!int "12"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "History": !!int "5"
  "Arcana": !!int "5"
"senses": "passive Perception 11"
"languages": "Common, Draconic, Dwarvish, Elvish"
"traits":
- "desc": "Naxene casts one of the following spells, using Intelligence as the spellcasting\
    \ ability (spell save DC 13; +5 to hit with spell attacks):\n\nAt will:\
    \ [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md) (1d10 fire damage), [light](/2-Mechanics/CLI/spells/light.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md)\n\n1/day each: [mage armor](/2-Mechanics/CLI/spells/mage-armor.md),\
    \ [magic missile](/2-Mechanics/CLI/spells/magic-missile.md), [suggestion](/2-Mechanics/CLI/spells/suggestion.md)"
  "name": "Spellcasting"
- "desc": "Goldenfields' crops are vital Waterdeep's survival, which is why the Watchful\
    \ Order of Magists and Protectors sent Naxene to make sure the temple-farm is\
    \ adequately defended. At first she regarded the task as a punishment, but now\
    \ she appreciates the peace and quiet.\n\nIdeal: \"There's no problem that can't\
    \ be solved with magic.\"\n\nBond: \"I have great respect for Lady Laeral Silverhand\
    \ of Waterdeep. She and the Lords' Alliance are going to bring some much-needed\
    \ order to this lawless land.\"\n\nFlaw: \"I'm too smart to be wrong about anything.\""
  "name": "Roleplaying Information"
"actions":
- "desc": "Melee Weapon Attack: +1 to hit, reach 5 ft., one creature. Hit: 2\
    \ (1d6 - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used\
    \ with two hands."
  "name": "Staff"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Naxene%20Drathkala.webp"
```
^statblock

```encounter-table
name: Naxene Drathkala
creatures:
 - 1: Naxene Drathkala
```