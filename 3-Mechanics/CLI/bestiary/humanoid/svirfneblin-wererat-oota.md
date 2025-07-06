---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
- monster/type/humanoid/shapechanger
aliases: ["Svirfneblin Wererat"]
NoteIcon: monster
BestiaryType: humanoid (human, shapechanger)
SourceType: Bestiary
BookSource: Out of the Abyss p. 97
---
# [Svirfneblin Wererat](2-Mechanics\CLI\bestiary\humanoid/svirfneblin-wererat-oota.md)
*Source: Out of the Abyss p. 97*  

```statblock
"name": "Svirfneblin Wererat (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, shapechanger"
"alignment": "Lawful Evil"
"ac": !!int "12"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "10"
- !!int "15"
- !!int "12"
- !!int "11"
- !!int "10"
- !!int "8"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "2"
"damage_immunities": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't silvered"
"senses": "darkvision 60 ft. (rat form only), darkvision 120 ft., passive Perception\
  \ 12"
"languages": "Common (can't speak in rat form), Gnomish, Terran, Undercommon"
"cr": "2"
"traits":
- "desc": "The svirfneblin wererat\n\nAt will: [nondetection](/2-Mechanics/CLI/spells/nondetection.md)\
    \ (self only)\n\n1/day each: [blindness/deafness](/2-Mechanics/CLI/spells/blindness-deafness.md),\
    \ [blur](/2-Mechanics/CLI/spells/blur.md), [disguise self](/2-Mechanics/CLI/spells/disguise-self.md)"
  "name": "Innate Spellcasting"
- "desc": "The wererat can use its action to polymorph into a rat-humanoid hybrid\
    \ or into a giant rat, or back into its true form, which is humanoid. Its statistics,\
    \ other than its size, are the same in each form. Any equipment it is wearing\
    \ or carrying isn't transformed. It reverts to its true form if it dies."
  "name": "Shapechanger"
- "desc": "The wererat has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "The svirfneblin wererat"
  "name": "Gnome Cunning"
- "desc": "The svirfneblin wererat"
  "name": "Stone Camouflage"
"actions":
- "desc": "The wererat makes two attacks, only one of which can be a bite."
  "name": "Multiattack (Humanoid or Hybrid Form Only)"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage. If the target is a humanoid, it must succeed on a DC\
    \ 11 Constitution saving throw or be cursed with wererat lycanthropy."
  "name": "Bite (Rat or Hybrid Form Only)"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword (Humanoid or Hybrid Form Only)"
- "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit:\
    \ 5 (1d6 + 2) piercing damage."
  "name": "Hand Crossbow (Humanoid or Hybrid Form Only)"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Svirfneblin%20Wererat.webp"
```
^statblock

```encounter-table
name: Svirfneblin Wererat
creatures:
 - 1: Svirfneblin Wererat
```