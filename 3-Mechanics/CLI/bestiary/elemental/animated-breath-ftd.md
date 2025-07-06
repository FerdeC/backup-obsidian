---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/ftd
- monster/cr/6
- monster/size/large
- monster/type/elemental
aliases: ["Animated Breath"]
NoteIcon: monster
BestiaryType: elemental
SourceType: Bestiary
BookSource: Fizban's Treasury of Dragons p. 163
---
# [Animated Breath](2-Mechanics\CLI\bestiary\elemental/animated-breath-ftd.md)
*Source: Fizban's Treasury of Dragons p. 163*  

A chromatic dragon's breath weapon is a manifestation of the energy that suffuses the dragon. With sufficient practice, dragons can learn to draw on magic from the Elemental Planes to shape their breath weapons into bipedal form, creating Elemental creatures called animated breaths. Chromatic dragons often use these creatures as guardians for their hoards or send them out to gather treasure from the territory around their lairs.

An animated breath is a bipedal creature formed from the same energy as the breath weapon of the dragon that created it. A red dragon's creation strongly resembles a fire elemental, while a black dragon's is similar to a water elemental, but viscous and foul-looking. A green dragon's animated poison breath looks like billowing clouds of green gas, while a white dragon's animated cold breath looks like a walking ice sculpture with frigid air whirling around it. A blue dragon's animated lightning breath is a constantly shifting form of crackling lightning, and it can suddenly vanish from one place to reappear in another, striking like a bolt from the blue.

```statblock
"name": "Animated Breath (FTD)"
"size": "Large"
"type": "elemental"
"alignment": "typically  Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor; 17 cold form only"
"hp": !!int "95"
"hit_dice": "10d10 + 40"
"stats":
- !!int "19"
- !!int "11"
- !!int "18"
- !!int "6"
- !!int "10"
- !!int "5"
"speed": "30 ft., fly 30 ft. (hover)"
"damage_resistances": "damage of the type matching the animated breath's form (acid,\
  \ cold, fire, lightning, or poison)"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned), [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
  \ [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands Draconic but can't speak"
"cr": "6"
"traits":
- "desc": "When created, the animated breath takes one of five forms, matching its\
    \ creator's breath weapon: Acid, Cold, Fire, Lightning, or Poison. This form determines\
    \ the creature's AC, damage resistance, traits, and attacks."
  "name": "Chromatic Form"
- "desc": "At the start of each of the animated breath's turns, each creature within\
    \ 5 feet of it takes 3 (1d6) fire damage, and flammable objects in the aura\
    \ that aren't being worn or carried ignite. A creature that touches the animated\
    \ breath or hits it with a melee attack takes 3 (1d6) fire damage."
  "name": "Fire Aura (Fire Form Only)"
- "desc": "A creature that starts its turn within 5 feet of the animated breath must\
    \ succeed on a DC 15 Constitution saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ until the start of its next turn. A creature that touches the animated breath\
    \ or hits it with a melee attack takes 3 (1d6) acid damage."
  "name": "Putrid Aura (Acid and Poison Forms Only)"
"actions":
- "desc": "The animated breath makes two Slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) bludgeoning damage plus 11 (2d10) damage of a type determined\
    \ by the animated breath's form: acid, cold, fire, lightning, or poison."
  "name": "Slam"
"bonus_actions":
- "desc": "The animated breath magically teleports to an unoccupied space it can see\
    \ within 30 feet of it. Each creature within 5 feet of the animated breath after\
    \ it teleports takes 3 (1d6) lightning damage."
  "name": "Lightning Burst (Lightning Form Only)"
"source":
- "FTD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/FTD/Animated%20Breath.webp"
```
^statblock

```encounter-table
name: Animated Breath
creatures:
 - 1: Animated Breath
```