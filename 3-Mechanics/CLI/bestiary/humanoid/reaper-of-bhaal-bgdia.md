---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Reaper of Bhaal"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 233
---
# [Reaper of Bhaal](2-Mechanics\CLI\bestiary\humanoid/reaper-of-bhaal-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 233*  

Bhaal's cultists emulate their deity, carrying out gruesome murders to spread fear and horror. They are charming and disarming when they wish, but in combat their true, bloodthirsty nature comes to the fore.

## Bloodletters

All cultists of Bhaal learn to call upon their god's power to leave their victims vulnerable to their long-bladed knives. When Bhaal's magic works its power, stab wounds erupt in terrible gouts of blood. Seemingly minor wounds plunge deep into a victim's body and cause terrible pain and bleeding.

## Killers from the Shadows

Bhaal's followers are cunning murderers who kill to strike fear and thrive on sowing terror in the cities they inhabit. They can call upon their god's power to blend into the shadows with ease, or even turn [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible) for a crucial moment.

## Cult Ranks

Low-ranking cultists of Bhaal are called night blades, whom Bhaal blesses with [darkvision](/2-Mechanics/CLI/rules/senses.md#darkvision) and superior stealth. Reapers are the next rank up. They gain the ability to turn [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible) and can use Bhaal's magic to evade suspicion. The highest rank are the death's heads, who can take on the skull-faced guise of their deity to terrify their prey. In combat, they intimidate foes by shrugging off the deadliest attacks with ease, showing that resisting Bhaal's schemes is futile.

```statblock
"name": "Reaper of Bhaal (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "11"
- !!int "20"
- !!int "13"
- !!int "15"
- !!int "12"
- !!int "16"
"speed": "40 ft."
"skillsaves":
  "Intimidation": !!int "5"
  "Stealth": !!int "9"
  "Perception": !!int "3"
  "Persuasion": !!int "5"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common"
"cr": "2"
"traits":
- "desc": "The reaper's innate spellcasting ability is Charisma (spell save DC 13).\
    \ It can innately cast the following spells, requiring no material components:\n\
    \n1/day each: [charm person](/2-Mechanics/CLI/spells/charm-person.md), [disguise\
    \ self](/2-Mechanics/CLI/spells/disguise-self.md), [sanctuary](/2-Mechanics/CLI/spells/sanctuary.md)"
  "name": "Innate Spellcasting"
- "desc": "As long as the reaper is not [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated),\
    \ hostile creatures within 5 feet of it gain vulnerability to piercing damage\
    \ unless they have resistance or immunity to such damage."
  "name": "Aura of Murder"
"actions":
- "desc": "The reaper makes two dagger attacks and uses Shroud Self."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 7 (1d4 + 5) piercing damage."
  "name": "Dagger"
- "desc": "The reaper magically turns [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ until the start of its next turn. This invisibility ends if the reaper makes\
    \ an attack roll, makes a damage roll, or casts a spell."
  "name": "Shroud Self"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Reaper%20of%20Bhaal.webp"
```
^statblock

```encounter-table
name: Reaper of Bhaal
creatures:
 - 1: Reaper of Bhaal
```