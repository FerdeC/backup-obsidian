---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/8
- monster/size/large
- monster/type/construct
aliases: ["Fiendish Flesh Golem"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 236
---
# [Fiendish Flesh Golem](2-Mechanics\CLI\bestiary\construct/fiendish-flesh-golem-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 236*  

A fiendish flesh golem is a particularly big flesh golem made of stitched-together body parts from devils, demons, yugoloths, and other fiends. As these parts can come from different creatures and be combined in different ways, no two fiendish flesh golems look exactly alike. Night hags guard the secret to making such golems, rarely sharing it with anyone else.

Some fiendish flesh golems have wings. However, the magic used to create these golems allows them to fly and hover even without wings.

```statblock
"name": "Fiendish Flesh Golem (BGDIA)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "210"
"hit_dice": "20d10 + 100"
"stats":
- !!int "20"
- !!int "9"
- !!int "20"
- !!int "7"
- !!int "10"
- !!int "5"
"speed": "30 ft., fly 30 ft. (hover)"
"damage_resistances": "cold, fire"
"damage_immunities": "lightning; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't adamantine or silvered"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "8"
"traits":
- "desc": "Whenever the golem starts its turn with 100 hit points or fewer, roll a\
    \ d6. On a 6, the golem goes berserk. On each of its turns while berserk, the\
    \ golem attacks the nearest creature it can see. If no creature is near enough\
    \ to move to and attack, the golem attacks an object, with preference for an object\
    \ smaller than itself. Once the golem goes berserk, it continues to do so until\
    \ it is destroyed or regains all its hit points. If the golem's creator is within\
    \ 60 feet of the berserk golem, the creator can try to calm it by speaking firmly\
    \ and persuasively. The golem must be able to hear its creator, who must take\
    \ an action to make a DC 15 Charisma ([Persuasion](/2-Mechanics/CLI/rules/skills.md#Persuasion))\
    \ check. If the check succeeds, the golem ceases being berserk. If it takes damage\
    \ while still at 100 hit points or fewer, the golem might go berserk again."
  "name": "Berserk"
- "desc": "The golem is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
- "desc": "Whenever the golem is subjected to lightning damage, it takes no damage\
    \ and instead regains a number of hit points equal to the lightning damage dealt."
  "name": "Lightning Absorption"
- "desc": "The golem has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The golem's weapon attacks are magical."
  "name": "Magic Weapons"
"actions":
- "desc": "The golem makes two slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 16\
    \ (2d10 + 5) bludgeoning damage."
  "name": "Slam"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Fiendish%20Flesh%20Golem.webp"
```
^statblock

```encounter-table
name: Fiendish Flesh Golem
creatures:
 - 1: Fiendish Flesh Golem
```