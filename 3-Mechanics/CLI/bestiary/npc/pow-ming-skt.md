---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/6
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Pow Ming"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 216
---
# [Pow Ming](2-Mechanics\CLI\bestiary\npc/pow-ming-skt.md)
*Source: Storm King's Thunder p. 216*  

```statblock
"name": "Pow Ming (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral"
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
"senses": "passive Perception 11"
"languages": "Common, Draconic, Dwarvish, Elvish"
"cr": "6"
"traits":
- "desc": "Pow is a 9th-level spellcaster. Her spellcasting ability is Intelligence\
    \ (spell save DC 14, +6 to hit with spell attacks). Pow has the following wizard\
    \ spells prepared:\n\nCantrips (at will): [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\n1st level\
    \ (4 slots): [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [mage\
    \ armor](/2-Mechanics/CLI/spells/mage-armor.md), [magic missile](/2-Mechanics/CLI/spells/magic-missile.md),\
    \ [shield](/2-Mechanics/CLI/spells/shield.md)\n\n2nd level (3 slots): [detect\
    \ thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md), [suggestion](/2-Mechanics/CLI/spells/suggestion.md)\n\
    \n3rd level (3 slots): [counterspell](/2-Mechanics/CLI/spells/counterspell.md),\
    \ [fireball](/2-Mechanics/CLI/spells/fireball.md), [fly](/2-Mechanics/CLI/spells/fly.md)\n\
    \n4th level (3 slots): [greater invisibility](/2-Mechanics/CLI/spells/greater-invisibility.md),\
    \ [ice storm](/2-Mechanics/CLI/spells/ice-storm.md)\n\n5th level (1 slots):\
    \ [cone of cold](/2-Mechanics/CLI/spells/cone-of-cold.md)"
  "name": "Spellcasting"
- "desc": "Pow carries a [bag of holding](/2-Mechanics/CLI/items/bag-of-holding.md)\
    \ and wears a [robe of serpents](/2-Mechanics/CLI/items/robe-of-serpents-skt.md)\
    \ with six snakes."
  "name": "Special Equipment"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Pow%20Ming.webp"
```
^statblock

```encounter-table
name: Pow Ming
creatures:
 - 1: Pow Ming
```