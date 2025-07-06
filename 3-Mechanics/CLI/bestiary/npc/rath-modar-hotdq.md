---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/hotdq
- monster/cr/6
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Rath Modar"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Hoard of the Dragon Queen p. 92, The Rise of Tiamat p. 91
---
# [Rath Modar](2-Mechanics\CLI\bestiary\npc/rath-modar-hotdq.md)
*Source: Hoard of the Dragon Queen p. 92, The Rise of Tiamat p. 91*  

```statblock
"name": "Rath Modar (HotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "13"
"ac_class": "16 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "71"
"hit_dice": "11d8 + 22"
"stats":
- !!int "11"
- !!int "16"
- !!int "14"
- !!int "18"
- !!int "14"
- !!int "10"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "5"
  "Intelligence": !!int "7"
"skillsaves":
  "Deception": !!int "3"
  "Stealth": !!int "6"
  "Insight": !!int "5"
  "Arcana": !!int "7"
"senses": "passive Perception 12"
"languages": "Common, Draconic, Infernal, Primordial, Thayan"
"cr": "6"
"traits":
- "desc": "Rath is an 11th-level spellcaster who uses Intelligence as his spellcasting\
    \ ability (spell save DC 15, +7 to hit with spell attacks). Rath has the following\
    \ spells prepared from the wizard spell list:\n\nCantrips (at will): [fire\
    \ bolt](/2-Mechanics/CLI/spells/fire-bolt.md), [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md), [shocking grasp](/2-Mechanics/CLI/spells/shocking-grasp.md)\n\
    \n1st level (4 slots): [chromatic orb](/2-Mechanics/CLI/spells/chromatic-orb.md),\
    \ [color spray](/2-Mechanics/CLI/spells/color-spray.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md),\
    \ [magic missile](/2-Mechanics/CLI/spells/magic-missile.md)\n\n2nd level (3\
    \ slots): [detect thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md), [mirror\
    \ image](/2-Mechanics/CLI/spells/mirror-image.md), [phantasmal force](/2-Mechanics/CLI/spells/phantasmal-force.md)\n\
    \n3rd level (3 slots): [counterspell](/2-Mechanics/CLI/spells/counterspell.md),\
    \ [fireball](/2-Mechanics/CLI/spells/fireball.md), [major image](/2-Mechanics/CLI/spells/major-image.md)\n\
    \n4th level (3 slots): [confusion](/2-Mechanics/CLI/spells/confusion.md),\
    \ [greater invisibility](/2-Mechanics/CLI/spells/greater-invisibility.md)\n\n\
    5th level (2 slots): [mislead](/2-Mechanics/CLI/spells/mislead.md), [seeming](/2-Mechanics/CLI/spells/seeming.md)\n\
    \n6th level (1 slots): [globe of invulnerability](/2-Mechanics/CLI/spells/globe-of-invulnerability.md)"
  "name": "Spellcasting"
- "desc": "Rath has a [staff of fire](/2-Mechanics/CLI/items/staff-of-fire.md), and\
    \ scrolls of [dimension door](/2-Mechanics/CLI/spells/dimension-door.md), [feather\
    \ fall](/2-Mechanics/CLI/spells/feather-fall.md), and [fireball](/2-Mechanics/CLI/spells/fireball.md)."
  "name": "Special Equipment"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d8)\
    \ bludgeoning damage."
  "name": "Quarterstaff"
"reactions":
- "desc": "When a creature Rath can see makes an attack roll against him, he can interpose\
    \ an illusory duplicate between the attacker and him. The attack automatically\
    \ misses Rath, then the illusion dissipates."
  "name": "Illusory Self (Recharges on a Short or Long Rest)"
"source":
- "HotDQ"
- "RoT"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/HotDQ/Rath%20Modar.webp"
```
^statblock

```encounter-table
name: Rath Modar
creatures:
 - 1: Rath Modar
```