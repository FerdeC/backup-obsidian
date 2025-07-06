---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/10
- monster/size/medium
- monster/type/celestial
aliases: ["Lumalia"]
NoteIcon: monster
BestiaryType: celestial
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 153
---
# [Lumalia](2-Mechanics\CLI\bestiary\npc/lumalia-tftyp.md)
*Source: Tales from the Yawning Portal p. 153*  

```statblock
"name": "Lumalia (TftYP)"
"size": "Medium"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d8 + 64"
"stats":
- !!int "18"
- !!int "18"
- !!int "18"
- !!int "17"
- !!int "20"
- !!int "20"
"speed": "30 ft., fly 90 ft."
"saves":
  "Charisma": !!int "9"
  "Wisdom": !!int "9"
"skillsaves":
  "Insight": !!int "9"
  "Perception": !!int "9"
"damage_resistances": "radiant; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "darkvision 120 ft., passive Perception 19"
"languages": "all, telepathy 120 ft."
"cr": "10"
"traits":
- "desc": "Lumalia's spellcasting ability is Charisma (spell save DC 17). Lumalia\
    \ can innately cast the following spells, requiring only verbal components:\n\n\
    At will: [detect evil and good](/2-Mechanics/CLI/spells/detect-evil-and-good.md)\n\
    \n1/day each: [commune](/2-Mechanics/CLI/spells/commune.md), [raise dead](/2-Mechanics/CLI/spells/raise-dead.md)"
  "name": "Innate Spellcasting"
- "desc": "Lumalia's weapon attacks are magical. When Lumalia hits with any weapon,\
    \ the weapon deals an extra 4d8 radiant damage (included in the attack)."
  "name": "Angelic Weapons"
- "desc": "Lumalia has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Lumalia makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) bludgeoning damage plus 18 (4d8) radiant damage."
  "name": "Mace"
- "desc": "Lumalia touches another creature. The target magically regains 20 (4d8\
    \ + 2) hit points and is freed from any curse, disease, poison, blindness, or\
    \ deafness."
  "name": "Healing Touch (3/Day)"
- "desc": "Lumalia magically polymorphs into a humanoid or beast that has a challenge\
    \ rating equal to or less than its own, or back into its true form. It reverts\
    \ to its true form if it dies. Any equipment it is wearing or carrying is absorbed\
    \ or borne by the new form (Lumalia's choice).\n\nIn a new form, Lumalia retains\
    \ its game statistics and ability to speak, but its AC, movement modes, Strength,\
    \ Dexterity, and special senses are replaced by those of the new form, and it\
    \ gains any statistics and capabilities (except class features, legendary actions,\
    \ and lair actions) that the new form has but that it lacks."
  "name": "Change Shape"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Lumalia.webp"
```
^statblock

```encounter-table
name: Lumalia
creatures:
 - 1: Lumalia
```