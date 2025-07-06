---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/8
- monster/size/medium
- monster/type/humanoid/fire-genasi
aliases: ["Bastian Thermandar"]
NoteIcon: monster
BestiaryType: humanoid (Fire genasi)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 201
---
# [Bastian Thermandar](2-Mechanics\CLI\bestiary\npc/bastian-thermandar-pota.md)
*Source: Princes of the Apocalypse p. 201*  

Like many in the fire cult, Bastian burns with an inner fire, but his fire is ambition, rather than a wish to see the world burn. Bastian is scheming to supplant Vanifer and claim Tinderstrike for himself.

As a practitioner of the arcane arts who learned much of his fire magic from Vanifer herself, Bastian relies on his spells in a fight, and he is a "quick-burning" sort who tries to deliver maximum impact early in the fight. If he knows a fight is coming but can't preemptively strike, Bastian becomes more cautious, casting wall of fire to protect himself before he hurls magic into the fray.

```statblock
"name": "Bastian Thermandar (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "Fire genasi"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"stats":
- !!int "12"
- !!int "14"
- !!int "15"
- !!int "11"
- !!int "9"
- !!int "18"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "7"
  "Arcana": !!int "3"
"damage_resistances": "fire"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Ignan"
"cr": "8"
"traits":
- "desc": "Bastian's innate spellcasting ability is Constitution (spell save DC 13,\
    \ +5 to hit with spell attacks). He can innately cast the following spells:\n\
    \nAt will: [produce flame](/2-Mechanics/CLI/spells/produce-flame.md)\n\n1/day:\
    \ [burning hands](/2-Mechanics/CLI/spells/burning-hands.md)"
  "name": "Innate Spellcasting"
- "desc": "Bastian is a 9th-level spellcaster. His spellcasting ability is Charisma\
    \ (spell save DC 15, +7 to hit with spell attacks). Bastian knows the following\
    \ sorcerer spells:\n\nCantrips (at will): [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [message](/2-Mechanics/CLI/spells/message.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md), [shocking grasp](/2-Mechanics/CLI/spells/shocking-grasp.md)\n\
    \n1st level (4 slots): [mage armor](/2-Mechanics/CLI/spells/mage-armor.md),\
    \ [magic missile](/2-Mechanics/CLI/spells/magic-missile.md), [shield](/2-Mechanics/CLI/spells/shield.md)\n\
    \n2nd level (3 slots): [misty step](/2-Mechanics/CLI/spells/misty-step.md),\
    \ [scorching ray](/2-Mechanics/CLI/spells/scorching-ray.md)\n\n3rd level (3\
    \ slots): [counterspell](/2-Mechanics/CLI/spells/counterspell.md), [fireball](/2-Mechanics/CLI/spells/fireball.md)\n\
    \n4th level (3 slots): [dimension door](/2-Mechanics/CLI/spells/dimension-door.md),\
    \ [wall of fire](/2-Mechanics/CLI/spells/wall-of-fire.md)\n\n5th level (1 slots):\
    \ [hold monster](/2-Mechanics/CLI/spells/hold-monster.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Bastian%20Thermandar.webp"
```
^statblock

```encounter-table
name: Bastian Thermandar
creatures:
 - 1: Bastian Thermandar
```