---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/3
- monster/size/medium
- monster/type/undead
aliases: ["Sephek Kaltro"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 23
---
# [Sephek Kaltro](2-Mechanics\CLI\bestiary\npc/sephek-kaltro-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 23*  

Sephek Kaltro is a well-built man in his thirties. He has an olive complexion, dark hair pulled back in a ponytail, and no facial or body hair. He is dressed in a stylish vest with matching pants and boots, similar in style to those worn by mariners of the southern Sword Coast, but wears no armor or cold weather clothing and doesn't appear to be armed. His most striking feature is his eyes, which are as blue as a frozen lake.

```statblock
"name": "Sephek Kaltro (IDRotF)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"stats":
- !!int "16"
- !!int "14"
- !!int "16"
- !!int "11"
- !!int "16"
- !!int "18"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "5"
  "Survival": !!int "5"
"damage_immunities": "cold"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "passive Perception 15"
"languages": "Common"
"cr": "3"
"traits":
- "desc": "Sephek can innately cast [misty step](/2-Mechanics/CLI/spells/misty-step.md)\
    \ up to three times per day, requiring no components. His innate spellcasting\
    \ ability is Charisma.\n\nAt will: [misty step](/2-Mechanics/CLI/spells/misty-step.md)"
  "name": "Innate Spellcasting"
- "desc": "If the temperature around him is 0 degrees Fahrenheit or lower, Sephek\
    \ regains 5 hit points at the start of his turn. If he takes fire damage, this\
    \ trait doesn't function at the start of Sephek's next turn. Sephek dies only\
    \ if he starts his turn with 0 hit points and doesn't regenerate."
  "name": "Cold Regeneration"
"actions":
- "desc": "Sephek attacks twice with a weapon."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if Sephek uses the\
    \ weapon with two hands, plus 5 (2d4) cold damage."
  "name": "Ice Longsword"
- "desc": "Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one\
    \ target. Hit: 5 (1d4 + 3) piercing damage plus 5 (2d4) cold damage."
  "name": "Ice Dagger"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Sephek%20Kaltro.webp"
```
^statblock

```encounter-table
name: Sephek Kaltro
creatures:
 - 1: Sephek Kaltro
```