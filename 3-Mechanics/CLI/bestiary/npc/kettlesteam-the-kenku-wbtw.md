---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wbtw
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/kenku
- monster/type/humanoid/warlock
aliases: ["Kettlesteam the Kenku"]
NoteIcon: monster
BestiaryType: humanoid (kenku, warlock)
SourceType: Bestiary
BookSource: The Wild Beyond the Witchlight p. 52
---
# [Kettlesteam the Kenku](2-Mechanics\CLI\bestiary\npc/kettlesteam-the-kenku-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 52*  

Kettlesteam the kenku snoops around the carnival under the cover of a [disguise self](/2-Mechanics/CLI/spells/disguise-self.md) spell, looking to cause trouble. The kenku has stolen the voice of a human mime named Candlefoot (see "Hall of Illusions "earlier in the chapter). While this prize remains in her possession, Kettlesteam can speak clearly in Candlefoot's soft, silky voice.

```statblock
"name": "Kettlesteam the Kenku (WBtW)"
"size": "Medium"
"type": "humanoid"
"subtype": "kenku, warlock"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"hp": !!int "22"
"hit_dice": "5d8"
"stats":
- !!int "10"
- !!int "16"
- !!int "10"
- !!int "11"
- !!int "10"
- !!int "16"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Wisdom": !!int "2"
"skillsaves":
  "Deception": !!int "5"
  "Stealth": !!int "5"
  "Investigation": !!int "2"
  "Perception": !!int "2"
  "Arcana": !!int "2"
  "Persuasion": !!int "5"
"senses": "passive Perception 12"
"languages": "understands Auran and Common but speaks only through the use of her\
  \ Mimicry trait"
"cr": "1"
"traits":
- "desc": "Kettlesteam casts one of the following spells, using Charisma as the spellcasting\
    \ ability (spell save DC 13):\n\nAt will: [disguise self](/2-Mechanics/CLI/spells/disguise-self.md),\
    \ [friends](/2-Mechanics/CLI/spells/friends.md), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md)\n\n1/day each:\
    \ [bestow curse](/2-Mechanics/CLI/spells/bestow-curse.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md),\
    \ [speak with animals](/2-Mechanics/CLI/spells/speak-with-animals.md)"
  "name": "Spellcasting"
- "desc": "Kettlesteam can mimic any sounds she has heard, including voices. A creature\
    \ that hears the sounds can tell they are imitations only with a successful DC\
    \ 13 Wisdom ([Insight](/2-Mechanics/CLI/rules/skills.md#Insight)) check."
  "name": "Mimicry"
"actions":
- "desc": "Kettlesteam makes two Dagger attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage."
  "name": "Dagger"
- "desc": "Kettlesteam targets one creature she can see within 10 feet of her. The\
    \ target is engulfed in a cloud of magical, sleep-inducing gas and must succeed\
    \ on a DC 13 Constitution saving throw or fall [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)\
    \ for 1 minute. A creature put to sleep by this gas awakens instantly if it takes\
    \ damage, or if someone uses an action to shake or slap the sleeper awake."
  "name": "Twilight Sleep (2/Day)"
"source":
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WBtW/Kettlesteam%20the%20Kenku.webp"
```
^statblock

```encounter-table
name: Kettlesteam the Kenku
creatures:
 - 1: Kettlesteam the Kenku
```