---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/13
- monster/size/medium
- monster/type/undead/kender
- monster/type/undead/shapechanger
aliases: ["Lorry Wanwillow"]
NoteIcon: monster
BestiaryType: undead (shapechanger, kender)
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 177
---
# [Lorry Wanwillow](2-Mechanics\CLI\bestiary\npc/lorry-wanwillow-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 177*  

```statblock
"name": "Lorry Wanwillow (DSotDQ)"
"size": "Medium"
"type": "undead"
"subtype": "shapechanger, kender"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "144"
"hit_dice": "17d8 + 68"
"stats":
- !!int "18"
- !!int "18"
- !!int "18"
- !!int "17"
- !!int "15"
- !!int "18"
"speed": "30 ft."
"saves":
  "Charisma": !!int "9"
  "Dexterity": !!int "9"
  "Wisdom": !!int "7"
"skillsaves":
  "Stealth": !!int "9"
  "Perception": !!int "7"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "the languages it knew in life"
"cr": "13"
"traits":
- "desc": "If Lorry isn't in sunlight or running water, it can use its action to polymorph\
    \ into a Tiny rat or a Medium cloud of mist, or back into its true form.\n\nWhile\
    \ in bat form, Lorry can't speak, its walking speed is 5 feet, and it has a flying\
    \ speed of 30 feet. Its statistics, other than its size and speed, are unchanged.\
    \ Anything it is wearing transforms with it, but nothing it is carrying does.\
    \ It reverts to its true form if it dies.\n\nWhile in mist form, Lorry can't take\
    \ any actions, speak, or manipulate objects. It is weightless, has a flying speed\
    \ of 20 feet, can hover, and can enter a hostile creature's space and stop there.\
    \ In addition, if air can pass through a space, the mist can do so without squeezing,\
    \ and it can't pass through water. It has advantage on Strength, Dexterity, and\
    \ Constitution saving throws, and it is immune to all nonmagical damage, except\
    \ the damage it takes from sunlight."
  "name": "Shapechanger"
- "desc": "If Lorry fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "When it drops to 0 hit points outside its resting place, Lorry transforms\
    \ into a cloud of mist (as in the Shapechanger trait) instead of falling [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious),\
    \ provided that it isn't in sunlight or running water. If it can't transform,\
    \ it is destroyed.\n\nWhile it has 0 hit points in mist form, it can't revert\
    \ to its vampire form, and it must reach its resting place within 2 hours or be\
    \ destroyed. Once in its resting place, it reverts to its vampire form. It is\
    \ then [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed) until it regains\
    \ at least 1 hit point. After spending 1 hour in its resting place with 0 hit\
    \ points, it regains 1 hit point."
  "name": "Misty Escape"
- "desc": "Lorry regains 20 hit points at the start of its turn if it has at least\
    \ 1 hit point and isn't in sunlight or running water. If Lorry takes radiant damage\
    \ or damage from holy water, this trait doesn't function at the start of Lorry's\
    \ next turn."
  "name": "Regeneration"
- "desc": "Lorry can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
- "desc": "Lorry has the following flaws:\n\nForbiddance. Lorry can't enter a residence\
    \ without an invitation from one of the occupants.\n\nHarmed by Running Water.\
    \ Lorry takes 20 acid damage if it ends its turn in running water.\n\nStake to\
    \ the Heart. If a piercing weapon made of wood is driven into Lorry's heart while\
    \ Lorry is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ in its resting place, Lorry is [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed)\
    \ until the stake is removed.\n\nSunlight Hypersensitivity. Lorry takes 20 radiant\
    \ damage when it starts its turn in sunlight. While in sunlight, it has disadvantage\
    \ on attack rolls and ability checks."
  "name": "Vampire Weaknesses"
"actions":
- "desc": "Lorry makes two attacks, only one of which can be a bite attack."
  "name": "Multiattack (Vampire Form Only)"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one creature. Hit: 8\
    \ (1d8 + 4) bludgeoning damage. Instead of dealing damage, Lorry can grapple\
    \ the target (escape DC 18)."
  "name": "Unarmed Strike (Vampire Form Only)"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one willing creature,\
    \ or a creature that is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ by Lorry, [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated),\
    \ or [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained). Hit: 7 (1d6\
    \ + 4) piercing damage plus 10 (3d6) necrotic damage. The target's hit point\
    \ maximum is reduced by an amount equal to the necrotic damage taken, and Lorry\
    \ regains hit points equal to that amount. The reduction lasts until the target\
    \ finishes a long rest. The target dies if this effect reduces its hit point maximum\
    \ to 0. A humanoid slain in this way and then buried in the ground rises the following\
    \ night as a [vampire spawn](/2-Mechanics/CLI/bestiary/undead/vampire-spawn.md)\
    \ under Lorry's control."
  "name": "Bite (Bat or Vampire Form Only)"
- "desc": "Lorry targets one humanoid it can see within 30 feet of it. If the target\
    \ can see Lorry, the target must succeed on a DC 17 Wisdom saving throw against\
    \ this magic or be [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed) by\
    \ Lorry. The [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed) target regards\
    \ Lorry as a trusted friend to be heeded and protected. Although the target isn't\
    \ under Lorry's control, it takes Lorry's requests or actions in the most favorable\
    \ way it can, and it is a willing target for Lorry's bite attack.\n\nEach time\
    \ Lorry or Lorry's companions do anything harmful to the target, it can repeat\
    \ the saving throw, ending the effect on itself on a success. Otherwise, the effect\
    \ lasts 24 hours or until Lorry is destroyed, is on a different plane of existence\
    \ than the target, or takes a bonus action to end the effect."
  "name": "Charm"
- "desc": "Lorry magically calls 2d4 swarms of [bats](/2-Mechanics/CLI/bestiary/beast/swarm-of-bats.md)\
    \ or [rats](/2-Mechanics/CLI/bestiary/beast/swarm-of-rats.md), provided that the\
    \ sun isn't up. While outdoors, Lorry can call 3d6 [wolves](/2-Mechanics/CLI/bestiary/beast/wolf.md)\
    \ instead. The called creatures arrive in 1d4 rounds, acting as allies of Lorry\
    \ and obeying its spoken commands. The beasts remain for 1 hour, until Lorry dies,\
    \ or until Lorry dismisses them as a bonus action."
  "name": "Children of the Night (1/Day)"
"legendary_actions":
- "desc": "Lorry moves up to its speed without provoking opportunity attacks."
  "name": "Move"
- "desc": "Lorry makes one unarmed strike."
  "name": "Unarmed Strike"
- "desc": "Lorry makes one bite attack."
  "name": "Bite (Costs 2 Actions)"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Lorry%20Wanwillow.webp"
```
^statblock

```encounter-table
name: Lorry Wanwillow
creatures:
 - 1: Lorry Wanwillow
```