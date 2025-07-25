---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Necromite of Myrkul"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 234
---
# [Necromite of Myrkul](2-Mechanics\CLI\bestiary\humanoid/necromite-of-myrkul-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 234*  

Those who follow Myrkul are either wizards or those who seek to master the necromantic arts.

## Delvers into Lore

Cultists of Myrkul study rituals that allow them to force the souls of the dead into service, compelling them to answer questions and share forgotten lore. They seek out arcane secrets in ancient ruins, and attempt to steal spellbooks and other tomes from wizards outside of the cult.

## Cult Ranks

A follower of Myrkul wields a flail that has a skull replacing the normal flail's striking head. Necromites are initiates who have not yet mastered arcane magic and rely on their flails in battle. Skull lashers are spellcasters who use magic to augment their combat abilities. The Masters of Souls delve deep into Myrkul's secrets, allowing them to animate the dead and perform other grave magic.

```statblock
"name": "Necromite of Myrkul (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "11"
"hp": !!int "13"
"hit_dice": "2d8 + 4"
"stats":
- !!int "10"
- !!int "13"
- !!int "15"
- !!int "16"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Religion": !!int "5"
  "Arcana": !!int "5"
"senses": "passive Perception 10"
"languages": "Abyssal, Common, Infernal"
"cr": "1/2"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 4 (1d8)\
    \ bludgeoning damage."
  "name": "Skull Flail"
- "desc": "Ranged Spell Attack: +5 to hit, range 90 ft., one target. Hit: 8\
    \ (2d4 + 3) necrotic damage."
  "name": "Claws of the Grave"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Necromite%20of%20Myrkul.webp"
```
^statblock

```encounter-table
name: Necromite of Myrkul
creatures:
 - 1: Necromite of Myrkul
```