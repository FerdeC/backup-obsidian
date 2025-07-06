---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cos
- monster/cr/6
- monster/size/medium
- monster/type/undead
aliases: ["Sir Godfrey Gwilym"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Curse of Strahd p. 139
---
# [Sir Godfrey Gwilym](2-Mechanics\CLI\bestiary\npc/sir-godfrey-gwilym-cos.md)
*Source: Curse of Strahd p. 139*  

```statblock
"name": "Sir Godfrey Gwilym (CoS)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "13"
"ac_class": "broken chainmail"
"hp": !!int "136"
"hit_dice": "16d8 + 64"
"stats":
- !!int "18"
- !!int "14"
- !!int "18"
- !!int "13"
- !!int "16"
- !!int "18"
"speed": "30 ft."
"saves":
  "Charisma": !!int "7"
  "Wisdom": !!int "6"
  "Strength": !!int "7"
  "Constitution": !!int "7"
"damage_resistances": "necrotic, psychic"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned),\
  \ [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "the languages it knew in life"
"cr": "6"
"traits":
- "desc": "Sir Godfrey is a 16th-level spellcaster. His spellcasting ability is Wisdom\
    \ (spell save DC 14, +6 to hit with spell attacks). He has the following paladin\
    \ spells prepared:\n\n1st level (4 slots): [command](/2-Mechanics/CLI/spells/command.md),\
    \ [divine favor](/2-Mechanics/CLI/spells/divine-favor.md), [thunderous smite](/2-Mechanics/CLI/spells/thunderous-smite.md)\n\
    \n2nd level (3 slots): [branding smite](/2-Mechanics/CLI/spells/branding-smite.md),\
    \ [magic weapon](/2-Mechanics/CLI/spells/magic-weapon.md)\n\n3rd level (3 slots):\
    \ [blinding smite](/2-Mechanics/CLI/spells/blinding-smite.md), [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md)\n\
    \n4th level (2 slots): [staggering smite](/2-Mechanics/CLI/spells/staggering-smite.md)"
  "name": "Spellcasting"
- "desc": "The knight regains 10 hit points at the start of its turn. If the knight\
    \ takes fire or radiant damage, this trait doesn't function at the start of the\
    \ knight's next turn. The knight's body is destroyed only if it starts its turn\
    \ with 0 hit points and doesn't regenerate."
  "name": "Regeneration"
- "desc": "When the knight's body is destroyed, its soul lingers. After 24 hours,\
    \ the soul inhabits and animates another humanoid corpse on the same plane of\
    \ existence and regains all its hit points. While the soul is bodiless, a [wish](/2-Mechanics/CLI/spells/wish.md)\
    \ spell can be used to force the soul to go to the afterlife and not return."
  "name": "Rejuvenation"
- "desc": "The knight is immune to effects that turn undead."
  "name": "Turn Immunity"
- "desc": "The knight knows the distance to and direction of any creature against\
    \ which it seeks revenge, even if the creature and the knight are on different\
    \ planes of existence. If the creature being tracked by the knight dies, the knight\
    \ knows."
  "name": "Vengeful Tracker"
"actions":
- "desc": "The knight makes two longsword attacks or two fist attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 15\
    \ (2d10 + 4) slashing damage. If the target is a creature against which the\
    \ knight has sworn vengeance, the target takes an extra 14 (4d6) slashing damage."
  "name": "Longsword"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) bludgeoning damage. If the target is a creature against which the\
    \ knight has sworn vengeance, the target takes an extra 14 (4d6) bludgeoning\
    \ damage. Instead of dealing damage, the knight can grapple the target (escape\
    \ DC 14) provided the target is Large or smaller."
  "name": "Fist"
- "desc": "The knight targets one creature it can see within 30 feet of it and against\
    \ which it has sworn vengeance. The target must make a DC 15 Wisdom saving throw.\
    \ On a failure, the target is [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed)\
    \ until the knight deals damage to it, or until the end of the knight's next turn.\
    \ When the paralysis ends, the target is [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ of the knight for 1 minute. The [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ target can repeat the saving throw at the end of each of its turns, with disadvantage\
    \ if it can see the knight, ending the [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ condition on itself on a success."
  "name": "Vengeful Glare"
"source":
- "CoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CoS/Sir%20Godfrey%20Gwilym.webp"
```
^statblock

```encounter-table
name: Sir Godfrey Gwilym
creatures:
 - 1: Sir Godfrey Gwilym
```