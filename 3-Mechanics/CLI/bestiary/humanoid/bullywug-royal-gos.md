---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/bullywug
aliases: ["Bullywug Royal"]
NoteIcon: monster
BestiaryType: humanoid (bullywug)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 232, The Wild Beyond the Witchlight
---
# [Bullywug Royal](2-Mechanics\CLI\bestiary\humanoid/bullywug-royal-gos.md)
*Source: Ghosts of Saltmarsh p. 232, The Wild Beyond the Witchlight*  

The largest and most intelligent bullywugs invariably end up leading their kind. These sneering specimens dress in robes made from leather, rough cloth, and bits of marsh plants. As seen in Danger at Dunwater, a bullywug royal is often accompanied by and mounted astride a giant toad.

```statblock
"name": "Bullywug Royal (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "bullywug"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "16"
- !!int "12"
- !!int "14"
- !!int "10"
- !!int "11"
- !!int "14"
"speed": "20 ft., swim 40 ft."
"saves":
  "Dexterity": !!int "3"
  "Strength": !!int "5"
"skillsaves":
  "Intimidation": !!int "4"
  "Athletics": !!int "5"
  "Stealth": !!int "3"
"senses": "passive Perception 10"
"languages": "Bullywug"
"cr": "3"
"traits":
- "desc": "The royal can breathe air and water."
  "name": "Amphibious"
- "desc": "A melee weapon deals one extra die of its damage when the royal hits with\
    \ it (included in the attack)."
  "name": "Brute"
- "desc": "The royal has advantage on melee attacks made while riding a frog mount."
  "name": "Frog Rider"
- "desc": "The royal can communicate simple concepts to frogs and toads when it speaks\
    \ in Bullywug."
  "name": "Speak with Frogs and Toads"
- "desc": "The royal's long jump is up to 20 feet and its high jump is up to 10 feet,\
    \ with or without a running start."
  "name": "Standing Leap"
- "desc": "The royal has advantage on Dexterity ([Stealth](/2-Mechanics/CLI/rules/skills.md#Stealth))\
    \ checks made to hide in swampy terrain."
  "name": "Swamp Camouflage"
"actions":
- "desc": "The royal makes two attacks: one with its royal spear and one with its\
    \ bite."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 10 ft. or range 20/60\
    \ ft., one target. Hit: 10 (2d6 + 3) piercing damage, or 12 (2d8 + 3) piercing\
    \ damage if used with two hands to make a melee attack. If the target is a Medium\
    \ or smaller creature, it must succeed on a DC 13 Strength saving throw or be\
    \ knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Royal Spear"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Bite"
- "desc": "The royal makes a loud pronouncement. Each bullywug within 60 feet of the\
    \ royal that can hear the pronouncement has advantage on its next attack roll."
  "name": "Croaked Decree (1/Day)"
"source":
- "GoS"
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Bullywug%20Royal.webp"
```
^statblock

```encounter-table
name: Bullywug Royal
creatures:
 - 1: Bullywug Royal
```