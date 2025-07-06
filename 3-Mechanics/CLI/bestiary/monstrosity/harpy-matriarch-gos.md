---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/5
- monster/size/medium
- monster/type/monstrosity
aliases: ["Harpy Matriarch"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 237
---
# [Harpy Matriarch](2-Mechanics\CLI\bestiary\monstrosity/harpy-matriarch-gos.md)
*Source: Ghosts of Saltmarsh p. 237*  

Happy to watch its flock squabble over carrion in Tammeraut's Fate, this gray-feathered matron of the harpies is surrounded by a cloud of magical spirits resembling skeletal seabirds.

```statblock
"name": "Harpy Matriarch (GoS)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "88"
"hit_dice": "16d8 + 16"
"stats":
- !!int "13"
- !!int "16"
- !!int "12"
- !!int "9"
- !!int "10"
- !!int "16"
"speed": "20 ft., fly 40 ft."
"saves":
  "Charisma": !!int "6"
  "Dexterity": !!int "6"
"skillsaves":
  "Perception": !!int "3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common"
"cr": "5"
"traits":
- "desc": "While within 60 feet of the matriarch, creatures have disadvantage on saving\
    \ throws against the matriarch's Luring Song."
  "name": "Luring Maestro"
- "desc": "The matriarch has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The matriarch makes two claws attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13\
    \ (3d6 + 3) slashing damage."
  "name": "Claws"
- "desc": "The matriarch can magically disguise itself to resemble a humanoid of roughly\
    \ similar size and shape for up to 1 hour. It can revert to its true form as a\
    \ bonus action. This illusion does not hold up to close scrutiny."
  "name": "Fleeting Form"
- "desc": "The matriarch sings a magical melody. Every humanoid and giant within 300\
    \ feet of the matriarch that can hear the song must succeed on a DC 14 Wisdom\
    \ saving throw or be [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed) until\
    \ the song ends. The matriarch must take a bonus action on its subsequent turns\
    \ to continue singing. It can stop singing at any time. The song ends if the matriarch\
    \ is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated).\n\n\
    While [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed) by the matriarch,\
    \ a target is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ and ignores the songs of other harpies. If the [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ target is more than 5 feet away from the matriarch, the target must move on\
    \ its turn toward the matriarch by the most direct route, trying to get within\
    \ 5 feet. It doesn't avoid opportunity attacks, but before moving into damaging\
    \ terrain, such as lava or a pit, and whenever it takes damage from a source other\
    \ than the matriarch, the target can repeat the saving throw. A [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ target can also repeat the saving throw at the end of each of its turns. If\
    \ the saving throw is successful, the effect ends on it.\n\nA target that successfully\
    \ saves is immune to this matriarch's song for the next 24 hours."
  "name": "Luring Song"
- "desc": "The matriarch projects a vision into the minds of creatures within 30 feet\
    \ of it that aren't constructs or undead, showing each creature achieving whatever\
    \ it most desires. An affected creature must succeed on a DC 14 Wisdom saving\
    \ throw or drop whatever it is holding and become [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed)\
    \ until the end of its next turn."
  "name": "Visage of Desire (1/Day)"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Harpy%20Matriarch.webp"
```
^statblock

```encounter-table
name: Harpy Matriarch
creatures:
 - 1: Harpy Matriarch
```