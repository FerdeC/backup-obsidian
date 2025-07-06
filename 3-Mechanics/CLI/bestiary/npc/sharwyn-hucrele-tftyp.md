---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Sharwyn Hucrele"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 242
---
# [Sharwyn Hucrele](2-Mechanics\CLI\bestiary\npc/sharwyn-hucrele-tftyp.md)
*Source: Tales from the Yawning Portal p. 242*  

```statblock
"name": "Sharwyn Hucrele (TftYP)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "Barkskin trait"
"hp": !!int "13"
"hit_dice": "2d8 + 4"
"stats":
- !!int "11"
- !!int "13"
- !!int "14"
- !!int "16"
- !!int "14"
- !!int "9"
"speed": "30 ft."
"skillsaves":
  "Insight": !!int "4"
  "Arcana": !!int "5"
  "Persuasion": !!int "1"
"senses": "passive Perception 12"
"languages": "Common, Draconic, Goblin"
"cr": "1/2"
"traits":
- "desc": "Sharwyn is a 1st-level spellcaster. Her spellcasting ability is Intelligence\
    \ (spell save DC 13, +5 to hit with spell attacks). She has the following wizard\
    \ spells prepared:\n\nCantrips (at will): [light](/2-Mechanics/CLI/spells/light.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md), [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md)\n\
    \n1st level (2 slots): [color spray](/2-Mechanics/CLI/spells/color-spray.md),\
    \ [magic missile](/2-Mechanics/CLI/spells/magic-missile.md), [shield](/2-Mechanics/CLI/spells/shield.md),\
    \ [sleep](/2-Mechanics/CLI/spells/sleep.md)"
  "name": "Spellcasting"
- "desc": "Sharwyn's AC can't be lower than 16."
  "name": "Barkskin"
- "desc": "Sharwyn has a [spellbook](/2-Mechanics/CLI/items/spellbook.md) that contains\
    \ the spells listed in her Spellcasting trait, plus [detect magic](/2-Mechanics/CLI/spells/detect-magic.md)\
    \ and [silent image](/2-Mechanics/CLI/spells/silent-image.md)."
  "name": "Special Equipment"
- "desc": "If the Gulthias Tree dies, Sharwyn dies 24 hours later."
  "name": "Tree Thrall"
"actions":
- "desc": "Melee Weapon Attack: +4, reach 5 ft., one target. Hit: 4 (1d4 +\
    \ 2) piercing damage."
  "name": "Dagger"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Sharwyn%20Hucrele.webp"
```
^statblock

```encounter-table
name: Sharwyn Hucrele
creatures:
 - 1: Sharwyn Hucrele
```