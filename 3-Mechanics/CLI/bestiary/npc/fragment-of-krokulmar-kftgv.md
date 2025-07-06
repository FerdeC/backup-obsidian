---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/0
- monster/size/tiny
- monster/type/aberration
aliases: ["Fragment of Krokulmar"]
NoteIcon: monster
BestiaryType: aberration
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 53
---
# [Fragment of Krokulmar](2-Mechanics\CLI\bestiary\npc/fragment-of-krokulmar-kftgv.md)
*Source: Keys from the Golden Vault p. 53*  

```statblock
"name": "Fragment of Krokulmar (KftGV)"
"size": "Tiny"
"type": "aberration"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "10"
"hit_dice": "3d4 + 3"
"stats":
- !!int "4"
- !!int "16"
- !!int "12"
- !!int "16"
- !!int "16"
- !!int "16"
"speed": "0 ft."
"skillsaves":
  "Stealth": !!int "7"
  "History": !!int "7"
  "Arcana": !!int "7"
  "Persuasion": !!int "7"
"damage_immunities": "psychic"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Deep Speech, telepathy 60 ft."
"cr": "0"
"actions":
- "desc": "The fragment touches one creature that has 0 hit points in the fragment's\
    \ space. The target regains 10 hit points, and each creature within 10 feet of\
    \ the healed creature takes 3 (1d6) psychic damage."
  "name": "Psionic Revitalization"
- "desc": "Until the start of the fragment's next turn, any attack roll made against\
    \ the fragment has disadvantage, and the fragment makes saving throws with advantage."
  "name": "Squirming Dodge"
"source":
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/KftGV/Fragment%20of%20Krokulmar.webp"
```
^statblock

```encounter-table
name: Fragment of Krokulmar
creatures:
 - 1: Fragment of Krokulmar
```