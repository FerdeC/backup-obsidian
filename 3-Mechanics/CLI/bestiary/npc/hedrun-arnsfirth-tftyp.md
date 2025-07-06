---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/3
- monster/size/medium
- monster/type/undead
aliases: ["Hedrun Arnsfirth"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 160
---
# [Hedrun Arnsfirth](2-Mechanics\CLI\bestiary\npc/hedrun-arnsfirth-tftyp.md)
*Source: Tales from the Yawning Portal p. 160*  

```statblock
"name": "Hedrun Arnsfirth (TftYP)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "37"
"hit_dice": "5d8 + 15"
"stats":
- !!int "11"
- !!int "14"
- !!int "16"
- !!int "12"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
"skillsaves":
  "Perception": !!int "4"
  "Arcana": !!int "3"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "the languages it knew in life"
"cr": "3"
"traits":
- "desc": "Hedrun's innate spellcasting ability is Charisma (spell save DC 13). It\
    \ can innately cast the following spells, requiring no verbal or material components:\n\
    \nAt will: [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [disguise\
    \ self](/2-Mechanics/CLI/spells/disguise-self.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)\n\
    \n1/day each: [fear](/2-Mechanics/CLI/spells/fear.md), [hold person](/2-Mechanics/CLI/spells/hold-person.md),\
    \ [misty step](/2-Mechanics/CLI/spells/misty-step.md)"
  "name": "Innate Spellcasting"
- "desc": "While in sunlight, Hedrun has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Hedrun attacks twice with Grave Bolt."
  "name": "Multiattack"
- "desc": "Ranged Spell Attack: +5 to hit, range 120 ft., one target. Hit: 7\
    \ (1d8 + 3) necrotic damage."
  "name": "Grave Bolt"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 9\
    \ (2d6 + 2) necrotic damage. The target must succeed on a DC 13 Constitution\
    \ saving throw or its hit point maximum is reduced by an amount equal to the damage\
    \ taken. This reduction lasts until the target finishes a long rest. The target\
    \ dies if this effect reduces its hit point maximum to 0.\n\nA humanoid slain\
    \ by this attack rises 24 hours later as a [zombie](/2-Mechanics/CLI/bestiary/undead/zombie.md)\
    \ under Hedrun's control, unless the humanoid is restored to life or its body\
    \ is destroyed. Hedrun can have no more than twelve [zombies](/2-Mechanics/CLI/bestiary/undead/zombie.md)\
    \ under its control at one time."
  "name": "Life Drain"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Hedrun%20Arnsfirth.webp"
```
^statblock

```encounter-table
name: Hedrun Arnsfirth
creatures:
 - 1: Hedrun Arnsfirth
```