---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/ftd
- monster/cr/11
- monster/size/large
- monster/type/construct
aliases: ["Dragonbone Golem"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Fizban's Treasury of Dragons p. 183
---
# [Dragonbone Golem](2-Mechanics\CLI\bestiary\construct/dragonbone-golem-ftd.md)
*Source: Fizban's Treasury of Dragons p. 183*  

A dragonbone golem is composed of dragon bones linked together with adamantine wire into the form of a dragon, animated by drawing on the bones' inherent magic. Most dragon bone golems are created by powerful dragons from the bones of vanquished rivals. Each bone is etched with intricate glyphs that allow animating power to flow through the golem's form.

Dragonbone golems' resilience and obedience make them excellent lair guardians for their dragon creators, and their supernaturally fearsome presence is a strong deterrent against intrusion.

```statblock
"name": "Dragonbone Golem (FTD)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "161"
"hit_dice": "19d10 + 57"
"stats":
- !!int "20"
- !!int "10"
- !!int "17"
- !!int "3"
- !!int "11"
- !!int "10"
"speed": "40 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands Draconic and the languages of its creator but can't speak"
"cr": "11"
"traits":
- "desc": "Each creature of the golem's choice that starts its turn within 20 feet\
    \ of the golem must make a DC 15 Wisdom saving throw unless the golem is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated).\
    \ On a failed save, the creature is [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ until the start of its next turn. On a successful save, the creature is immune\
    \ to this golem's Fear Aura for the next 24 hours."
  "name": "Fear Aura"
- "desc": "The golem has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The golem doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The golem makes one Pinion attack and two Rend attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) piercing damage. If the target is a Medium or smaller creature,\
    \ it is pinned beneath the bony pinion and [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained).\
    \ The golem has two pinions, each of which can restrain one target. If a creature\
    \ is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained) by one of the\
    \ pinions, the golem can't attack with it. Any creature [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ by a pinion can free itself at the start of its turn with a successful DC 17\
    \ Strength ([Athletics](/2-Mechanics/CLI/rules/skills.md#Athletics)) check."
  "name": "Pinion"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) piercing damage plus 5 (1d10) necrotic damage."
  "name": "Rend"
- "desc": "The golem emits a 60-foot cone of petrifying gas from its mouth. Each creature\
    \ in that area must succeed on a DC 15 Constitution saving throw or take 35 (10d6)\
    \ poison damage and be [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ as it begins to turn to stone. The [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ target must repeat the saving throw at the end of its next turn. On a successful\
    \ save, the effect ends on the target. On a failed save, the target is [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified)."
  "name": "Petrifying Breath (Recharge 5-6)"
"source":
- "FTD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/FTD/Dragonbone%20Golem.webp"
```
^statblock

```encounter-table
name: Dragonbone Golem
creatures:
 - 1: Dragonbone Golem
```