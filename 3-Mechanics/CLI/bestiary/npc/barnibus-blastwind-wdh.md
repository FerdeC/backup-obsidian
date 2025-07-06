---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Barnibus Blastwind"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 195
---
# [Barnibus Blastwind](2-Mechanics\CLI\bestiary\npc/barnibus-blastwind-wdh.md)
*Source: Waterdeep: Dragon Heist p. 195*  

Barnibus works for the Watchful Order of Magists and Protectors, investigating crimes that involve the use of magic. He comes across as prickly and secretive, confiding only in Saeth Cromley, a retired sergeant of the City Watch who assists in many of his investigations.

A lifelong bachelor, Barnibus has a small, tidy estate in the Sea Ward that he inherited from his grandmother. When not serving the Watchful Order, he spends his days reading and writing books in his library.

Barnibus uses spells that help him investigate crimes, pry secrets from the minds of suspects, and locate missing persons. He finds violence appalling and would never use his magic to inflict harm on others-even those who harm him.

```statblock
"name": "Barnibus Blastwind (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Good"
"ac": !!int "10"
"ac_class": "13 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "24"
"hit_dice": "7d8 - 7"
"stats":
- !!int "9"
- !!int "10"
- !!int "9"
- !!int "17"
- !!int "15"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
  "Intelligence": !!int "5"
"skillsaves":
  "Investigation": !!int "7"
  "Insight": !!int "6"
  "Perception": !!int "4"
  "Arcana": !!int "5"
"senses": "passive Perception 14"
"languages": "Common, Draconic, Dwarvish, Halfling"
"cr": "2"
"traits":
- "desc": "Barnibus is a 7th-level spellcaster. His spellcasting ability is Intelligence\
    \ (spell save DC 13, +5 to hit with spell attacks) He has the following wizard\
    \ spells prepared:\n\nCantrips (at will): [blade ward](/2-Mechanics/CLI/spells/blade-ward.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [message](/2-Mechanics/CLI/spells/message.md)\n\n1st level (4 slots): [comprehend\
    \ languages](/2-Mechanics/CLI/spells/comprehend-languages.md), [identify](/2-Mechanics/CLI/spells/identify.md),\
    \ [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md),\
    \ [shield](/2-Mechanics/CLI/spells/shield.md)\n\n2nd level (3 slots): [detect\
    \ thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md), [suggestion](/2-Mechanics/CLI/spells/suggestion.md)\n\
    \n3rd level (3 slots): [clairvoyance](/2-Mechanics/CLI/spells/clairvoyance.md),\
    \ [sending](/2-Mechanics/CLI/spells/sending.md)\n\n4th level (1 slots): [locate\
    \ creature](/2-Mechanics/CLI/spells/locate-creature.md), [Otiluke's resilient\
    \ sphere](/2-Mechanics/CLI/spells/otilukes-resilient-sphere.md)"
  "name": "Spellcasting"
- "desc": "Barnibus carries a [wand of magic detection](/2-Mechanics/CLI/items/wand-of-magic-detection.md).\
    \ (spell included in spell list below but does not use a slot when cast from the\
    \ wand)"
  "name": "Special Equipment"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +2 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 2 (1d4) piercing damage."
  "name": "Dagger"
"source":
- "WDH"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDH/Barnibus%20Blastwind.webp"
```
^statblock

```encounter-table
name: Barnibus Blastwind
creatures:
 - 1: Barnibus Blastwind
```