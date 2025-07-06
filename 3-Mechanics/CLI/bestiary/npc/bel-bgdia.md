---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/25
- monster/size/large
- monster/type/fiend/devil
aliases: ["Bel"]
NoteIcon: monster
BestiaryType: fiend (devil)
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 115
---
# [Bel](2-Mechanics\CLI\bestiary\npc/bel-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 115*  

From his bastion, Zariel's second-in-command and the former lord of Avernus oversees the forges that furnish weapons and armor for the Blood War. Though Asmodeus has instructed Zariel to accept Bel as her advisor, Bel and Zariel loathe each other and invent distractions to keep them apart.

Bel outwardly plays the role of Zariel's loyal vassal. However, Bel rankles at Zariel's rulership of the layer of the Nine Hells that was once his, but he won't challenge her directly as long as he thinks Asmodeus supports Zariel.

```statblock
"name": "Bel (BGDIA)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "364"
"hit_dice": "27d10 + 216"
"stats":
- !!int "28"
- !!int "14"
- !!int "26"
- !!int "25"
- !!int "19"
- !!int "26"
"speed": "30 ft., fly 60 ft."
"saves":
  "Dexterity": !!int "10"
  "Wisdom": !!int "12"
  "Constitution": !!int "16"
"skillsaves":
  "Deception": !!int "16"
  "Insight": !!int "12"
  "Arcana": !!int "15"
  "Persuasion": !!int "16"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "truesight 120 ft., passive Perception 14"
"languages": "Common, Infernal, telepathy 120 ft."
"cr": "25"
"traits":
- "desc": "Bel's spellcasting ability is Charisma (spell save DC 23). Bel can innately\
    \ cast the following spells, requiring no material components:\n\nAt will:\
    \ [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [fireball](/2-Mechanics/CLI/spells/fireball.md)\n\
    \n1/day each: [imprisonment](/2-Mechanics/CLI/spells/imprisonment.md), [meteor\
    \ swarm](/2-Mechanics/CLI/spells/meteor-swarm.md)\n\n3/day each: [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md),\
    \ [hold monster](/2-Mechanics/CLI/spells/hold-monster.md), [mirror image](/2-Mechanics/CLI/spells/mirror-image.md),\
    \ [mislead](/2-Mechanics/CLI/spells/mislead.md), [raise dead](/2-Mechanics/CLI/spells/raise-dead.md),\
    \ [teleport](/2-Mechanics/CLI/spells/teleport.md), [wall of fire](/2-Mechanics/CLI/spells/wall-of-fire.md)"
  "name": "Innate Spellcasting"
- "desc": "Any creature hostile to Bel that starts its turn within 20 feet of him\
    \ must make a DC 23 Wisdom saving throw, unless Bel is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated).\
    \ Unless the save succeeds, the creature is [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ until the start of its next turn. If a creature's saving throw is successful,\
    \ the creature is immune to Bel's Fear Aura for the next 24 hours."
  "name": "Fear Aura"
- "desc": "If Bel fails a saving throw, he can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Bel has advantage on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
- "desc": "Bel's weapon attacks are magical."
  "name": "Magic Weapons"
"actions":
- "desc": "Bel makes three attacks: two with his greatsword and one with his tail."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +16 to hit, reach 10 ft., one target. Hit: 23\
    \ (4d6 + 9) slashing damage plus 21 (6d6) fire damage. If the target is a\
    \ flammable object that is not being held or worn, it catches fire."
  "name": "Greatsword"
- "desc": "Melee Weapon Attack: +16 to hit, reach 10 ft., one target. Hit: 25\
    \ (3d10 + 9) bludgeoning damage. If the target is a creature, it must succeed\
    \ on a DC 23 Constitution saving throw or be [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)\
    \ until the end of its next turn."
  "name": "Tail"
"legendary_actions":
- "desc": "Bel casts [fireball](/2-Mechanics/CLI/spells/fireball.md)."
  "name": "Fireball"
- "desc": "Roll a d6 for Bel. The number rolled on the die is subtracted from the\
    \ next attack roll made against Bel or an ally of his choice within the next minute."
  "name": "Tactical Edge (Costs 2 Actions)"
- "desc": "Bel magically summons an ice devil with an ice spear (as described in the\
    \ ice devil's entry in the Monster Manual). The ice devil appears in an unoccupied\
    \ space within 60 feet of Bel, acts as Bel's ally, and can summon other devils\
    \ if it has such power. The ice devil remains until Bel dies or until he dismisses\
    \ it as an action."
  "name": "Summon Ice Devil (Costs 3 Actions)"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Bel.webp"
```
^statblock

```encounter-table
name: Bel
creatures:
 - 1: Bel
```