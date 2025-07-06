---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/4
- monster/size/medium
- monster/type/celestial
aliases: ["Eku"]
NoteIcon: monster
BestiaryType: celestial
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 34
---
# [Eku](2-Mechanics\CLI\bestiary\npc/eku-toa.md)
*Source: Tomb of Annihilation p. 34*  

```statblock
"name": "Eku (ToA)"
"size": "Medium"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "97"
"hit_dice": "13d8 + 39"
"stats":
- !!int "16"
- !!int "20"
- !!int "17"
- !!int "18"
- !!int "20"
- !!int "18"
"speed": "30 ft., fly 90 ft."
"saves":
  "Charisma": !!int "6"
  "Wisdom": !!int "7"
  "Constitution": !!int "5"
"damage_resistances": "radiant"
"damage_immunities": "psychic; bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "truesight 120 ft., passive Perception 15"
"languages": "all, telepathy 120 ft."
"cr": "4"
"traits":
- "desc": "Eku's spellcasting ability is Charisma (spell save DC 14). It can innately\
    \ cast the following spells, requiring only verbal components:\n\nAt will:\
    \ [detect evil and good](/2-Mechanics/CLI/spells/detect-evil-and-good.md), [detect\
    \ magic](/2-Mechanics/CLI/spells/detect-magic.md), [detect thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md)\n\
    \n1/day each: [dream](/2-Mechanics/CLI/spells/dream.md), [greater restoration](/2-Mechanics/CLI/spells/greater-restoration.md),\
    \ [scrying](/2-Mechanics/CLI/spells/scrying.md)\n\n3/day each: [bless](/2-Mechanics/CLI/spells/bless.md),\
    \ [create food and water](/2-Mechanics/CLI/spells/create-food-and-water.md), [cure\
    \ wounds](/2-Mechanics/CLI/spells/cure-wounds.md), [lesser restoration](/2-Mechanics/CLI/spells/lesser-restoration.md),\
    \ [protection from poison](/2-Mechanics/CLI/spells/protection-from-poison.md),\
    \ [sanctuary](/2-Mechanics/CLI/spells/sanctuary.md), [shield](/2-Mechanics/CLI/spells/shield.md)"
  "name": "Innate Spellcasting"
- "desc": "Eku's weapon attacks are magical."
  "name": "Magic Weapons"
- "desc": "Eku is immune to scrying and to any effect that would sense its emotions,\
    \ read its thoughts, or detect its location."
  "name": "Shielded Mind"
"actions":
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. Hit: 8\
    \ (1d6 + 5) piercing damage, and the target must succeed on a DC 13 Constitution\
    \ saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 24 hours. Until this poison ends, the target is [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious).\
    \ Another creature can use an action to shake the target awake."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one Medium or smaller\
    \ creature. Hit: 10 (2d6 + 3) bludgeoning damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 15). Until this grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and Eku can't constrict another target."
  "name": "Constrict"
- "desc": "Eku magically polymorphs into a humanoid or beast that has a challenge\
    \ rating equal to or less than its own, or back into its true form. It reverts\
    \ to its true form if it dies. Any equipment it is wearing or carrying is absorbed\
    \ or borne by the new form (Eku's choice).\n\nIn a new form, Eku retains its game\
    \ statistics and ability to speak, but its AC, movement modes, Strength, Dexterity,\
    \ and other actions are replaced by those of the new form, and it gains any statistics\
    \ and capabilities (except class features, legendary actions, and lair actions)\
    \ that the new form has but that it lacks. If the new form has a bite attack,\
    \ Eku can use its bite in that form."
  "name": "Change Shape"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Eku.webp"
```
^statblock

```encounter-table
name: Eku
creatures:
 - 1: Eku
```