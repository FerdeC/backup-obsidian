---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/10
- monster/size/large
- monster/type/undead
aliases: ["Lesser Death Dragon"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 195
---
# [Lesser Death Dragon](2-Mechanics\CLI\bestiary\undead/lesser-death-dragon-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 195*  

Most death dragons are pale imitations of their former selves. They remember flashes and echoes, and sometimes things or creatures they encounter painfully remind them of what they once had. These fleeting moments of lucidity quickly burn away in rage and anguish, driving the dragons to destroy the would-be memento.

## Death Dragons

Death dragons are the Undead skeletal remains of metallic or chromatic dragons, infused with the lingering fires of the Cataclysm by foul magic. Rarely, death dragons arise when a dragon meets its end in a way that torments its soul and consumes it with a need for vengeance. Regardless of how it arose, a death dragon retains a shadow of its former personality. The stronger the death dragon, the more it fights the hate consuming it, holding on to some vestige of its memories.

A death dragon's bones burn with violet Cataclysmic fire, which it can unleash in a horrific mockery of the breath weapon it possessed in life. The breath snuffs out life force and infuses undeath into corpses it touches. These zombies burn with Cataclysmic fire and serve the death dragon's will, typically going on rampages to destroy all living creatures in sight.

```statblock
"name": "Lesser Death Dragon (DSotDQ)"
"size": "Large"
"type": "undead"
"alignment": "typically  Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "199"
"hit_dice": "21d10 + 84"
"stats":
- !!int "20"
- !!int "10"
- !!int "18"
- !!int "5"
- !!int "10"
- !!int "5"
"speed": "40 ft., fly 80 ft."
"saves":
  "Dexterity": !!int "4"
  "Wisdom": !!int "4"
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "4"
"damage_resistances": "piercing"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 30 ft., darkvision 60 ft., passive Perception 14"
"languages": "understands Common and Draconic but can't speak"
"cr": "10"
"traits":
- "desc": "The dragon doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The dragon makes one Bite attack and two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 14\
    \ (2d8 + 5) piercing damage plus 4 (1d8) necrotic damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft. one target. Hit: 8 (1d6\
    \ + 5) slashing damage. If the target is a Medium or smaller creature, it is\
    \ [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled) (escape DC 15). Until\
    \ this grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained).\
    \ The dragon has two claws, each of which can grapple one target."
  "name": "Claw"
- "desc": "The dragon exhales a wave of ghostly purple flames in a 30-foot cone. Each\
    \ creature in that area must make a DC 16 Dexterity saving throw, taking 36 (8d8)\
    \ necrotic damage on a failed save, or half as much damage on a successful one.\
    \ A creature dies if the breath reduces it to 0 hit points. Additionally, any\
    \ Medium or smaller Humanoid killed by the breath's damage, as well as every corpse\
    \ of such a creatures within the cone, becomes a zombie (see the Monster Manual)\
    \ under the dragon's control. The zombie acts on the dragon's initiative but immediately\
    \ after the dragon's turn. Absent any other command, the zombie tries to kill\
    \ any non-Undead creature it encounters."
  "name": "Cataclysmic Breath (Recharge 5-6)"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Lesser%20Death%20Dragon.webp"
```
^statblock

```encounter-table
name: Lesser Death Dragon
creatures:
 - 1: Lesser Death Dragon
```