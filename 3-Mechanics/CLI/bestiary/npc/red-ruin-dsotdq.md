---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/10
- monster/size/medium
- monster/type/humanoid
aliases: ["Red Ruin"]
NoteIcon: monster
BestiaryType: humanoid
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 208
---
# [Red Ruin](2-Mechanics\CLI\bestiary\npc/red-ruin-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 208*  

Known for her incredible awareness and reflexes, the dragonnel-flying ace Red Ruin leads the Red Dragon Army's airborne forces. Her actual name is unknown, leading her allies to refer to her merely as "commander" or "Red Ruin"—a sobriquet earned after razing numerous targets from the air. She rarely removes her distinctive dragonnel-shaped helmet, leading to speculation about her actual identity. She also speaks little, relying on sharp hand gestures to direct dragonnel-riders in flight.

```statblock
"name": "Red Ruin (DSotDQ)"
"size": "Medium"
"type": "humanoid"
"alignment": "Lawful Evil"
"ac": !!int "20"
"ac_class": "[plate](/2-Mechanics/CLI/items/plate-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "150"
"hit_dice": "20d8 + 60"
"stats":
- !!int "19"
- !!int "12"
- !!int "17"
- !!int "13"
- !!int "14"
- !!int "15"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
  "Strength": !!int "8"
"skillsaves":
  "Athletics": !!int "8"
  "Perception": !!int "6"
"damage_resistances": "fire"
"senses": "passive Perception 16"
"languages": "Common, Draconic"
"cr": "10"
"traits":
- "desc": "While Red Ruin can see a Dragon that isn't hostile to her, she has advantage\
    \ on attack rolls."
  "name": "Draconic Devotion"
- "desc": "When Red Ruin is mounted and a creature targets her mount with an attack,\
    \ Red Ruin can cause the attack to target her instead."
  "name": "Mounted Combat Master"
- "desc": "When Red Ruin or her mount makes a Dexterity saving throw to take half\
    \ damage from an effect, they take no damage on a success and half damage on a\
    \ failure."
  "name": "Mounted Evasion"
"actions":
- "desc": "Red Ruin makes three Ember Lance attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 10\
    \ (1d12 + 4) piercing damage plus 7 (2d6) fire damage. If the target is a\
    \ Medium or smaller creature, it must succeed on a DC 16 Strength saving throw\
    \ or fall [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Ember Lance"
- "desc": "Red Ruin fires an explosive crossbow bolt at a point she can see within\
    \ 120 feet of herself. When the bolt reaches that point, or if it hits an object\
    \ early, it detonates in a 20-foot-radius sphere. Each creature in that area must\
    \ make a DC 15 Dexterity saving throw, taking 35 (10d6) fire damage on a failed\
    \ save, or half as much damage on a successful one."
  "name": "Explosive Hand Crossbow (Recharge 5-6)"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Red%20Ruin.webp"
```
^statblock

```encounter-table
name: Red Ruin
creatures:
 - 1: Red Ruin
```