---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/vgm
- monster/cr/1-4
- monster/size/small
- monster/type/humanoid/goblinoid
aliases: ["Booyahg Wielder"]
NoteIcon: monster
BestiaryType: humanoid (goblinoid)
SourceType: Bestiary
BookSource: Volo's Guide to Monsters p. 42
---
# [Booyahg Wielder](2-Mechanics\CLI\bestiary\humanoid/booyahg-wielder-vgm.md)
*Source: Volo's Guide to Monsters p. 42*  

This goblin found a magic item (a [necklace of fireballs](/2-Mechanics/CLI/items/necklace-of-fireballs.md), a [circlet of blasting](/2-Mechanics/CLI/items/circlet-of-blasting.md), or the like) and learned how to use it.

## Booyahgs

Spellcasters of any sort among the goblins are rare. Goblins typically lack the intelligence and patience needed to learn and practice wizardry, and they fare poorly even when given access to the necessary training and knowledge. Sorcerers are less prevalent among them than in many other races, and Khurgorbaeyag seems to dislike sharing his divine power with his followers. And although many goblins would readily offer anything to have the abilities of a warlock, the patrons that grant such power know a goblin is unlikely to be able to uphold its end of any bargain.

Even when a goblin is born with the ability to become a spellcaster, the knowledge and talent necessary to carry on the tradition rarely persists for more than a couple of generations. Because they have so little experience with magic, goblins make no distinction between its forms. To them all magic is "booyahg," and the word is part of the name they give to any of its practitioners.

A goblin with access to booyahg becomes a member of the lashers and can often rise to the role of boss.

```statblock
"name": "Booyahg Wielder (VGM)"
"size": "Small"
"type": "humanoid"
"subtype": "goblinoid"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "7"
"hit_dice": "2d6"
"stats":
- !!int "8"
- !!int "14"
- !!int "10"
- !!int "10"
- !!int "8"
- !!int "8"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "6"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Goblin"
"cr": "1/4"
"traits":
- "desc": "The goblin can take the Disengage or Hide action as a bonus action on each\
    \ of its turns."
  "name": "Nimble Escape"
- "desc": "The goblin found a magic item (a [necklace of fireballs](/2-Mechanics/CLI/items/necklace-of-fireballs.md),\
    \ a [circlet of blasting](/2-Mechanics/CLI/items/circlet-of-blasting.md), or the\
    \ like) and learned how to use it."
  "name": "Special Equipment"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) slashing damage."
  "name": "Scimitar"
- "desc": "Ranged Weapon Attack: +4 to hit, range 80/320 ft., one target. Hit:\
    \ 5 (1d6 + 2) piercing damage."
  "name": "Shortbow"
"source":
- "VGM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/VGM/Booyahg%20Wielder.webp"
```
^statblock

```encounter-table
name: Booyahg Wielder
creatures:
 - 1: Booyahg Wielder
```