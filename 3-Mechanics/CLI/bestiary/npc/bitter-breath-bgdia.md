---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/11
- monster/size/large
- monster/type/fiend/devil
aliases: ["Bitter Breath"]
NoteIcon: monster
BestiaryType: fiend (devil)
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 90
---
# [Bitter Breath](2-Mechanics\CLI\bestiary\npc/bitter-breath-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 90*  

```statblock
"name": "Bitter Breath (BGDIA)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "178"
"hit_dice": "17d10 + 85"
"stats":
- !!int "22"
- !!int "17"
- !!int "21"
- !!int "12"
- !!int "16"
- !!int "17"
"speed": "20 ft."
"saves":
  "Charisma": !!int "7"
  "Dexterity": !!int "7"
  "Wisdom": !!int "7"
  "Strength": !!int "10"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Infernal, telepathy 120 ft."
"cr": "11"
"traits":
- "desc": "Magical darkness doesn't impede Bitter Breath's darkvision."
  "name": "Devil's Sight"
- "desc": "Bitter Breath has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Bitter Breath makes three melee attacks: two with its fork and one with\
    \ its tail. It can use Hurl Flame in place of any melee attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 15\
    \ (2d8 + 6) piercing damage."
  "name": "Fork"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 10\
    \ (1d8 + 6) piercing damage. If the target is a creature other than an undead\
    \ or a construct, it must succeed on a DC 17 Constitution saving throw or lose\
    \ 10 (3d6) hit points at the start of each of its turns due to an infernal wound.\
    \ Each time Bitter Breath hits the wounded target with this attack, the damage\
    \ dealt by the wound increases by 10 (3d6). Any creature can take an action\
    \ to stanch the wound with a successful DC 12 Wisdom ([Medicine](/2-Mechanics/CLI/rules/skills.md#Medicine))\
    \ check. The wound also closes if the target receives magical healing."
  "name": "Tail"
- "desc": "Ranged Spell Attack: +7 to hit, range 150 ft., one target. Hit: 14\
    \ (4d6) fire damage. If the target is a flammable object that isn't being worn\
    \ or carried, it also catches fire."
  "name": "Hurl Flame"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Bitter%20Breath.webp"
```
^statblock

```encounter-table
name: Bitter Breath
creatures:
 - 1: Bitter Breath
```