---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/jttrc
- monster/cr/8
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Diva Luma"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Journeys through the Radiant Citadel p. 71
---
# [Diva Luma](2-Mechanics\CLI\bestiary\npc/diva-luma-jttrc.md)
*Source: Journeys through the Radiant Citadel p. 71*  

```statblock
"name": "Diva Luma (JttRC)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Good alignment"
"ac": !!int "15"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"stats":
- !!int "11"
- !!int "16"
- !!int "14"
- !!int "13"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "6"
  "Intelligence": !!int "4"
"skillsaves":
  "Deception": !!int "3"
  "Stealth": !!int "9"
  "Perception": !!int "3"
  "Acrobatics": !!int "6"
"damage_resistances": "poison"
"senses": "passive Perception 13"
"languages": "Thieves' cant plus any two languages"
"cr": "8"
"traits":
- "desc": "During its first turn, Diva Luma has advantage on attack rolls against\
    \ any creature that hasn't taken a turn. Any hit Diva Luma scores against a [surprised](/2-Mechanics/CLI/rules/conditions.md#surprised)\
    \ creature is a critical hit."
  "name": "Assassinate"
- "desc": "If Diva Luma is subjected to an effect that allows it to make a Dexterity\
    \ saving throw to take only half damage, Diva Luma instead takes no damage if\
    \ it succeeds on the saving throw, and only half damage if it fails."
  "name": "Evasion"
- "desc": "Diva Luma deals an extra 14 (4d6) damage when it hits a target with a\
    \ weapon attack and has advantage on the attack roll, or when the target is within\
    \ 5 feet of an ally of Diva Luma that isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ and Diva Luma doesn't have disadvantage on the attack roll."
  "name": "Sneak Attack (1/Turn)"
"actions":
- "desc": "Diva Luma makes two high-heeled shoe attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "High-Heeled Shoe"
"source":
- "JttRC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/JttRC/Diva%20Luma.webp"
```
^statblock

```encounter-table
name: Diva Luma
creatures:
 - 1: Diva Luma
```