---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/jttrc
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/merfolk
aliases: ["Nightsea chil-liren"]
NoteIcon: monster
BestiaryType: humanoid (merfolk)
SourceType: Bestiary
BookSource: Journeys through the Radiant Citadel p. 177
---
# [Nightsea chil-liren](2-Mechanics\CLI\bestiary\humanoid/nightsea-chil-liren-jttrc.md)
*Source: Journeys through the Radiant Citadel p. 177*  

Janya is populated by descendants of Djaynai who escaped into the sea during the Passage of Vultures. The magic of Djaynaian transmuters and that of the Nightsea itself gave these people the ability to live beneath the waves. Now known as Nightsea chil-liren, the people of Janya look similar to the humans of Djaynai, but their brown skin is often tinged shades of gray, and eel-like fins run along their arms and legs.

```statblock
"name": "Nightsea chil-liren (JttRC)"
"size": "Medium"
"type": "humanoid"
"subtype": "merfolk"
"alignment": "Neutral"
"ac": !!int "11"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "10"
- !!int "13"
- !!int "12"
- !!int "11"
- !!int "11"
- !!int "12"
"speed": "10 ft., swim 40 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Aquan, Common"
"cr": "1/8"
"traits":
- "desc": "Nightsea chil-liren can breathe only underwater."
  "name": "Water Breathing"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +2 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 3 (1d6) piercing damage, or 4 (1d8) piercing damage\
    \ if used with two hands to make a melee attack."
  "name": "Spear"
"source":
- "JttRC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/JttRC/Nightsea%20chil-liren.webp"
```
^statblock

```encounter-table
name: Nightsea chil-liren
creatures:
 - 1: Nightsea chil-liren
```