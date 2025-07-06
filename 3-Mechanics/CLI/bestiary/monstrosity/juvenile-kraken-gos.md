---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/14
- monster/size/huge
- monster/type/monstrosity/titan
aliases: ["Juvenile Kraken"]
NoteIcon: monster
BestiaryType: monstrosity (titan)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 238
---
# [Juvenile Kraken](2-Mechanics\CLI\bestiary\monstrosity/juvenile-kraken-gos.md)
*Source: Ghosts of Saltmarsh p. 238*  

Hidden in a deep, dark underwater pit near the Styes, this creature bears the mark of the dark god Tharizdun's madness. Becoming more independent every day, it dreams of freeing itself from its aboleth tenders and wreaking its own foul will upon the seas.

```statblock
"name": "Juvenile Kraken (GoS)"
"size": "Huge"
"type": "monstrosity"
"subtype": "titan"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "207"
"hit_dice": "18d12 + 90"
"stats":
- !!int "24"
- !!int "11"
- !!int "20"
- !!int "19"
- !!int "15"
- !!int "17"
"speed": "20 ft., swim 50 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "7"
  "Intelligence": !!int "9"
  "Strength": !!int "12"
  "Constitution": !!int "10"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "lightning"
"condition_immunities": "[frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed)"
"senses": "truesight 120 ft., passive Perception 12"
"languages": "Abyssal, Celestial, Infernal, Primordial, telepathy 60 ft. but can't\
  \ speak"
"cr": "14"
"traits":
- "desc": "The kraken can breathe air and water."
  "name": "Amphibious"
- "desc": "The kraken ignores difficult terrain, and magical effects can't reduce\
    \ its speed or cause it to be [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained).\
    \ It can spend 5 feet of movement to escape from nonmagical restraints or being\
    \ [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)."
  "name": "Freedom of Movement"
"actions":
- "desc": "The kraken makes two tentacle attacks, each of which it can replace with\
    \ a use of Fling."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 20\
    \ (3d8 + 7) piercing damage. If the target is a Medium or smaller creature [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ by the kraken, that creature is swallowed and the grapple ends. While swallowed,\
    \ the creature is [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded) and\
    \ [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained), it has total\
    \ cover against attacks and other effects outside the kraken, and it takes 21\
    \ (6d6) acid damage at the start of each of the kraken's turns. One Medium or\
    \ two smaller creatures can be swallowed at the same time.\n\nIf the kraken takes\
    \ 35 damage or more on a single turn from a creature inside it, the kraken must\
    \ succeed on a DC 23 Constitution saving throw at the end of that turn or regurgitate\
    \ all swallowed creatures, which fall [prone](/2-Mechanics/CLI/rules/conditions.md#prone)\
    \ in spaces within 10 feet of the kraken. If the kraken dies, a swallowed creature\
    \ is no longer [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained) by\
    \ it and can escape from the corpse using 10 feet of movement, exiting [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +12 to hit, reach 20 ft., one target. Hit: 17\
    \ (3d6 + 7) bludgeoning damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 20). Until the grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained).\
    \ The kraken has ten tentacles, each of which can grapple one target."
  "name": "Tentacle"
- "desc": "One Medium or smaller object held or creature [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ by the kraken is thrown up to 40 feet in a random direction and knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone).\
    \ If a thrown target strikes a solid surface, the target takes 3 (1d6) bludgeoning\
    \ damage for every 10 feet it was thrown. If the target is thrown at another creature,\
    \ that creature must succeed on a DC 13 Dexterity saving throw or take the same\
    \ damage and be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Fling"
- "desc": "The kraken magically create a bolt of lightning, which can strike a target\
    \ the kraken can see within 90 feet of it. The target must make a DC 18 Dexterity\
    \ saving throw, taking 22 (4d10) lightning damage on a failed save, or half\
    \ as much damage on a successful one."
  "name": "Lightning Strike"
"legendary_actions":
- "desc": "The kraken makes one tentacle attack."
  "name": "Tentacle Attack (Costs 2 Actions)"
- "desc": "The kraken uses Fling."
  "name": "Fling"
- "desc": "While underwater, the kraken expels an ink cloud in a 40-foot radius. The\
    \ cloud spreads around corners, and that area is heavily obscured to creatures\
    \ other than the kraken. Each creature other than the kraken that ends its turn\
    \ there must succeed on a DC 18 Constitution saving throw, taking 11 (2d10)\
    \ poison damage on a failed save or half as much damage on a successful one. A\
    \ strong current disperses the cloud, which otherwise disappears at the end of\
    \ the kraken's next turn."
  "name": "Ink Cloud (Costs 3 Actions)"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Juvenile%20Kraken.webp"
```
^statblock

```encounter-table
name: Juvenile Kraken
creatures:
 - 1: Juvenile Kraken
```