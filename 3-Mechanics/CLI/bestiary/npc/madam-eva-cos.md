---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cos
- monster/cr/10
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Madam Eva"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Curse of Strahd p. 233
---
# [Madam Eva](2-Mechanics\CLI\bestiary\npc/madam-eva-cos.md)
*Source: Curse of Strahd p. 233*  

The fortune-teller Madam Eva lives among the Vistani but isn't truly one of them. She appears to be in her seventies, but she is, in fact, much older.

## Royal Blood

Madam Eva is Strahd's half-sister, though Strahd is unaware of this fact. Her real name is Katarina, and she is the daughter of a Vistani woman whom King Barov, Strahd's father, took to his bed during one of his many crusades. Madam Eva knows she is Strahd's half-sister but has told no one of the royal blood flowing through her veins.

## Mother Night

Over four hundred years ago, Katarina came to Barovia and insinuated herself into Strahd's court, working as a maid in Castle Ravenloft. She came to know the castle like the back of her hand, and she was present for the wedding of Sergei and Tatyana. After Strahd went mad and murdered his brother, she fled the castle and took refuge with the Vistani. Later, she forged a pact with the goddess Mother Night, trading her youth for the power to undo the evil that Strahd had wrought. Mother Night transformed Katarina into an ageless crone gifted with the power of magical foresight. In the guise of Madam Eva, she uses this ability to help Strahd. She can send her Vistani out in their wagons to visit other worlds and bring adventurers to Strahd's domain, in hopes that they will find a way to destroy the vampire or set Strahd free.

## For the Love of Strahd

The Dark Powers of Ravenloft would consider Madam Eva a worthy choice to replace Strahd as the master of Ravenloft, but she has all the power she desires and doesn't seek to supplant him. She would rather help Strahd find someone else to succeed him, although she has grave doubts about her ability to locate such an individual.

None of Madam Eva's Vistani kin know her true identity or purpose. They puzzle over her desire to remain in Barovia.

## Madam Eva's Traits

### Ideal

"I wish Strahd to be free of his curse."

### Bond

"The Vistani are my people now."

### Flaw

"The people whose fates I divine aren't important. They are but the means to an end."

```statblock
"name": "Madam Eva (CoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Neutral"
"ac": !!int "10"
"hp": !!int "88"
"hit_dice": "16d8 + 16"
"stats":
- !!int "8"
- !!int "11"
- !!int "12"
- !!int "17"
- !!int "20"
- !!int "18"
"speed": "20 ft."
"saves":
  "Constitution": !!int "5"
"skillsaves":
  "Intimidation": !!int "8"
  "Deception": !!int "8"
  "Religion": !!int "7"
  "Insight": !!int "13"
  "Perception": !!int "9"
  "Arcana": !!int "7"
"senses": "passive Perception 19"
"languages": "Abyssal, Common, Elvish, Infernal"
"cr": "10"
"traits":
- "desc": "Madam Eva is a 16th-level spellcaster. Her spellcasting ability is Wisdom\
    \ (spell save DC 17, +9 to hit with spell attacks). Madam Eva has the following\
    \ cleric spells prepared:\n\nCantrips (at will): [light](/2-Mechanics/CLI/spells/light.md),\
    \ [mending](/2-Mechanics/CLI/spells/mending.md), [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md),\
    \ [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\n1st level (4 slots):\
    \ [bane](/2-Mechanics/CLI/spells/bane.md), [command](/2-Mechanics/CLI/spells/command.md),\
    \ [detect evil and good](/2-Mechanics/CLI/spells/detect-evil-and-good.md), [protection\
    \ from evil and good](/2-Mechanics/CLI/spells/protection-from-evil-and-good.md)\n\
    \n2nd level (3 slots): [lesser restoration](/2-Mechanics/CLI/spells/lesser-restoration.md),\
    \ [protection from poison](/2-Mechanics/CLI/spells/protection-from-poison.md),\
    \ [spiritual weapon](/2-Mechanics/CLI/spells/spiritual-weapon.md)\n\n3rd level\
    \ (3 slots): [create food and water](/2-Mechanics/CLI/spells/create-food-and-water.md),\
    \ [speak with dead](/2-Mechanics/CLI/spells/speak-with-dead.md), [spirit guardians](/2-Mechanics/CLI/spells/spirit-guardians.md)\n\
    \n4th level (3 slots): [divination](/2-Mechanics/CLI/spells/divination.md),\
    \ [freedom of movement](/2-Mechanics/CLI/spells/freedom-of-movement.md), [guardian\
    \ of faith](/2-Mechanics/CLI/spells/guardian-of-faith.md)\n\n5th level (2 slots):\
    \ [greater restoration](/2-Mechanics/CLI/spells/greater-restoration.md), [raise\
    \ dead](/2-Mechanics/CLI/spells/raise-dead.md)\n\n6th level (1 slots): [find\
    \ the path](/2-Mechanics/CLI/spells/find-the-path.md), [harm](/2-Mechanics/CLI/spells/harm.md),\
    \ [true seeing](/2-Mechanics/CLI/spells/true-seeing.md)\n\n7th level (1 slots):\
    \ [fire storm](/2-Mechanics/CLI/spells/fire-storm.md), [regenerate](/2-Mechanics/CLI/spells/regenerate.md)\n\
    \n8th level (1 slots): [earthquake](/2-Mechanics/CLI/spells/earthquake.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 2 (1d4)\
    \ piercing damage."
  "name": "Dagger"
- "desc": "Madam Eva targets one creature that she can see within 30 feet of her.\
    \ The target must succeed on a DC 17 Wisdom saving throw or be cursed. While cursed,\
    \ the target is [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded) and [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened).\
    \ The curse lasts until ended with a [greater restoration](/2-Mechanics/CLI/spells/greater-restoration.md)\
    \ spell, a [remove curse](/2-Mechanics/CLI/spells/remove-curse.md) spell, or similar\
    \ magic. When the curse ends, Madam Eva takes 5d6 psychic damage."
  "name": "Curse (Recharges after a Long Rest)"
- "desc": "Madam Eva targets one creature that she can see within 10 feet of her and\
    \ casts one of the following spells on the target (save DC 17), requiring neither\
    \ somatic nor material components to do so: [animal friendship](/2-Mechanics/CLI/spells/animal-friendship.md),\
    \ [charm person](/2-Mechanics/CLI/spells/charm-person.md), or [hold person](/2-Mechanics/CLI/spells/hold-person.md).\
    \ If the target succeeds on the initial saving throw, Madam Eva is [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded)\
    \ until the end of her next turn. Once a target succeeds on a saving throw against\
    \ this effect, it is immune to the Evil Eye power of all Vistani for 24 hours."
  "name": "Evil Eye (Recharges after a Short or Long Rest)"
"source":
- "CoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CoS/Madam%20Eva.webp"
```
^statblock

```encounter-table
name: Madam Eva
creatures:
 - 1: Madam Eva
```