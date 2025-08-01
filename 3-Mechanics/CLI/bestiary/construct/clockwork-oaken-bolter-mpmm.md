---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/5
- monster/environment/forest
- monster/environment/grassland
- monster/environment/hill
- monster/environment/mountain
- monster/size/medium
- monster/type/construct
aliases: ["Clockwork Oaken Bolter"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 80, Mordenkainen's Tome of Foes p. 126
---
# [Clockwork Oaken Bolter](2-Mechanics\CLI\bestiary\construct/clockwork-oaken-bolter-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 80, Mordenkainen's Tome of Foes p. 126*  

No ordinary ballista, an oaken bolter is a Construct capable of striking at long distances. The bolts it launches can rend flesh, destroy armor, or drag enemies toward traps or melee-oriented clockworks—and at shorter ranges, burst with explosive force.

## Clockworks

Gnomes' tinkering with magic and mechanical devices has produced many failed Constructs but also has resulted in genuine advances, such as clockworks. The methods used to craft clockworks have been shared between gnome communities over many generations.

### Individual Designs

Gnome artisans prefer unique clockworks over perfectly functioning ones that copy too much from other creations. A clockwork can be customized by adding one of the following enhancements and one potential malfunction to its stat block. You can select randomly or choose a pair of modifications that fit the temperament of the clockwork's builder.

**Clockwork Enhancements**

`dice: [](clockwork-oaken-bolter-mpmm.md#^clockwork-enhancements)`

| dice: d10 | Enhancement |
|-----------|-------------|
| 1 | **Camouflaged.** The clockwork gains proficiency in [Stealth](/2-Mechanics/CLI/rules/skills.md#Stealth) if it lacks that proficiency. While motionless, it is indistinguishable from a stopped machine. |
| 2 | **Sensors.** The range of the clockwork's [darkvision](/2-Mechanics/CLI/rules/senses.md#darkvision) increases by 60 feet, and it gains proficiency in [Perception](/2-Mechanics/CLI/rules/skills.md#Perception) if it lacks that proficiency. |
| 3 | **Fortified.** The clockwork's AC increases by 2. |
| 4 | **Increased Speed.** The clockwork's speed increases by 10 feet. |
| 5 | **Reinforced Construction.** The clockwork has resistance to force, lightning, and thunder damage. |
| 6 | **Self-Repairing.** If the clockwork starts its turn with fewer than half its hit points but at least 1 hit point, it regains 5 hit points. If it takes lightning damage, this ability doesn't function at the start of its next turn. |
| 7 | **Sturdy Frame.** The clockwork's hit point maximum increases by an amount equal to its number of Hit Dice. |
| 8 | **Suction.** The clockwork gains a climbing speed of 30 feet. |
| 9 | **Vocal Resonator.** The clockwork gains the ability to speak rudimentary Common or Gnomish. |
| 10 | **Water Propulsion.** The clockwork gains a swimming speed of 30 feet. |
^clockwork-enhancements

**Clockwork Malfunctions**

`dice: [](clockwork-oaken-bolter-mpmm.md#^clockwork-malfunctions)`

| dice: d8 | Malfunction |
|----------|-------------|
| 1 | **Faulty Sensors.** Roll a `d6` at the start of the clock work's turn. If you roll a 1, the clockwork is [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded) until the end of its turn. |
| 2 | **Flawed Targeting.** Roll a `d6` at the start of the clock work's turn. If you roll a 1, the clockwork makes attack rolls with disadvantage until the end of its turn. |
| 3 | **Ground Fault.** The clockwork has vulnerability to lightning damage. |
| 4 | **Imprinting Loop.** Roll a `d6` at the start of the clock work's turn. If you roll a 1, the clockwork mistakes one creature it can see within 30 feet for its creator. The clockwork won't willingly harm that creature for 1 minute or until that creature attacks or dam ages it. |
| 5 | **Limited Steering.** The clockwork must move in a straight line. It can turn up to 90 degrees before moving and again at the midpoint of its movement. It can rotate freely if it doesn't use any of its speeds on its turn. |
| 6 | **Overactive Sense of Self-Preservation.** If the clock work has half its hit points or fewer at the start of its turn in combat, roll a `d6`. If you roll a 1, it retreats from combat if possible. It otherwise keeps fighting. |
| 7 | **Overheats.** Roll a `d6` at the start of the clockwork's turn. If you roll a 1, the clockwork is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated) until the end of its turn. |
| 8 | **Rusty Gears.** The clockwork has disadvantage on initiative rolls, and its speed decreases by 10 feet. |
^clockwork-malfunctions

```statblock
"name": "Clockwork Oaken Bolter (MPMM)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"stats":
- !!int "12"
- !!int "18"
- !!int "15"
- !!int "3"
- !!int "10"
- !!int "1"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands one language of its creator but can't speak"
"cr": "5"
"traits":
- "desc": "The clockwork has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The clockwork doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The clockwork makes two Lancing Bolt attacks or one Lancing Bolt attack\
    \ and one Harpoon attack."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 100/400\
    \ ft., one target. Hit: 15 (2d10 + 4) piercing damage."
  "name": "Lancing Bolt"
- "desc": "Ranged Weapon Attack: +7 to hit, range 50/200 ft., one target. Hit:\
    \ 9 (1d10 + 4) piercing damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 12). While [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ in this way, a creature's speed isn't reduced, but it can move only in directions\
    \ that bring it closer to the clockwork. A creature takes 5 (1d10) slashing\
    \ damage if it escapes from the grapple or if it tries and fails. The clockwork\
    \ can grapple only one creature at a time with its harpoon."
  "name": "Harpoon"
- "desc": "The clockwork launches an explosive charge at a point within 120 feet.\
    \ Each creature in a 20-foot-radius sphere centered on that point must make a\
    \ DC 15 Dexterity saving throw, taking 17 (5d6) fire damage on a failed save,\
    \ or half as much damage on a successful one."
  "name": "Explosive Bolt (Recharge 5-6)"
"bonus_actions":
- "desc": "The clockwork pulls the creature [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ by its Harpoon up to 20 feet closer."
  "name": "Reel In"
"source":
- "MPMM"
- "MTF"
- "RtG"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPMM/Clockwork%20Oaken%20Bolter.webp"
```
^statblock

```encounter-table
name: Clockwork Oaken Bolter
creatures:
 - 1: Clockwork Oaken Bolter
```

## Environment

forest, grassland, hill, mountain