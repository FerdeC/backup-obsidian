---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/11
- monster/size/large
- monster/type/monstrosity
aliases: ["Torogar Steelfist"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 112
---
# [Torogar Steelfist](2-Mechanics\CLI\bestiary\npc/torogar-steelfist-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 112*  

```statblock
"name": "Torogar Steelfist (BGDIA)"
"size": "Large"
"type": "monstrosity"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "168"
"hit_dice": "16d10 + 80"
"stats":
- !!int "25"
- !!int "17"
- !!int "20"
- !!int "8"
- !!int "9"
- !!int "16"
"speed": "40 ft."
"saves":
  "Strength": !!int "11"
  "Constitution": !!int "9"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Abyssal, Common"
"cr": "11"
"traits":
- "desc": "Immediately after using the Dash action, Torogar can make one melee attack\
    \ with his horns."
  "name": "Goring Rush"
- "desc": "Torogar can perfectly recall any path he has traveled."
  "name": "Labyrinthine Recall"
- "desc": "As a bonus action, Torogar can enter a rage that lasts for 1 minute. The\
    \ rage ends early if Torogar is knocked [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)\
    \ or if his turn ends and he hasn't attacked a hostile creature or taken damage\
    \ since his last turn. While raging, Torogar gains the following benefits:\n\n\
    He has advantage on Strength checks and Strength saving throws.\n\nHe deals an\
    \ extra 3 damage when he hits a target with a melee weapon attack.\n\nHe has resistance\
    \ to bludgeoning, piercing, and slashing damage."
  "name": "Rage (Recharges after a Short or Long Rest)"
- "desc": "Torogar wears [gauntlets of flaming fury](/2-Mechanics/CLI/items/gauntlets-of-flaming-fury-bgdia.md)\
    \ and a [belt of fire giant strength](/2-Mechanics/CLI/items/belt-of-fire-giant-strength.md).\
    \ Without the belt, his Strength is 21. He also carries a [soul coin](/2-Mechanics/CLI/items/soul-coin-bgdia.md)."
  "name": "Special Equipment"
"actions":
- "desc": "Torogar makes three attacks: two with his scimitars and one with his horns."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 5 ft., one target. Hit: 14\
    \ (2d6 + 7) slashing damage, or 17 (2d6 + 10) slashing damage while raging,\
    \ plus 3 (1d6) fire damage from the gauntlets of flaming fury."
  "name": "Scimitar"
- "desc": "Melee Weapon Attack: +11 to hit, reach 5 ft., one target. Hit: 16\
    \ (2d8 + 7) piercing damage, or 19 (2d8 + 10) piercing damage while raging."
  "name": "Horns"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Torogar%20Steelfist.webp"
```
^statblock

```encounter-table
name: Torogar Steelfist
creatures:
 - 1: Torogar Steelfist
```