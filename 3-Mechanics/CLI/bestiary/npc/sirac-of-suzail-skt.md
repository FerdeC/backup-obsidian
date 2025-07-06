---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/
- monster/size/medium
- monster/type/humanoid/chondathan-human
aliases: ["Sirac of Suzail"]
NoteIcon: monster
BestiaryType: humanoid (Chondathan human)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 247
---
# [Sirac of Suzail](2-Mechanics\CLI\bestiary\npc/sirac-of-suzail-skt.md)
*Source: Storm King's Thunder p. 247*  

An acolyte of Torm, Sirac grew up on the streets of Suzail, the capital of Cormyr. He came to Icewind Dale to become a knucklehead trout fisher but instead found religion. The misbegotten son of Artus Cimber, a renowned human adventurer, Sirac hasn't seen his father since he was a baby.

Ideal:"Without duty or loyalty, a man is nothing."

Bond:"Icewind Dale is where I belong for the rest of my life."

Flaw:"I am honest to a fault."

```statblock
"name": "Sirac of Suzail (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Chondathan human"
"alignment": "Lawful Good"
"ac": !!int "14"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "22"
"hit_dice": "5d8"
"stats":
- !!int "14"
- !!int "17"
- !!int "11"
- !!int "12"
- !!int "13"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "4"
  "Insight": !!int "3"
  "Survival": !!int "3"
"senses": "passive Perception 11"
"languages": "Common, Orc"
"traits":
- "desc": "An acolyte of Torm, Sirac grew up on the streets of Suzail, the capital\
    \ of Cormyr. He came to Icewind Dale to become a knucklehead trout fisher but\
    \ instead found religion. The misbegotten son of Artus Cimber, a renowned human\
    \ adventurer, Sirac hasn't seen his father since he was a baby.\n\nIdeal: \"Without\
    \ duty or loyalty, a man is nothing.\"\n\nBond: \"Icewind Dale is where i belong\
    \ for the rest of my life.\"\n\nFlaw: \"I am honest to a fault.\""
  "name": "Roleplaying Information"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +5 to hit, range 20/60 ft., one target. Hit:\
    \ 5 (1d4 + 3) piercing damage. Sirac carries six darts."
  "name": "Dart"
"reactions":
- "desc": "Sirac adds 2 to his AC against on melee attack that would hit him. To do\
    \ so, Sirac must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Sirac%20of%20Suzail.webp"
```
^statblock

```encounter-table
name: Sirac of Suzail
creatures:
 - 1: Sirac of Suzail
```