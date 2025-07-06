---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/10
- monster/size/medium
- monster/type/aberration
aliases: ["Mr. Dory"]
NoteIcon: monster
BestiaryType: aberration
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 246
---
# [Mr. Dory](2-Mechanics\CLI\bestiary\npc/mr-dory-gos.md)
*Source: Ghosts of Saltmarsh p. 246*  

One of the four councillors who rule the Styes, Mr. Dory hides his cursed nature in plain sight. His rare, liquid-sensitive "skin condition" is actually a form of the same aboleth affliction that creates skum, though Dory's condition is not as severe, and he has managed to retain his free will.

```statblock
"name": "Mr. Dory (GoS)"
"size": "Medium"
"type": "aberration"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "170"
"hit_dice": "20d8 + 80"
"stats":
- !!int "13"
- !!int "20"
- !!int "19"
- !!int "14"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Constitution": !!int "8"
"skillsaves":
  "Athletics": !!int "5"
  "Stealth": !!int "9"
  "Perception": !!int "6"
"damage_immunities": "necrotic"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Abyssal, Common, Deep Speech, telepathy 60 ft."
"cr": "10"
"traits":
- "desc": "Mr. Dory's innate spellcasting ability is Charisma (save DC 15, +7 to\
    \ hit with spell attacks). Mr. Dory can innately cast the following spells, requiring\
    \ no material components:\n\nAt will: [detect magic](/2-Mechanics/CLI/spells/detect-magic.md),\
    \ [detect thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md), [invisibility](/2-Mechanics/CLI/spells/invisibility.md)\
    \ (self only)\n\n1/day each: [cloudkill](/2-Mechanics/CLI/spells/cloudkill.md),\
    \ [etherealness](/2-Mechanics/CLI/spells/etherealness.md)\n\n2/day each: [fear](/2-Mechanics/CLI/spells/fear.md),\
    \ [fireball](/2-Mechanics/CLI/spells/fireball.md), [fly](/2-Mechanics/CLI/spells/fly.md)"
  "name": "Innate Spellcasting"
- "desc": "Mr. Dory has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Mr. Dory takes 6 (1d12) acid damage at the end of every hour he goes\
    \ without exposure to water."
  "name": "Water Dependency"
"actions":
- "desc": "Mr. Dory makes three attacks with his rapier."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 9 (1d8\
    \ + 5) piercing damage and 7 (2d6) necrotic damage."
  "name": "Rapier"
- "desc": "Mr. Dory glares at a creature he can see within 30 feet of him. The target\
    \ must make a DC 15 Constitution saving throw. On a failed save, it takes 27 (5d10)\
    \ necrotic damage and 27 (5d10) poison damage and then gains vulnerability to\
    \ both necrotic and poison damage for 1 minute. On a successful save, it takes\
    \ half damage and does not gain the vulnerabilities."
  "name": "Eye of Corruption (Recharge 5-6)"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Mr.%20Dory.webp"
```
^statblock

```encounter-table
name: Mr. Dory
creatures:
 - 1: Mr. Dory
```