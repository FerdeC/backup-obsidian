---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/hotdq
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Azbara Jos"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Hoard of the Dragon Queen p. 88
---
# [Azbara Jos](2-Mechanics\CLI\bestiary\npc/azbara-jos-hotdq.md)
*Source: Hoard of the Dragon Queen p. 88*  

```statblock
"name": "Azbara Jos (HotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "13"
"ac_class": "16 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"stats":
- !!int "9"
- !!int "16"
- !!int "14"
- !!int "16"
- !!int "13"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "3"
  "Intelligence": !!int "5"
"skillsaves":
  "Deception": !!int "2"
  "Stealth": !!int "5"
  "Insight": !!int "3"
  "Arcana": !!int "5"
"senses": "passive Perception 11"
"languages": "Common, Draconic, Infernal, Primordial, Thayan"
"cr": "4"
"traits":
- "desc": "Azbara is a 6th-level spellcaster that uses Intelligence as his spellcasting\
    \ ability (spell save DC 13, +5 to hit with spell attacks). Azbara has the following\
    \ spells prepared from the wizard spell list:\n\nCantrips (at will): [mage\
    \ hand](/2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md),\
    \ [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md), [shocking grasp](/2-Mechanics/CLI/spells/shocking-grasp.md)\n\
    \n1st level (4 slots): [fog cloud](/2-Mechanics/CLI/spells/fog-cloud.md),\
    \ [magic missile](/2-Mechanics/CLI/spells/magic-missile.md), [shield](/2-Mechanics/CLI/spells/shield.md),\
    \ [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md)\n\n2nd level (3 slots):\
    \ [invisibility](/2-Mechanics/CLI/spells/invisibility.md), [misty step](/2-Mechanics/CLI/spells/misty-step.md),\
    \ [scorching ray](/2-Mechanics/CLI/spells/scorching-ray.md)\n\n3rd level (3\
    \ slots): [counterspell](/2-Mechanics/CLI/spells/counterspell.md), [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md),\
    \ [fireball](/2-Mechanics/CLI/spells/fireball.md)"
  "name": "Spellcasting"
- "desc": "Azbara has two [scrolls](/2-Mechanics/CLI/items/spell-scroll-1st-level.md)\
    \ of [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)."
  "name": "Special Equipment"
- "desc": "When Azbara casts an evocation Cantrips and misses, or the target succeeds\
    \ on its saving throw, the target still takes half the cantrip's damage but suffers\
    \ no other effect."
  "name": "Potent Cantrips"
- "desc": "When Azbara casts an evocation spell that affects other creatures that\
    \ he can see, he can choose a number of them equal to 1+the spell's level to succeed\
    \ on their saving throws against the spell. Those creatures take no damage if\
    \ they would normally take half damage from the spell."
  "name": "Sculpt Spells"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or ranged 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage."
  "name": "Dagger"
"source":
- "HotDQ"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/HotDQ/Azbara%20Jos.webp"
```
^statblock

```encounter-table
name: Azbara Jos
creatures:
 - 1: Azbara Jos
```