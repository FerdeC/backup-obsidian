---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/3
- monster/size/large
- monster/type/monstrosity
aliases: ["Emberhorn Minotaur"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 120
---
# [Emberhorn Minotaur](2-Mechanics\CLI\bestiary\monstrosity/emberhorn-minotaur-pota.md)
*Source: Princes of the Apocalypse p. 120*  

```statblock
"name": "Emberhorn Minotaur (PotA)"
"size": "Large"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "76"
"hit_dice": "9d10 + 27"
"stats":
- !!int "18"
- !!int "11"
- !!int "16"
- !!int "6"
- !!int "16"
- !!int "9"
"speed": "40 ft."
"skillsaves":
  "Perception": !!int "7"
"damage_immunities": "fire"
"senses": "darkvision 60 ft., passive Perception 17"
"languages": "Abyssal"
"cr": "3"
"traits":
- "desc": "If the minotaur moves at least 10 feet straight toward a target and then\
    \ hits it with a gore attack on the same turn, the target takes an extra 9 (2d8)\
    \ piercing damage. If the target is a creature, it must succeed on a DC 14 Strength\
    \ saving throw or be pushed up to 10 feet away and knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Charge"
- "desc": "The minotaur can perfectly recall any path it has traveled."
  "name": "Labyrinthine Recall"
- "desc": "At the start of its turn, the minotaur can gain advantage on all melee\
    \ weapon attack rolls it makes during that turn, but attack rolls against it have\
    \ advantage until the start of its next turn."
  "name": "Reckless"
"actions":
- "desc": "The minotaur exhales a cloud of burning embers in a 15-foot cone. Each\
    \ creature in that area must succeed on a DC 14 Dexterity saving throw, taking\
    \ 21 (6d6) fire damage on a failed save, or half as much damage on a successful\
    \ one."
  "name": "Burning Breath (Recharge 5-6)"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 17\
    \ (2d12 + 4) slashing damage."
  "name": "Greataxe"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) piercing damage."
  "name": "Gore"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Emberhorn%20Minotaur.webp"
```
^statblock

```encounter-table
name: Emberhorn Minotaur
creatures:
 - 1: Emberhorn Minotaur
```