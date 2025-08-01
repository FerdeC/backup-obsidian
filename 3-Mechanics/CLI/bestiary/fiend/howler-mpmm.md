---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/8
- monster/environment/desert
- monster/environment/grassland
- monster/environment/hill
- monster/environment/underdark
- monster/size/large
- monster/type/fiend
aliases: ["Howler"]
NoteIcon: monster
BestiaryType: fiend
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 155, Mordenkainen's Tome of Foes p. 210
---
# [Howler](2-Mechanics\CLI\bestiary\fiend/howler-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 155, Mordenkainen's Tome of Foes p. 210*  

> [!quote]- A quote from Mordenkainen  
> 
> Why does the howler sing? Doing so causes its prey to flee, and surely stealth would make for better hunting in howling Pandemonium. There is only one answer: the creature can taste fear.

A far-off wail precedes the sight of a howler. Even at a distance, listeners' minds cringe at the sound and fill with horror at the realization that the noise is drawing closer. When howlers go on the prowl, courage isn't enough to stand up against them.

These nightmare creatures are native to Pandemonium, but they can be found on most of the Lower Planes, where they are trained as war hounds. Howlers can be domesticated, after a fashion, but they respond only to brutal training in which they are forced to recognize the trainer as the pack's undisputed leader. A trained pack then follows its leader without hesitation. Howler packs course over the battlefields of the Blood War and also serve evil mortals powerful and vicious enough to command their loyalty.

Howlers rely on speed, numbers, and their mind-numbing howling to corner prey before they tear it apart. Their howls flood the minds of their victims, making complex thought impossible. Listeners can do little more than stare in horror and stumble around the battlefield in a search for safety. Fiends especially prize howlers for this reason, because for a few crucial moments in a battle, their howls can neutralize an enemy.

```statblock
"name": "Howler (MPMM)"
"size": "Large"
"type": "fiend"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "90"
"hit_dice": "12d10 + 24"
"stats":
- !!int "17"
- !!int "16"
- !!int "15"
- !!int "5"
- !!int "14"
- !!int "6"
"speed": "40 ft."
"skillsaves":
  "Perception": !!int "5"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"condition_immunities": "[frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "understands Abyssal but can't speak"
"cr": "8"
"traits":
- "desc": "A howler has advantage on attack rolls against a creature if at least one\
    \ of the howler's allies is within 5 feet of the creature and the ally isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "The howler makes two Rending Bite attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) piercing damage, plus 22 (4d10) psychic damage if the target is\
    \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened). This attack ignores\
    \ damage resistance."
  "name": "Rending Bite"
- "desc": "The howler emits a keening howl in a 60-foot cone. Each creature in that\
    \ area must succeed on a DC 13 Wisdom saving throw or take 16 (3d10) psychic\
    \ damage and be [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ until the end of the howler's next turn. While a creature is [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ in this way, its speed is halved, and it is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated).\
    \ A target that successfully saves is immune to the Mind-Breaking Howl of all\
    \ howlers for the next 24 hours."
  "name": "Mind-Breaking Howl (Recharge 4-6)"
"source":
- "MPMM"
- "MTF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPMM/Howler.webp"
```
^statblock

```encounter-table
name: Howler
creatures:
 - 1: Howler
```

## Environment

desert, grassland, hill, underdark