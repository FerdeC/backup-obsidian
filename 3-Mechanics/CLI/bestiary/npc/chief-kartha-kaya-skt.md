---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/4
- monster/size/large
- monster/type/monstrosity
aliases: ["Chief Kartha-Kaya"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Storm King's Thunder p. 173
---
# [Chief Kartha-Kaya](2-Mechanics\CLI\bestiary\npc/chief-kartha-kaya-skt.md)
*Source: Storm King's Thunder p. 173*  

```statblock
"name": "Chief Kartha-Kaya (SKT)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "11"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "70"
"hit_dice": "8d10 + 16"
"stats":
- !!int "18"
- !!int "11"
- !!int "15"
- !!int "14"
- !!int "15"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "4"
  "Survival": !!int "4"
"senses": "passive Perception 12"
"languages": "Common, Yikaria"
"cr": "4"
"traits":
- "desc": "Chief Kartha attempts to magically possess a humanoid or giant. Chief Kartha\
    \ must touch the target throughout a short rest, or the attempt fails. At the\
    \ end of the rest, the target must succeed on a DC 12 Constitution saving throw\
    \ or be possessed by Chief Kartha, which disappears with everything it is carrying\
    \ and wearing. Until the possession ends, the target is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated),\
    \ loses control of its body, and is unaware of its surroundings. Chief Kartha\
    \ now controls the body and can't be targeted by any attack, spell, or other effect,\
    \ and it retains its alignment; its Intelligence, Wisdom, and Charisma scores;\
    \ and its proficiencies. It otherwise uses the target's statistics, except the\
    \ target's knowledge, class features, feats, and proficiencies.\n\nThe possession\
    \ lasts until either the body drops to 0 hit points, Chief Kartha ends the possession\
    \ as an action, or Chief Kartha is forced out of the body by an effect such as\
    \ the [dispel evil and good](/2-Mechanics/CLI/spells/dispel-evil-and-good.md)\
    \ spell. When the possession ends, Chief Kartha reappears in an unoccupied space\
    \ within 5 feet of the body and is [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)\
    \ until the end of its next turn. If the host body dies while it is possessed\
    \ by Chief Kartha, Chief Kartha dies as well, and its body doesn't reappear."
  "name": "Possession (Recharges after a Short or Long Rest)"
"actions":
- "desc": "Chief Kartha makes two attacks, either with his flame tongue greatsword\
    \ or his longbow."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 18\
    \ (4d6 + 4) slashing damage plus 7 (2d6) fire damage."
  "name": "Flame Tongue Greatsword"
- "desc": "Ranged Weapon Attack: +2 to hit, range 150/600 ft., one target. Hit:\
    \ 9 (2d8) piercing damage."
  "name": "Longbow"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Chief%20Kartha-Kaya.webp"
```
^statblock

```encounter-table
name: Chief Kartha-Kaya
creatures:
 - 1: Chief Kartha-Kaya
```