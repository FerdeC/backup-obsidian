---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/6
- monster/size/medium
- monster/type/humanoid/earth-genasi
aliases: ["Miraj Vizann"]
NoteIcon: monster
BestiaryType: humanoid (Earth genasi)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 198
---
# [Miraj Vizann](2-Mechanics\CLI\bestiary\npc/miraj-vizann-pota.md)
*Source: Princes of the Apocalypse p. 198*  

Miraj is an earth genasi from Calimshan. He is a perfectionist who oversees the Black Earth cult's tunneling operations and specializes in magic and alchemical processes that shape stone. He also has an affinity for the element of water and styles himself a 'mud sorcerer.'

Though he is the most accomplished spellcaster in the Cult of the Black Earth, he has no interest in challenging Marlos Urnrayle for leadership. He knows that he is no match for the medusa and is happy to pursue his experiments while Marlos leads.

```statblock
"name": "Miraj Vizann (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "Earth genasi"
"alignment": "Neutral Evil"
"ac": !!int "10"
"ac_class": "13 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"stats":
- !!int "12"
- !!int "10"
- !!int "17"
- !!int "13"
- !!int "11"
- !!int "18"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "7"
  "Arcana": !!int "4"
"senses": "passive Perception 10"
"languages": "Common, Primordial"
"cr": "6"
"traits":
- "desc": "Miraj's innate spellcasting ability is Constitution (spell save DC 14).\
    \ He can innately cast the following spell, requiring no material components:\n\
    \n1/day: [pass without trace](/2-Mechanics/CLI/spells/pass-without-trace.md)"
  "name": "Innate Spellcasting"
- "desc": "Miraj is an 11th-level spellcaster. His spellcasting ability is Charisma\
    \ (spell save DC 15, +7 to hit with spell attacks). He knows the following sorcerer\
    \ spells:\n\nCantrips (at will): [acid splash](/2-Mechanics/CLI/spells/acid-splash.md),\
    \ [blade ward](/2-Mechanics/CLI/spells/blade-ward.md), [friends](/2-Mechanics/CLI/spells/friends.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md), [message](/2-Mechanics/CLI/spells/message.md),\
    \ [mold earth](/2-Mechanics/CLI/spells/mold-earth-xge.md)\n\n1st level (4 slots):\
    \ [chromatic orb](/2-Mechanics/CLI/spells/chromatic-orb.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md),\
    \ [magic missile](/2-Mechanics/CLI/spells/magic-missile.md)\n\n2nd level (3\
    \ slots): [Maximilian's earthen grasp](/2-Mechanics/CLI/spells/maximilians-earthen-grasp-xge.md),\
    \ [shatter](/2-Mechanics/CLI/spells/shatter.md), [suggestion](/2-Mechanics/CLI/spells/suggestion.md)\n\
    \n3rd level (3 slots): [counterspell](/2-Mechanics/CLI/spells/counterspell.md),\
    \ [erupting earth](/2-Mechanics/CLI/spells/erupting-earth-xge.md)\n\n4th level\
    \ (3 slots): [polymorph](/2-Mechanics/CLI/spells/polymorph.md), [stoneskin](/2-Mechanics/CLI/spells/stoneskin.md)\n\
    \n5th level (2 slots): [wall of stone](/2-Mechanics/CLI/spells/wall-of-stone.md)\n\
    \n6th level (1 slots): [move earth](/2-Mechanics/CLI/spells/move-earth.md)"
  "name": "Spellcasting"
- "desc": "Moving through difficult terrain made of earth or stone costs Miraj no\
    \ extra movement."
  "name": "Earth Walk"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) bludgeoning damage, or 5 (1d8 + 1) bludgeoning damage when used with\
    \ two hands."
  "name": "Staff"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Miraj%20Vizann.webp"
```
^statblock

```encounter-table
name: Miraj Vizann
creatures:
 - 1: Miraj Vizann
```