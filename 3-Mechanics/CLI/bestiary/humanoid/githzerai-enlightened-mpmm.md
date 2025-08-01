---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/10
- monster/environment/desert
- monster/environment/mountain
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid/gith
aliases: ["Githzerai Enlightened"]
NoteIcon: monster
BestiaryType: humanoid (gith)
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 143, Mordenkainen's Tome of Foes p. 208
---
# [Githzerai Enlightened](2-Mechanics\CLI\bestiary\humanoid/githzerai-enlightened-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 143, Mordenkainen's Tome of Foes p. 208*  

Some spiritual githzerai spend long hours in meditation to transcend the limits of their forms and to apprehend the nature of reality. Zerths who complete the next tier of their training become known as the enlightened.

## Githzerai

Githzerai are otherworldly folk with psionic powers who share an ancestral link to githyanki (also in this book). The githzerai followers of the great leader Zaerith Menyar-Ag-Gith are an ascetic people who live apart from the rest of the cosmos, within the confines of fortresses floating through the chaos of Limbo. Instead of imposing their will on other peoples, they focus on controlling and manipulating their endlessly malleable home.

```statblock
"name": "Githzerai Enlightened (MPMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "gith"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "psychic defense"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"stats":
- !!int "14"
- !!int "19"
- !!int "16"
- !!int "17"
- !!int "19"
- !!int "13"
"speed": "40 ft."
"saves":
  "Dexterity": !!int "8"
  "Wisdom": !!int "8"
  "Intelligence": !!int "7"
  "Strength": !!int "6"
"skillsaves":
  "Insight": !!int "8"
  "Perception": !!int "8"
  "Arcana": !!int "7"
"senses": "passive Perception 18"
"languages": "Gith"
"cr": "10"
"traits":
- "desc": "The githzerai casts one of the following spells, requiring no spell components\
    \ and using Wisdom as the spellcasting ability (spell save DC 16):\n\nAt will:\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md) (the hand is invisible)\n\n\
    1/day each: [plane shift](/2-Mechanics/CLI/spells/plane-shift.md), [teleport](/2-Mechanics/CLI/spells/teleport.md)\n\
    \n3/day: [see invisibility](/2-Mechanics/CLI/spells/see-invisibility.md)"
  "name": "Spellcasting (Psionics)"
- "desc": "While the githzerai is wearing no armor and wielding no shield, its AC\
    \ includes its Wisdom modifier."
  "name": "Psychic Defense"
"actions":
- "desc": "The githzerai makes three Unarmed Strike attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) bludgeoning damage plus 18 (4d8) psychic damage."
  "name": "Unarmed Strike"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. Hit: 13\
    \ (2d8 + 4) bludgeoning damage plus 52 (8d12) psychic damage. The target must\
    \ succeed on a DC 16 Wisdom saving throw or move 1 round forward in time. A target\
    \ moved forward in time vanishes for the duration. When the effect ends, the target\
    \ reappears in the space it left or in an unoccupied space nearest to that space\
    \ if it's occupied."
  "name": "Temporal Strike (Recharge 6)"
"reactions":
- "desc": "When the githzerai falls, it reduces any falling damage it takes by 50."
  "name": "Slow Fall"
"source":
- "MPMM"
- "MTF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPMM/Githzerai%20Enlightened.webp"
```
^statblock

```encounter-table
name: Githzerai Enlightened
creatures:
 - 1: Githzerai Enlightened
```

## Environment

desert, mountain, urban