---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/2
- monster/size/small
- monster/type/humanoid/halfling
aliases: ["Wiggan Nettlebee"]
NoteIcon: monster
BestiaryType: humanoid (halfling)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 212
---
# [Wiggan Nettlebee](2-Mechanics\CLI\bestiary\npc/wiggan-nettlebee-pota.md)
*Source: Princes of the Apocalypse p. 212*  

Wiggan Nettlebee is the patriarch of the Nettlebee clan, a wealthy family of halflings that raise livestock and farm their land. He presents the outward appearance of a modest rancher, and he forbids extravagance on his farm. Thinking he had found a cult dedicated to the dominating nature and utilizing its darker aspects, Wiggan joined the Cult of the Black Earth. He still doesn't know the full extent of the cult's plans.

Wiggan dislikes and distrusts outsiders. He believes they are all evildoers who would steal from him if they could. He sees the earth cult as a powerful and necessary ally toward securing his finances and sustaining his position. A greedy miser, Wiggan becomes visibly upset at the thought of parting with even a few spare coins from his hoard.

```statblock
"name": "Wiggan Nettlebee (PotA)"
"size": "Small"
"type": "humanoid"
"subtype": "halfling"
"alignment": "Neutral Evil"
"ac": !!int "11"
"ac_class": "16 with [barkskin](/2-Mechanics/CLI/spells/barkskin.md)"
"hp": !!int "36"
"hit_dice": "8d6 + 8"
"stats":
- !!int "8"
- !!int "12"
- !!int "12"
- !!int "14"
- !!int "15"
- !!int "13"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "3"
  "Insight": !!int "4"
"senses": "passive Perception 12"
"languages": "Common, Halfling"
"cr": "2"
"traits":
- "desc": "Wiggan is a 4th-level spellcaster. His spellcasting ability is Wisdom (spell\
    \ save DC 12, +4 to hit with spell attacks). He has the following cleric spells\
    \ prepared:\n\nCantrips (at will): [guidance](/2-Mechanics/CLI/spells/guidance.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md), [mending](/2-Mechanics/CLI/spells/mending.md),\
    \ [shillelagh](/2-Mechanics/CLI/spells/shillelagh.md), [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1st level (4 slots): [animal friendship](/2-Mechanics/CLI/spells/animal-friendship.md),\
    \ [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md), [healing word](/2-Mechanics/CLI/spells/healing-word.md),\
    \ [inflict wounds](/2-Mechanics/CLI/spells/inflict-wounds.md), [speak with animals](/2-Mechanics/CLI/spells/speak-with-animals.md)\n\
    \n2nd level (3 slots): [barkskin](/2-Mechanics/CLI/spells/barkskin.md), [spike\
    \ growth](/2-Mechanics/CLI/spells/spike-growth.md), [spiritual weapon](/2-Mechanics/CLI/spells/spiritual-weapon.md)"
  "name": "Spellcasting"
- "desc": "Wiggan has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Brave Devotion"
"actions":
- "desc": "Wiggan makes two attacks with his wooden cane."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +0 to hit (+4 to hit with shillelagh), reach\
    \ 5 ft., one target. Hit: 1 (1d4 - 1) bludgeoning damage, or 6 (1d8 + 2)\
    \ bludgeoning damage with shillelagh."
  "name": "Wooden Cane"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Wiggan%20Nettlebee.webp"
```
^statblock

```encounter-table
name: Wiggan Nettlebee
creatures:
 - 1: Wiggan Nettlebee
```