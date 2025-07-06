---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/14
- monster/size/huge
- monster/type/undead
aliases: ["Greater Death Dragon"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 195
---
# [Greater Death Dragon](2-Mechanics\CLI\bestiary\undead/greater-death-dragon-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 195*  

Some death dragons manage to retain almost all of their former selves, albeit twisted by their state of being. These greater death dragons scheme to achieve their ends, all the while amassing and jealously guarding treasure hoards as they did in life. In battle, they are deadly foes, channeling the Cataclysmic fire that limns their bones and fuels their breath. They take cruel delight in snatching foes in their jaws, rushing into the air, then dropping the snared creatures to their doom.

## Death Dragons

Death dragons are the Undead skeletal remains of metallic or chromatic dragons, infused with the lingering fires of the Cataclysm by foul magic. Rarely, death dragons arise when a dragon meets its end in a way that torments its soul and consumes it with a need for vengeance. Regardless of how it arose, a death dragon retains a shadow of its former personality. The stronger the death dragon, the more it fights the hate consuming it, holding on to some vestige of its memories.

A death dragon's bones burn with violet Cataclysmic fire, which it can unleash in a horrific mockery of the breath weapon it possessed in life. The breath snuffs out life force and infuses undeath into corpses it touches. These zombies burn with Cataclysmic fire and serve the death dragon's will, typically going on rampages to destroy all living creatures in sight.

```statblock
"name": "Greater Death Dragon (DSotDQ)"
"size": "Huge"
"type": "undead"
"alignment": "typically  Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "230"
"hit_dice": "20d12 + 100"
"stats":
- !!int "23"
- !!int "10"
- !!int "20"
- !!int "11"
- !!int "14"
- !!int "10"
"speed": "40 ft., fly 80 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "7"
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "7"
"damage_resistances": "piercing"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 17"
"languages": "Common, Draconic"
"cr": "14"
"traits":
- "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The dragon doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The dragon makes one Bite attack and two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 17\
    \ (2d10 + 6) piercing damage plus 4 (1d8) necrotic damage. If the target is\
    \ a Large or smaller creature, it is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 19). Until this grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and the dragon can't bite a different target."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +11 to hit, reach 5 ft. one target. Hit: 10\
    \ (1d8 + 6) slashing damage."
  "name": "Claw"
- "desc": "The dragon exhales a wave of ghostly purple flames in a 60-foot cone. Each\
    \ creature in that area must make a DC 18 Dexterity saving throw, taking 45 (10d8)\
    \ necrotic damage on a failed save, or half as much damage on a successful one.\
    \ A creature dies if the breath reduces it to 0 hit points. Additionally, any\
    \ Medium or smaller Humanoid killed by the breath's damage, as well as every corpse\
    \ of such a creature within the cone, becomes a zombie (see the Monster Manual)\
    \ under the dragon's control. The zombie acts on the dragon's initiative but immediately\
    \ after the dragon's turn. Absent any other command, the zombie tries to kill\
    \ any non-Undead creature it encounters."
  "name": "Cataclysmic Breath (Recharge 5-6)"
"legendary_actions":
- "desc": "The dragon makes one Claw attack."
  "name": "Claw"
- "desc": "The dragon moves up to half its flying speed without provoking opportunity\
    \ attacks, carrying with it any creatures it is grappling. During this move, if\
    \ it enters the space of a Medium or smaller creature, that creature takes 4 (1d8)\
    \ necrotic damage. A creature can take this damage only once per turn."
  "name": "Cataclysmic Rush (Costs 2 Actions)"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Greater%20Death%20Dragon.webp"
```
^statblock

```encounter-table
name: Greater Death Dragon
creatures:
 - 1: Greater Death Dragon
```