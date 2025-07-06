---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/10
- monster/size/huge
- monster/type/undead
aliases: ["Ooze Master"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 241
---
# [Ooze Master](2-Mechanics\CLI\bestiary\undead/ooze-master-tftyp.md)
*Source: Tales from the Yawning Portal p. 241*  

```statblock
"name": "Ooze Master (TftYP)"
"size": "Huge"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "9"
"ac_class": "natural armor"
"hp": !!int "138"
"hit_dice": "12d12 + 60"
"stats":
- !!int "16"
- !!int "1"
- !!int "20"
- !!int "17"
- !!int "10"
- !!int "16"
"speed": "30 ft., climb 30 ft."
"saves":
  "Wisdom": !!int "4"
  "Intelligence": !!int "7"
"skillsaves":
  "Insight": !!int "4"
  "Arcana": !!int "7"
"damage_resistances": "lightning; necrotic; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "acid, cold, poison"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone)"
"senses": "blindsight 120 ft., passive Perception 10"
"languages": "Common, Primordial, Thayan"
"cr": "10"
"traits":
- "desc": "The Ooze Master is a 9th-level spellcaster. Its spellcasting ability is\
    \ Intelligence (spell save DC 15, +7 to hit with spell attacks). It has the\
    \ following wizard spells prepared:\n\nCantrips (at will): [acid splash](/2-Mechanics/CLI/spells/acid-splash.md),\
    \ [friends](/2-Mechanics/CLI/spells/friends.md), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [poison spray](/2-Mechanics/CLI/spells/poison-spray.md)\n\n1st level (4 slots):\
    \ [charm person](/2-Mechanics/CLI/spells/charm-person.md), [detect magic](/2-Mechanics/CLI/spells/detect-magic.md),\
    \ [magic missile](/2-Mechanics/CLI/spells/magic-missile.md), [ray of sickness](/2-Mechanics/CLI/spells/ray-of-sickness.md)\n\
    \n2nd level (3 slots): [detect thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md),\
    \ [Melf's acid arrow](/2-Mechanics/CLI/spells/melfs-acid-arrow.md), [suggestion](/2-Mechanics/CLI/spells/suggestion.md)\n\
    \n3rd level (3 slots): [fear](/2-Mechanics/CLI/spells/fear.md), [slow](/2-Mechanics/CLI/spells/slow.md),\
    \ [stinking cloud](/2-Mechanics/CLI/spells/stinking-cloud.md)\n\n4th level (3\
    \ slots): [confusion](/2-Mechanics/CLI/spells/confusion.md), [Evard's black\
    \ tentacles](/2-Mechanics/CLI/spells/evards-black-tentacles.md)\n\n5th level\
    \ (1 slots): [cloudkill](/2-Mechanics/CLI/spells/cloudkill.md)"
  "name": "Spellcasting"
- "desc": "A creature that touches the Ooze Master or hits it with a melee attack\
    \ while within 5 feet of it takes 9 (2d8) acid damage. Any nonmagical weapon\
    \ that hits the Ooze Master corrodes. After dealing damage, the weapon takes a\
    \ permanent and cumulative −1 penalty to damage rolls. If its penalty drops to\
    \ −5, the weapon is destroyed. Nonmagical ammunition that hits the Ooze Master\
    \ is destroyed after dealing damage.\n\nThe Ooze Master can eat through 2-inch-thick,\
    \ nonmagical wood or metal in 1 round."
  "name": "Corrosive Form"
- "desc": "When the Ooze Master casts a spell with a casting time of 1 action, it\
    \ can make one pseudopod attack as a bonus action."
  "name": "Instinctive Attack"
- "desc": "The Ooze Master can climb difficult surfaces, including upside down on\
    \ ceilings, without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 13\
    \ (3d6 + 3) bludgeoning damage plus 10 (3d6) acid damage."
  "name": "Pseudopod"
"reactions":
- "desc": "If a creature the Ooze Master can see makes an attack roll against it while\
    \ within 30 feet of it, the Ooze Master can use a reaction to divert the attack\
    \ if another creature is within the attack's range. The attacker must make a DC\
    \ 15 Wisdom saving throw. On a failed save, the attacker targets the creature\
    \ that is closest to it, not including itself or the Ooze Master. If multiple\
    \ creatures are closest, the attacker chooses which one to target. On a successful\
    \ save, the attacker is immune to this Instinctive Charm for 24 hours. Creatures\
    \ that can't be [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed) are immune\
    \ to this effect."
  "name": "Instinctive Charm"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Ooze%20Master.webp"
```
^statblock

```encounter-table
name: Ooze Master
creatures:
 - 1: Ooze Master
```