---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/scc
- monster/cr/5
- monster/size/large
- monster/type/monstrosity
aliases: ["Mage Hunter"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Strixhaven: A Curriculum of Chaos p. 199
---
# [Mage Hunter](2-Mechanics\CLI\bestiary\monstrosity/mage-hunter-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 199*  

Mage hunters are hideous spider-legged creatures employed by the Oriq to pursue magic-wielders. These creatures can naturally sense magic via the glowing purple spines on their backs.

A mage hunter is usually in its sentry form, a diamond-shaped drone with a heightened ability to sense and locate mages. Once it finds a quarry, the mage hunter takes on its arachnoid hunter form and pursues its targets with vicious skill.

```statblock
"name": "Mage Hunter (SCC)"
"size": "Large"
"type": "monstrosity"
"alignment": "typically  Lawful Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "10d10 + 30"
"stats":
- !!int "19"
- !!int "15"
- !!int "16"
- !!int "11"
- !!int "17"
- !!int "10"
"speed": "40 ft., climb 40 ft. (hunter form only), fly 10 ft. (hover sentry form only)"
"saves":
  "Charisma": !!int "3"
  "Wisdom": !!int "6"
  "Intelligence": !!int "3"
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "9"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [prone](/2-Mechanics/CLI/rules/conditions.md#prone)"
"senses": "blindsight 120 ft. (blind beyond this radius), passive Perception 19"
"languages": "understands Common but can't speak"
"cr": "5"
"traits":
- "desc": "The hunter knows the location of every spellcaster, active spell, and magic\
    \ item within 120 feet of itself."
  "name": "Magic Sense"
- "desc": "The hunter can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb (Hunter Form Only)"
"actions":
- "desc": "The hunter makes two Claw attacks."
  "name": "Multiattack (Hunter Form Only)"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 15\
    \ (2d10 + 4) slashing damage."
  "name": "Claw (Hunter Form Only)"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 22\
    \ (4d8 + 4) piercing damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 15). Until this grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and the hunter can't make a Tail attack against another target."
  "name": "Tail"
- "desc": "The hunter emits a pulse of energy that helps it better locate its magical\
    \ quarry. Each creature within 120 feet of the hunter that has the ability to\
    \ cast spells must succeed on a DC 14 Wisdom saving throw or be mystically marked\
    \ by the hunter for 1 hour.\n\nWhile marked, a creature can't become hidden from\
    \ the hunter and gains no benefit from the [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ condition against the hunter. Additionally, while a marked creature is on the\
    \ same plane of existence as the hunter, the hunter always knows the distance\
    \ and direction to the creature."
  "name": "Mage Tracker (Sentry Form Only)"
"bonus_actions":
- "desc": "The hunter folds into its drone-like sentry form or unfolds into its hunter\
    \ form. Its game statistics are the same in each form."
  "name": "Shift Form"
"reactions":
- "desc": "When the hunter takes damage from a spell, it takes only half the triggering\
    \ damage (rounded down). If the creature that cast the spell is within 60 feet\
    \ of the hunter, that creature must succeed on a DC 14 Dexterity saving throw\
    \ or take the other half of the damage."
  "name": "Consume and Destroy"
"source":
- "SCC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SCC/Mage%20Hunter.webp"
```
^statblock

```encounter-table
name: Mage Hunter
creatures:
 - 1: Mage Hunter
```