---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/ftd
- monster/cr/5
- monster/size/medium
- monster/type/humanoid
aliases: ["Dragon Blessed"]
NoteIcon: monster
BestiaryType: humanoid
SourceType: Bestiary
BookSource: Fizban's Treasury of Dragons p. 188
---
# [Dragon Blessed](2-Mechanics\CLI\bestiary\humanoid/dragon-blessed-ftd.md)
*Source: Fizban's Treasury of Dragons p. 188*  

Dragon blessed are the acolytes of dragons, whom they revere as gods. They wield magic to heal and support those who have earned their dragon masters' favor—and scourge those who incur the dragons' wrath. Dragon blessed view their lives and magical abilities as gifts bestowed by their dragon, and they give life energy to save those they deem important to their masters' work.

## Dragon Followers

Dragons boast many minions, students, employees, acolytes, and thralls. Dragon followers are those servitors whose devotion to a dragon approaches fanatical reverence and who receive magical power from the dragon in return.

Dragon followers might serve and revere any kind of dragon, and their behavior and beliefs reflect the ethos of the dragon they follow. Many dragon followers have personal stories of benevolent dragons sharing great knowledge, protecting their towns, or sparing their lives during some foolhardy adventure. Other followers seek to uncover the mysteries of draconic nature and live a life worthy of their dragon's reward, and they dream of a world where dragons can live among them as their rulers.

```statblock
"name": "Dragon Blessed (FTD)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[scale mail](/2-Mechanics/CLI/items/scale-mail.md)"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"stats":
- !!int "12"
- !!int "10"
- !!int "16"
- !!int "14"
- !!int "17"
- !!int "10"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Constitution": !!int "6"
"skillsaves":
  "Medicine": !!int "6"
  "Religion": !!int "5"
"condition_immunities": "[frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "passive Perception 13"
"languages": "Common, Draconic, and any two languages"
"cr": "5"
"traits":
- "desc": "The blessed casts one of the following spells, using Wisdom as the spellcasting\
    \ ability (spell save DC 14):\n\nAt will: [light](/2-Mechanics/CLI/spells/light.md),\
    \ [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\n1/day each: [enhance\
    \ ability](/2-Mechanics/CLI/spells/enhance-ability.md), [flame strike](/2-Mechanics/CLI/spells/flame-strike.md),\
    \ [mass cure wounds](/2-Mechanics/CLI/spells/mass-cure-wounds.md), [revivify](/2-Mechanics/CLI/spells/revivify.md),\
    \ [tongues](/2-Mechanics/CLI/spells/tongues.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The blessed makes two Mace or Radiant Bolt attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) bludgeoning damage plus 18 (4d8) radiant damage."
  "name": "Mace"
- "desc": "Ranged Spell Attack: +6 to hit, range 120 ft., one target. Hit: 22\
    \ (5d8) radiant damage, and the blessed regains 5 (1d10) hit points."
  "name": "Radiant Bolt"
"source":
- "FTD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/FTD/Dragon%20Blessed.webp"
```
^statblock

```encounter-table
name: Dragon Blessed
creatures:
 - 1: Dragon Blessed
```