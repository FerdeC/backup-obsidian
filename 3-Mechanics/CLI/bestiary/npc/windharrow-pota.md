---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/half-elf
aliases: ["Windharrow"]
NoteIcon: monster
BestiaryType: humanoid (half-elf)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 192
---
# [Windharrow](2-Mechanics\CLI\bestiary\npc/windharrow-pota.md)
*Source: Princes of the Apocalypse p. 192*  

An opportunistic half-moon elf rake and bandit formerly known as Harald Grayspear, Windharrow was given his new name by Aerisi Kalinoth. When Aerisi was still with her family, Harald charmed and flattered his way into her favor. When Aerisi ran away from home to become the air prophet, she took Windharrow with her.

At Aerisi's insistence, Windharrow recruited a band of flutists from the ranks of new converts to the air cult, calling them the Windwyrds. Most have no musical talent whatsoever, and their music is often a shrill cacophony. Of all the air cultists, the Windwyrds are the least fanatical and the most fearful for their lives. Aerisi disposes of these minstrels on a whim, replacing them with other initiates. Those that master some skill with their instruments survive the longest, but the cost of failure creates a highly competitive environment among the minstrels.

Windharrow is loyal to Aerisi Kalinoth as long as he fears her power. If his life is threatened or a richer offer presents itself, Windharrow betrays the air cult without a backward glance.

```statblock
"name": "Windharrow (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-elf"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "55"
"hit_dice": "10d8 + 10"
"stats":
- !!int "10"
- !!int "16"
- !!int "12"
- !!int "14"
- !!int "10"
- !!int "17"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "7"
  "Stealth": !!int "5"
  "Performance": !!int "7"
  "Acrobatics": !!int "5"
  "Persuasion": !!int "5"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Auran, Common, Elvish"
"cr": "3"
"traits":
- "desc": "Windharrow is an 8th-level spellcaster. His spellcasting ability is Charisma\
    \ (spell save DC 13, +5 to hit with spell attacks). Windharrow knows the following\
    \ bard spells:\n\nCantrips (at will): [friends](/2-Mechanics/CLI/spells/friends.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md), [vicious mockery](/2-Mechanics/CLI/spells/vicious-mockery.md)\n\
    \n1st level (4 slots): [disguise self](/2-Mechanics/CLI/spells/disguise-self.md),\
    \ [dissonant whispers](/2-Mechanics/CLI/spells/dissonant-whispers.md), [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md)\n\
    \n2nd level (3 slots): [invisibility](/2-Mechanics/CLI/spells/invisibility.md),\
    \ [shatter](/2-Mechanics/CLI/spells/shatter.md), [silence](/2-Mechanics/CLI/spells/silence.md)\n\
    \n3rd level (3 slots): [nondetection](/2-Mechanics/CLI/spells/nondetection.md),\
    \ [sending](/2-Mechanics/CLI/spells/sending.md), [tongues](/2-Mechanics/CLI/spells/tongues.md)\n\
    \n4th level (2 slots): [confusion](/2-Mechanics/CLI/spells/confusion.md),\
    \ [dimension door](/2-Mechanics/CLI/spells/dimension-door.md)"
  "name": "Spellcasting"
- "desc": "Windharrow has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put him to sleep."
  "name": "Fey Ancestry"
"actions":
- "desc": "Windharrow makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 7\
    \ (1d8 + 3) piercing damage."
  "name": "Rapier"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Windharrow.webp"
```
^statblock

```encounter-table
name: Windharrow
creatures:
 - 1: Windharrow
```