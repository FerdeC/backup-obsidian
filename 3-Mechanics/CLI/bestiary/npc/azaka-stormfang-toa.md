---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/human
- monster/type/humanoid/shapechanger
aliases: ["Azaka Stormfang"]
NoteIcon: monster
BestiaryType: humanoid (human, shapechanger)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 33
---
# [Azaka Stormfang](2-Mechanics\CLI\bestiary\npc/azaka-stormfang-toa.md)
*Source: Tomb of Annihilation p. 33*  

```statblock
"name": "Azaka Stormfang (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, shapechanger"
"alignment": "Neutral Good"
"ac": !!int "12"
"hp": !!int "120"
"hit_dice": "16d8 + 48"
"stats":
- !!int "17"
- !!int "15"
- !!int "16"
- !!int "10"
- !!int "13"
- !!int "11"
"speed": "30 ft. (40 ft. in tiger form)"
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "5"
"damage_immunities": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't silvered"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common (can't speak in tiger form)"
"cr": "4"
"traits":
- "desc": "The Azaka can use its action to polymorph into a tiger-humanoid hybrid\
    \ or into a tiger, or back into its true form, which is humanoid. Its statistics,\
    \ other than its size, are the same in each form. Any equipment it is wearing\
    \ or carrying isn't transformed. It reverts to its true form if it dies."
  "name": "Shapechanger"
- "desc": "The Azaka has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or smell."
  "name": "Keen Hearing and Smell"
- "desc": "If the Azaka moves at least 15 feet straight toward a creature and then\
    \ hits it with a claw attack on the same turn, that target must succeed on a DC\
    \ 14 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone).\
    \ If the target is [prone](/2-Mechanics/CLI/rules/conditions.md#prone), the Azaka\
    \ can make one bite attack against it as a bonus action."
  "name": "Pounce (Tiger or Hybrid Form Only)"
"actions":
- "desc": "In humanoid form, the Azaka makes two scimitar attacks or two longbow attacks.\
    \ In hybrid form, it can attack like a humanoid or make two claw attacks."
  "name": "Multiattack (Humanoid or Hybrid Form Only)"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (1d10\
    \ + 3) piercing damage. If the target is a humanoid, it must succeed on a DC\
    \ 13 Constitution saving throw or be cursed with Azaka lycanthropy."
  "name": "Bite (Tiger or Hybrid Form Only)"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage."
  "name": "Claw (Tiger or Hybrid Form Only)"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Scimitar (Humanoid or Hybrid Form Only)"
- "desc": "Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. Hit:\
    \ 6 (1d8 + 2) piercing damage."
  "name": "Longbow (Humanoid or Hybrid Form Only)"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Azaka%20Stormfang.webp"
```
^statblock

```encounter-table
name: Azaka Stormfang
creatures:
 - 1: Azaka Stormfang
```