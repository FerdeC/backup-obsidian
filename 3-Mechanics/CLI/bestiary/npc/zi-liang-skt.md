---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/
- monster/size/medium
- monster/type/humanoid/shou-human
aliases: ["Zi Liang"]
NoteIcon: monster
BestiaryType: humanoid (Shou human)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 251
---
# [Zi Liang](2-Mechanics\CLI\bestiary\npc/zi-liang-skt.md)
*Source: Storm King's Thunder p. 251*  

Zi Liang is a devout worshiper of Chauntea, the Earth Mother. She has considerably less faith in Goldenfields' defenders, so she patrols the temple-farm during her off-duty hours.

Ideal:"If we faithfully tend to our gardens and our fields, Chauntea will smile upon us."

Bond:"Goldenfields is the breadbasket of the North. People depend on its safety and prosperity, and I'll do what must be done to protect it."

Flaw:"I don't trust authority. I do what my heart says is right."

```statblock
"name": "Zi Liang (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Shou human"
"alignment": "Chaotic Good"
"ac": !!int "15"
"hp": !!int "22"
"hit_dice": "5d8"
"stats":
- !!int "12"
- !!int "15"
- !!int "11"
- !!int "14"
- !!int "16"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "3"
  "Stealth": !!int "4"
  "Perception": !!int "5"
  "Acrobatics": !!int "4"
"senses": "passive Perception 15"
"languages": "Common, Elvish, Goblin"
"traits":
- "desc": "While Zi is wearing no armor and wielding no shield, her AC includes her\
    \ Wisdom modifier."
  "name": "Unarmored Defense"
- "desc": "Zi Liang is a devout worshiper of Chauntea, the Earth Mother. She has considerably\
    \ less faith in Goldenfields' defenders, so she patrols the temple-farm during\
    \ her off-duty hours.\n\nIdeal: \"If we faithfully tend to our gardens and our\
    \ fields, Chauntea will smile upon us.\"\n\nBond: \"Goldenfields is the breadbasket\
    \ of the North. People depend on its safety and prosperity, and I'll do what must\
    \ be done to protect it.\"\n\nFlaw: \"I don't trust authority. I do what my heart\
    \ says is right.\""
  "name": "Roleplaying Information"
"actions":
- "desc": "Zi makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) bludgeoning damage, or 5 (1d8 + 1) bludgeoning damage if used with both\
    \ hands."
  "name": "Quarterstaff"
- "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit:\
    \ 4 (1d4 + 2) bludgeoning damage. Zi carries twenty sling stones."
  "name": "Sling"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Zi%20Liang.webp"
```
^statblock

```encounter-table
name: Zi Liang
creatures:
 - 1: Zi Liang
```