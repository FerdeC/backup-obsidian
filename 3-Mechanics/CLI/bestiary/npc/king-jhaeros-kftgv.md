---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/9
- monster/size/large
- monster/type/construct
aliases: ["King Jhaeros"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 158
---
# [King Jhaeros](2-Mechanics\CLI\bestiary\npc/king-jhaeros-kftgv.md)
*Source: Keys from the Golden Vault p. 158*  

Known for its exquisite glasswork, Ghalasine was a prosperous city ruled by King Jhaeros Astolko. Governing from Castle Cinis, Jhaeros was advised by two councilors, Regine LaVerne and Charmayne Daymore, and a guard captain named Naevys Tharesso. Jhaeros's rule was compassionate, just, and kind. Over the last year, however, Naevys watched with growing concern as Jhaeros became more withdrawn and secretive, closing Ghalasine to trade and failing to honor his alliances.

Jhaeros has been transformed into a heartless puppet under Charmayne's command.

```statblock
"name": "King Jhaeros (KftGV)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "133"
"hit_dice": "14d10 + 56"
"stats":
- !!int "20"
- !!int "9"
- !!int "18"
- !!int "10"
- !!int "10"
- !!int "10"
"speed": "20 ft."
"damage_immunities": "poison; psychic; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't adamantine"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "understands Common, Draconic, Elvish, and Ignan but can't speak"
"cr": "9"
"traits":
- "desc": "Whenever Jhaeros is subjected to fire damage, he takes no damage and instead\
    \ regains a number of hit points equal to the fire damage dealt."
  "name": "Fire Absorption"
- "desc": "Whenever Jhaeros starts its turn with 60 hit points or fewer, roll a d6.\
    \ On a 6, Jhaeros goes berserk. On each of its turns while berserk, Jhaeros attacks\
    \ the nearest creature it can see. If no creature is near enough to move to and\
    \ attack, Jhaeros attacks an object, with preference for an object smaller than\
    \ itself. Once Jhaeros goes berserk, it continues to do so until it is destroyed\
    \ or regains all its hit points."
  "name": "Berserk"
- "desc": "Jhaeros is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
- "desc": "Jhaeros has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Jhaeros's weapon attacks are magical."
  "name": "Magic Weapons"
- "desc": "When Jhaeros drops to 0 hit points, he explodes in a harmless cloud of\
    \ ashes, leaving nothing else behind."
  "name": "Ashen Creature"
"actions":
- "desc": "Jhaeros makes two slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 16\
    \ (2d10 + 5) bludgeoning damage. If the target is a creature, it must succeed\
    \ on a DC 15 Constitution saving throw or have its hit point maximum reduced by\
    \ an amount equal to the damage taken. The target dies if this attack reduces\
    \ its hit point maximum to 0. The reduction lasts until removed by the  [greater\
    \ restoration](/2-Mechanics/CLI/spells/greater-restoration.md) spell or other\
    \ magic."
  "name": "Slam"
- "desc": "Until the end of its next turn, Jhaeros magically gains a +2 bonus to its\
    \ AC, has advantage on Dexterity saving throws, and can use its slam attack as\
    \ a bonus action."
  "name": "Haste (Recharge 5-6)"
"source":
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/KftGV/King%20Jhaeros.webp"
```
^statblock

```encounter-table
name: King Jhaeros
creatures:
 - 1: King Jhaeros
```