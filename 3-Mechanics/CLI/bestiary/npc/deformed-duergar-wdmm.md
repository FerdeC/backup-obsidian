---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/dwarf
aliases: ["Deformed Duergar"]
NoteIcon: monster
BestiaryType: humanoid (dwarf)
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 180
---
# [Deformed Duergar](2-Mechanics\CLI\bestiary\npc/deformed-duergar-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 180*  

This creature used to be two separate duergar, a male named Blork and a female named Muatha. Arcturia fused them together into a single creature by using magic that only a [wish](/2-Mechanics/CLI/spells/wish.md) spell can undo. Both skulls merged into one bulbous head that has three ears, three eyes, two noses, and two mouths. It has a third arm on the right side of its body, and its left leg splits into two at the knee, giving it three feet. The transformation drove the poor creature insane, and it regards all other creatures as threats that must be destroyed.

```statblock
"name": "Deformed Duergar (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "[scale mail](/2-Mechanics/CLI/items/scale-mail.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "40"
"hit_dice": "4d8 + 4"
"stats":
- !!int "14"
- !!int "11"
- !!int "14"
- !!int "11"
- !!int "10"
- !!int "9"
"speed": "25 ft."
"damage_resistances": "poison"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "Dwarvish, Undercommon"
"cr": "1"
"traits":
- "desc": "The duergar can make an attack with its javelin as a bonus action."
  "name": "Third Arm"
- "desc": "The duergar has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks and on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned),\
    \ and knocked [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)."
  "name": "Merged Heads"
- "desc": "The duergar has advantage on saving throws against poison, spells, and\
    \ illusions, as well as to resist being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed)."
  "name": "Duergar Resilience"
- "desc": "While in sunlight, the duergar has disadvantage on attack rolls, as well\
    \ as on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "For 1 minute, the duergar magically increases in size, along with anything\
    \ it is wearing or carrying. While enlarged, the duergar is Large, doubles its\
    \ damage dice on Strength-based weapon attacks (included in the attacks), and\
    \ makes Strength checks and Strength saving throws with advantage. If the duergar\
    \ lacks the room to become Large, it attains the maximum size possible in the\
    \ space available."
  "name": "Enlarge (Recharges after a Short or Long Rest)"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) piercing damage, or 11 (2d8 + 2) piercing damage while enlarged."
  "name": "War Pick"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 5 (1d6 + 2) piercing damage, or 9 (2d6 + 2) piercing\
    \ damage while enlarged."
  "name": "Javelin"
- "desc": "The duergar magically turns [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ until it attacks, casts a spell, or uses its Enlarge, or until its [concentration](/2-Mechanics/CLI/rules/conditions.md#concentration)\
    \ is broken, up to 1 hour (as if concentrating on a spell). Any equipment the\
    \ duergar wears or carries is [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ with it."
  "name": "Invisibility (Recharges after a Short or Long Rest)"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Deformed%20Duergar.webp"
```
^statblock

```encounter-table
name: Deformed Duergar
creatures:
 - 1: Deformed Duergar
```