---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/jttrc
- monster/cr/21
- monster/size/large
- monster/type/celestial
aliases: ["Atash"]
NoteIcon: monster
BestiaryType: celestial
SourceType: Bestiary
BookSource: Journeys through the Radiant Citadel p. 166
---
# [Atash](2-Mechanics\CLI\bestiary\npc/atash-jttrc.md)
*Source: Journeys through the Radiant Citadel p. 166*  

```statblock
"name": "Atash (JttRC)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Neutral"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "243"
"hit_dice": "18d10 + 144"
"stats":
- !!int "26"
- !!int "22"
- !!int "26"
- !!int "25"
- !!int "25"
- !!int "30"
"speed": "50 ft., fly 150 ft."
"saves":
  "Charisma": !!int "17"
  "Wisdom": !!int "14"
  "Intelligence": !!int "14"
"skillsaves":
  "Perception": !!int "14"
"damage_resistances": "radiant; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "truesight 120 ft., passive Perception 24"
"languages": "all, telepathy 120 ft."
"cr": "21"
"traits":
- "desc": "Atash's spellcasting ability is Charisma (spell save DC 25). It can innately\
    \ cast the following spells, requiring no material components:\n\nAt will:\
    \ [detect evil and good](/2-Mechanics/CLI/spells/detect-evil-and-good.md), [invisibility](/2-Mechanics/CLI/spells/invisibility.md)\
    \ (self only)\n\n1/day each: [commune](/2-Mechanics/CLI/spells/commune.md),\
    \ [control weather](/2-Mechanics/CLI/spells/control-weather.md)\n\n3/day each:\
    \ [blade barrier](/2-Mechanics/CLI/spells/blade-barrier.md), [dispel evil and\
    \ good](/2-Mechanics/CLI/spells/dispel-evil-and-good.md), [resurrection](/2-Mechanics/CLI/spells/resurrection.md)"
  "name": "Innate Spellcasting"
- "desc": "Atash's weapon attacks are magical. When Atash hits with any weapon, the\
    \ weapon deals an extra 6d8 radiant damage (included in the attack)."
  "name": "Angelic Weapons"
- "desc": "Atash knows if it hears a lie."
  "name": "Divine Awareness"
- "desc": "Atash has advantage on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Atash makes two greatsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +15 to hit, reach 5 ft., one target. Hit: 22\
    \ (4d6 + 8) slashing damage plus 27 (6d8) radiant damage."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +13 to hit, range 150/600 ft., one target. Hit:\
    \ 15 (2d8 + 6) piercing damage plus 27 (6d8) radiant damage. If the target\
    \ is a creature that has 100 hit points or fewer, it must succeed on a DC 15 Constitution\
    \ saving throw or die."
  "name": "Slaying Longbow"
- "desc": "Atash releases its greatsword to hover magically in an unoccupied space\
    \ within 5 feet of it. If Atash can see the sword, Atash can mentally command\
    \ it as a bonus action to fly up to 50 feet and either make one attack against\
    \ a target or return to Atash's hands. If the hovering sword is targeted by any\
    \ effect, Atash is considered to be holding it. The hovering sword falls if Atash\
    \ dies."
  "name": "Flying Sword"
- "desc": "Atash touches another creature. The target magically regains 40 (8d8 +\
    \ 4) hit points and is freed from any curse, disease, poison, blindness, or deafness."
  "name": "Healing Touch (4/Day)"
"legendary_actions":
- "desc": "Atash magically teleports, along with any equipment it is wearing or carrying,\
    \ up to 120 feet to an unoccupied space it can see."
  "name": "Teleport"
- "desc": "Atash emits magical, divine energy. Each creature of its choice in a 10-foot\
    \ radius must make a DC 23 Dexterity saving throw, taking 14 (4d6) fire damage\
    \ plus 14 (4d6) radiant damage on a failed save, or half as much damage on a\
    \ successful one."
  "name": "Searing Burst (Costs 2 Actions)"
- "desc": "Atash targets one creature it can see within 30 feet of it. If the target\
    \ can see it, the target must succeed on a DC 15 Constitution saving throw or\
    \ be [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded) until magic such\
    \ as the [lesser restoration](/2-Mechanics/CLI/spells/lesser-restoration.md) spell\
    \ removes the blindness."
  "name": "Blinding Gaze (Costs 3 Actions)"
"source":
- "JttRC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/JttRC/Atash.webp"
```
^statblock

```encounter-table
name: Atash
creatures:
 - 1: Atash
```