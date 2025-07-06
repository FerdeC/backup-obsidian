---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/6
- monster/size/medium
- monster/type/humanoid/tortle
aliases: ["Krull"]
NoteIcon: monster
BestiaryType: humanoid (tortle)
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 110
---
# [Krull](2-Mechanics\CLI\bestiary\npc/krull-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 110*  

```statblock
"name": "Krull (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "tortle"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"stats":
- !!int "20"
- !!int "14"
- !!int "15"
- !!int "12"
- !!int "20"
- !!int "12"
"speed": "30 ft."
"saves":
  "Charisma": !!int "4"
  "Wisdom": !!int "8"
"skillsaves":
  "Medicine": !!int "8"
  "Nature": !!int "4"
  "Arcana": !!int "4"
  "Survival": !!int "8"
"senses": "passive Perception 15"
"languages": "Aquan, Common, Draconic"
"cr": "6"
"traits":
- "desc": "Krull is a 14th-level spellcaster. His spellcasting ability is Wisdom (spell\
    \ save DC 16, +8 to hit with spell attacks). He has the following cleric spells\
    \ prepared:\n\nCantrips (at will): [chill touch](/2-Mechanics/CLI/spells/chill-touch.md),\
    \ [mending](/2-Mechanics/CLI/spells/mending.md), [resistance](/2-Mechanics/CLI/spells/resistance.md),\
    \ [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md), [spare the dying](/2-Mechanics/CLI/spells/spare-the-dying.md),\
    \ [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\n1st level (4 slots):\
    \ [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md), [detect evil and good](/2-Mechanics/CLI/spells/detect-evil-and-good.md),\
    \ [false life](/2-Mechanics/CLI/spells/false-life.md), [inflict wounds](/2-Mechanics/CLI/spells/inflict-wounds.md),\
    \ [ray of sickness](/2-Mechanics/CLI/spells/ray-of-sickness.md)\n\n2nd level\
    \ (3 slots): [blindness/deafness](/2-Mechanics/CLI/spells/blindness-deafness.md),\
    \ [gentle repose](/2-Mechanics/CLI/spells/gentle-repose.md), [hold person](/2-Mechanics/CLI/spells/hold-person.md),\
    \ [ray of enfeeblement](/2-Mechanics/CLI/spells/ray-of-enfeeblement.md), [spiritual\
    \ weapon](/2-Mechanics/CLI/spells/spiritual-weapon.md)\n\n3rd level (3 slots):\
    \ [animate dead](/2-Mechanics/CLI/spells/animate-dead.md), [magic circle](/2-Mechanics/CLI/spells/magic-circle.md),\
    \ [speak with dead](/2-Mechanics/CLI/spells/speak-with-dead.md), [spirit guardians](/2-Mechanics/CLI/spells/spirit-guardians.md),\
    \ [vampiric touch](/2-Mechanics/CLI/spells/vampiric-touch.md)\n\n4th level (3\
    \ slots): [banishment](/2-Mechanics/CLI/spells/banishment.md), [blight](/2-Mechanics/CLI/spells/blight.md),\
    \ [death ward](/2-Mechanics/CLI/spells/death-ward.md), [divination](/2-Mechanics/CLI/spells/divination.md),\
    \ [locate creature](/2-Mechanics/CLI/spells/locate-creature.md)\n\n5th level\
    \ (2 slots): [antilife shell](/2-Mechanics/CLI/spells/antilife-shell.md), [cloudkill](/2-Mechanics/CLI/spells/cloudkill.md),\
    \ [contagion](/2-Mechanics/CLI/spells/contagion.md), [greater restoration](/2-Mechanics/CLI/spells/greater-restoration.md)\n\
    \n6th level (1 slots): [create undead](/2-Mechanics/CLI/spells/create-undead.md),\
    \ [true seeing](/2-Mechanics/CLI/spells/true-seeing.md)\n\n7th level (1 slots):\
    \ [divine word](/2-Mechanics/CLI/spells/divine-word.md), [regenerate](/2-Mechanics/CLI/spells/regenerate.md)"
  "name": "Spellcasting"
- "desc": "Krull can hold his breath for 1 hour."
  "name": "Hold Breath"
- "desc": "Necrotic damage dealt by Krull's spells ignores resistance to necrotic\
    \ damage."
  "name": "Inescapable Destruction"
"actions":
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 7 (1d4\
    \ + 5) piercing damage."
  "name": "Claws"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d6 + 6) bludgeoning damage plus 9 (2d8) necrotic damage."
  "name": "+1 Maul"
- "desc": "Krull withdraws into his shell. Until he emerges as a bonus action, he\
    \ has a +4 bonus to AC and has advantage on Strength and Constitution saving throws.\
    \ While in his shell, Krull is [prone](/2-Mechanics/CLI/rules/conditions.md#prone),\
    \ his speed is 0 and can't increase, he has disadvantage on Dexterity saving throws,\
    \ he can't take reactions, and the only action he can take is to emerge from his\
    \ shell."
  "name": "Shell Defense"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Krull.webp"
```
^statblock

```encounter-table
name: Krull
creatures:
 - 1: Krull
```