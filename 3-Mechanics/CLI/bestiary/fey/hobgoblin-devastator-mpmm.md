---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/4
- monster/environment/forest
- monster/environment/grassland
- monster/environment/hill
- monster/size/medium
- monster/type/fey/goblinoid
aliases: ["Hobgoblin Devastator"]
NoteIcon: monster
BestiaryType: fey (goblinoid)
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 153, Volo's Guide to Monsters p. 161
---
# [Hobgoblin Devastator](2-Mechanics\CLI\bestiary\fey/hobgoblin-devastator-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 153, Volo's Guide to Monsters p. 161*  

Hobgoblins with a prodigious talent for magic sometimes undergo grueling training to become hobgoblin devastators. Devastators are spellcasters who call down fireballs and other destructive magic in the defense of the court they serve, whether that court is in the Feywild or the Material Plane. A hobgoblin devastator on the battlefield is a boon to their allies and a threat to every foe around them.

Far from being cloistered academics, hobgoblin devastators are masters of the battlefield. In addition to tactical applications of the magical arts, they learn the basics of weapon use, and they measure their deeds by the enemies defeated though their magic. They have the respect of other members of the host and receive obedience and deference from many quarters.

In the Feywild, many archfey seek to bolster their armies' might with the services of hobgoblin devastators.

> [!note] Goblinoids of the Feywild
> 
> The goblinoid peoples—goblins, hobgoblins, and bugbears—first appeared in the Feywild millennia ago, and they resided there until the god Maglubiyet conquered them. They then spread throughout the multiverse, with many of them ending up on the worlds of the Material Plane. Most goblinoids encountered on those worlds are members of families that have been away from the Feywild for centuries, and over time, those lineages have become Humanoid. Fey goblinoids, who still bear the magic of the Feywild, are rare on the Material Plane but not unheard of. Hobgoblin devastators are examples of such Fey folk, as are hobgoblin iron shadows and nilbogs (also in this book).
^goblinoids-of-the-feywild

```statblock
"name": "Hobgoblin Devastator (MPMM)"
"size": "Medium"
"type": "fey"
"subtype": "goblinoid"
"alignment": "Typically  Lawful Neutral"
"ac": !!int "13"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "45"
"hit_dice": "7d8 + 14"
"stats":
- !!int "13"
- !!int "12"
- !!int "14"
- !!int "16"
- !!int "13"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Arcana": !!int "5"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Goblin"
"cr": "4"
"traits":
- "desc": "The hobgoblin casts one of the following spells, using Intelligence as\
    \ the spellcasting ability (spell save DC 13):\n\nAt will: [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\n2/day each:\
    \ [fireball](/2-Mechanics/CLI/spells/fireball.md), [fly](/2-Mechanics/CLI/spells/fly.md),\
    \ [fog cloud](/2-Mechanics/CLI/spells/fog-cloud.md), [gust of wind](/2-Mechanics/CLI/spells/gust-of-wind.md),\
    \ [lightning bolt](/2-Mechanics/CLI/spells/lightning-bolt.md)"
  "name": "Spellcasting"
- "desc": "When the hobgoblin casts a spell that causes damage or that forces other\
    \ creatures to make a saving throw, it can choose itself and any number of allies\
    \ to be immune to the damage caused by the spell and to succeed on the required\
    \ saving throw."
  "name": "Army Arcana"
"actions":
- "desc": "The hobgoblin makes two Quarterstaff or Devastating Bolt attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) bludgeoning damage, or 5 (1d8 + 1) bludgeoning damage if used with two\
    \ hands, plus 13 (3d8) force damage."
  "name": "Quarterstaff"
- "desc": "Ranged Spell Attack: +5 to hit, range 60 ft., one target. Hit: 21\
    \ (4d8 + 3) force damage, and the target is knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Devastating Bolt"
"source":
- "MPMM"
- "VGM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPMM/Hobgoblin%20Devastator.webp"
```
^statblock

```encounter-table
name: Hobgoblin Devastator
creatures:
 - 1: Hobgoblin Devastator
```

## Environment

forest, grassland, hill