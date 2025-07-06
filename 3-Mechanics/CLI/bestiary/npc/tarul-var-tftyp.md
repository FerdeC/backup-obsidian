---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/13
- monster/size/medium
- monster/type/undead
aliases: ["Tarul Var"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 244
---
# [Tarul Var](2-Mechanics\CLI\bestiary\npc/tarul-var-tftyp.md)
*Source: Tales from the Yawning Portal p. 244*  

After failing in an earlier task for the Red Wizards, the lich Tarul Var is sequestered within the Doomvault (Dead in Thay), where he tries to avoid the attention of Szass Tam. Interlopers who discover his quarters are set upon by the lich and his dread warrior guards, but if Var is brought to the brink of death, he might bargain for a chance to escape the dungeon.

## Undead Nature

A lich doesn't require air, food, drink, or sleep.

```statblock
"name": "Tarul Var (TftYP)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "105"
"hit_dice": "14d8 + 42"
"stats":
- !!int "11"
- !!int "16"
- !!int "16"
- !!int "19"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "7"
  "Intelligence": !!int "9"
  "Constitution": !!int "8"
"skillsaves":
  "Insight": !!int "7"
  "Perception": !!int "7"
  "History": !!int "9"
  "Arcana": !!int "9"
"damage_resistances": "cold; lightning; necrotic; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 17"
"languages": "Abyssal, Common, Infernal, Primordial, Thayan"
"cr": "13"
"traits":
- "desc": "Var is a 12th-level spellcaster. His spellcasting ability is Intelligence\
    \ (spell save DC 17, +9 to hit with spell attacks). He has the following wizard\
    \ spells prepared:\n\nConjuration spell of 1st level or higher\n\nCantrips\
    \ (at will): [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md),\
    \ [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md)\n\n1st level (4 slots):\
    \ [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [magic missile](/2-Mechanics/CLI/spells/magic-missile.md),\
    \ [shield](/2-Mechanics/CLI/spells/shield.md), [unseen servant](/2-Mechanics/CLI/spells/unseen-servant.md)\n\
    \n2nd level (3 slots): [detect thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md),\
    \ [flaming sphere](/2-Mechanics/CLI/spells/flaming-sphere.md), [mirror image](/2-Mechanics/CLI/spells/mirror-image.md),\
    \ [scorching ray](/2-Mechanics/CLI/spells/scorching-ray.md)\n\n3rd level (3\
    \ slots): [counterspell](/2-Mechanics/CLI/spells/counterspell.md), [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md),\
    \ [fireball](/2-Mechanics/CLI/spells/fireball.md)\n\n4th level (3 slots):\
    \ [dimension door](/2-Mechanics/CLI/spells/dimension-door.md), [Evard's black\
    \ tentacles](/2-Mechanics/CLI/spells/evards-black-tentacles.md)\n\n5th level\
    \ (3 slots): [cloudkill](/2-Mechanics/CLI/spells/cloudkill.md), [scrying](/2-Mechanics/CLI/spells/scrying.md)\n\
    \n6th level (1 slots): [circle of death](/2-Mechanics/CLI/spells/circle-of-death.md)"
  "name": "Spellcasting"
- "desc": "While Var is concentrating on a conjuration spell, his [concentration](/2-Mechanics/CLI/rules/conditions.md#concentration)\
    \ can't be broken as a result of taking damage."
  "name": "Focused Conjuration"
- "desc": "If Var fails a saving throw, he can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "If Var is destroyed but his phylactery remains intact, Var gains a new\
    \ body in 1d10 days, regaining all his hit points and becoming active again.\
    \ The new body appears within 5 feet of the phylactery."
  "name": "Rejuvenation"
- "desc": "Var has advantage on saving throws against any effect that turns undead."
  "name": "Turn Resistance"
"actions":
- "desc": "Melee Spell Attack: +9 to hit, reach 5 ft., one creature. Hit: 10\
    \ (3d6) cold damage. The target must succeed on a DC 17 Constitution saving\
    \ throw or be [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed) for\
    \ 1 minute. The target can repeat the saving throw at the end of each of its turns,\
    \ ending the effect on itself on a success."
  "name": "Paralyzing Touch"
- "desc": "Var teleports up to 30 feet to an unoccupied space he can see. Alternatively,\
    \ he can choose a space within range that is occupied by a Small or Medium creature.\
    \ If that creature is willing, both creatures teleport, swapping places. Var can\
    \ use this feature again only after he finishes a long rest or casts a conjuration\
    \ spell of 1st level or higher."
  "name": "Benign Transposition"
"legendary_actions":
- "desc": "Var casts a cantrip."
  "name": "Cantrip"
- "desc": "Var uses Paralyzing Touch."
  "name": "Paralyzing Touch (Costs 2 Actions)"
- "desc": "Var fixes his gaze on one creature he can see within 10 feet of him. The\
    \ target must succeed on a DC 17 Wisdom saving throw against this magic or become\
    \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened) for 1 minute.\
    \ The [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened) target can\
    \ repeat the saving throw at the end of each of its turns, ending the effect on\
    \ itself on a success. If a target's saving throw is successful or the effect\
    \ ends for it, the target is immune to Var's gaze for the next 24 hours."
  "name": "Frightening Gaze (Costs 2 Actions)"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Tarul%20Var.webp"
```
^statblock

```encounter-table
name: Tarul Var
creatures:
 - 1: Tarul Var
```