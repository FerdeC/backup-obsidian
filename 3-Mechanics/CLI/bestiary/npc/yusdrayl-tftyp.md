---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/1
- monster/size/small
- monster/type/humanoid/kobold
aliases: ["Yusdrayl"]
NoteIcon: monster
BestiaryType: humanoid (kobold)
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 248
---
# [Yusdrayl](2-Mechanics\CLI\bestiary\npc/yusdrayl-tftyp.md)
*Source: Tales from the Yawning Portal p. 248*  

Kobolds are craven reptilian humanoids that worship evil dragons as demigods and serve them as minions and toadies. Kobolds inhabit dragons' lairs when they can but more commonly infest dungeons, gathering treasures and trinkets to add to their own tiny hoards.

## Strength in Numbers

 Kobolds are egg-laying creatures. They mature quickly and can live to be "great wyrms" more than a century old. However, many kobolds perish before they reach the end of their first decade. Physically weak, they are easy prey for predators. This vulnerability forces them to band together. Their superior numbers can win battles against powerful adversaries, but often with massive casualties on the kobold side.

## Tunnelers and Builders

Kobolds make up for their physical ineptitude with a cleverness for trap making and tunneling. Their lairs consist of low tunnels through which they move easily but which hinder larger humanoids. Kobolds also riddle their lairs with traps. The most insidious kobold traps make use of natural hazards and other creatures. A trip wire might connect to a spring-loaded trap that hurls clay pots of flesh-eating green slime or flings crates of venomous giant centipedes at intruders.

## The Lost God

In addition to the dragons they revere, kobolds worship a lesser god named Kurtulmak. Legends speak of how Kurtulmak served as Tiamat's vassal in the Nine Hells until Garl Glittergold, the god of gnomes, stole a trinket from the Dragon Queen's hoard. Tiamat sent Kurtulmak to retrieve the trinket, but Garl Glittergold played a trick on him, collapsing the earth and trapping the kobold god in an underground maze for eternity. For this reason, kobolds hate gnomes and pranks of any kind. Kurtulmak's most devoted worshipers dedicate themselves to finding and releasing their lost god from his prison-maze.

```statblock
"name": "Yusdrayl (TftYP)"
"size": "Small"
"type": "humanoid"
"subtype": "kobold"
"alignment": "Lawful Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "16"
"hit_dice": "3d6 + 6"
"stats":
- !!int "8"
- !!int "15"
- !!int "14"
- !!int "10"
- !!int "10"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Insight": !!int "2"
  "Arcana": !!int "2"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Draconic"
"cr": "1"
"traits":
- "desc": "Yusdrayl is a 2nd-level spellcaster. Her spellcasting ability is Charisma\
    \ (spell save DC 13, +5 to hit with spell attacks). She knows the following\
    \ sorcerer spells:\n\nCantrips (at will): [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md), [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md),\
    \ [shocking grasp](/2-Mechanics/CLI/spells/shocking-grasp.md)\n\n1st level (4\
    \ slots): [burning hands](/2-Mechanics/CLI/spells/burning-hands.md), [chromatic\
    \ orb](/2-Mechanics/CLI/spells/chromatic-orb.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
  "name": "Spellcasting"
- "desc": "While in sunlight, Yusdrayl has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
- "desc": "Yusdrayl has advantage on an attack roll against a creature if at least\
    \ one of her allies is within 5 feet of the creature and the ally isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage."
  "name": "Dagger"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Yusdrayl.webp"
```
^statblock

```encounter-table
name: Yusdrayl
creatures:
 - 1: Yusdrayl
```