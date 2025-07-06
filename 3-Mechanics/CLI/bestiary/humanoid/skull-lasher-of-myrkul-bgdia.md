---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Skull Lasher of Myrkul"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 234
---
# [Skull Lasher of Myrkul](2-Mechanics\CLI\bestiary\humanoid/skull-lasher-of-myrkul-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 234*  

Those who follow Myrkul are either wizards or those who seek to master the necromantic arts.

## Delvers into Lore

Cultists of Myrkul study rituals that allow them to force the souls of the dead into service, compelling them to answer questions and share forgotten lore. They seek out arcane secrets in ancient ruins, and attempt to steal spellbooks and other tomes from wizards outside of the cult.

## Cult Ranks

A follower of Myrkul wields a flail that has a skull replacing the normal flail's striking head. Necromites are initiates who have not yet mastered arcane magic and rely on their flails in battle. Skull lashers are spellcasters who use magic to augment their combat abilities. The Masters of Souls delve deep into Myrkul's secrets, allowing them to animate the dead and perform other grave magic.

```statblock
"name": "Skull Lasher of Myrkul (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"stats":
- !!int "10"
- !!int "14"
- !!int "15"
- !!int "16"
- !!int "13"
- !!int "10"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "3"
"skillsaves":
  "Religion": !!int "5"
  "Arcana": !!int "5"
"senses": "passive Perception 11"
"languages": "Abyssal, Common, Infernal"
"cr": "1"
"traits":
- "desc": "The skull lasher is a 3rd-level spellcaster. Its spellcasting ability is\
    \ Wisdom (spell save DC 13, +5 to hit with spell attacks). It has the following\
    \ wizard spells prepared:\n\nCantrips (at will): [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [message](/2-Mechanics/CLI/spells/message.md), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\
    \n1st level (4 slots): [detect magic](/2-Mechanics/CLI/spells/detect-magic.md),\
    \ [protection from evil and good](/2-Mechanics/CLI/spells/protection-from-evil-and-good.md),\
    \ [ray of sickness](/2-Mechanics/CLI/spells/ray-of-sickness.md) (see \"Actions\"\
    \ below), [shield](/2-Mechanics/CLI/spells/shield.md)\n\n2nd level (2 slots):\
    \ [darkness](/2-Mechanics/CLI/spells/darkness.md), [misty step](/2-Mechanics/CLI/spells/misty-step.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The skull lasher makes two attacks with its flail."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 4 (1d8)\
    \ bludgeoning damage plus 7 (2d6) necrotic damage, and the target has disadvantage\
    \ on all saving throws until the end of the skull lasher's next turn."
  "name": "Iron Skull Flail"
- "desc": "Ranged Spell Attack: +5 to hit, range 60 ft., one creature. Hit:\
    \ 9 (2d8) poison damage, and the target must succeed on a DC 13 Constitution\
    \ saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ until the end of the skull lasher's next turn. If the skull lasher casts this\
    \ spell using a spell slot of 2nd level or higher, the damage increases by 1d8\
    \ for each slot level above 1st."
  "name": "Ray of Sickness (1st-Level Spell; Requires a Spell Slot)"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Skull%20Lasher%20of%20Myrkul.webp"
```
^statblock

```encounter-table
name: Skull Lasher of Myrkul
creatures:
 - 1: Skull Lasher of Myrkul
```