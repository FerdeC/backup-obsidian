---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/6
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Black Gauntlet of Bane"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 235
---
# [Black Gauntlet of Bane](2-Mechanics\CLI\bestiary\humanoid/black-gauntlet-of-bane-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 235*  

Bane's devoted followers are warriors who seek to rule through martial strength and intimidation, cruel tyrants who use threats and gifts as needed to ensure loyalty. They enslave those too weak to resist them and shower the strong with gifts and promises of power to turn them into loyal vassals.

## Cruel Tyrants

Whenever Bane's followers gain power, they institute draconian measures to ensure that their rule is unquestioned. They stamp out all opposition while richly rewarding those who swear fealty.

## Warrior Cult

Cultists of Bane are warriors who wear heavy armor and wield maces, swords, spears, and crossbows. They paint the right gauntlet of their armor black in honor of their patron. Bane's clerics wield black maces with heads shaped to look like a closed fist.

## Cult Ranks

Bane's cultists operate according to strict military hierarchies. The lowest rank consists of the fists of Bane, foot soldiers who obey all orders without hesitation. They are led by iron consuls, cunning field officers who excel at coordinating the fists in combat. The black gauntlets are the priests who command the consuls.

```statblock
"name": "Black Gauntlet of Bane (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "[chain mail](/2-Mechanics/CLI/items/chain-mail.md)"
"hp": !!int "51"
"hit_dice": "6d8 + 24"
"stats":
- !!int "18"
- !!int "11"
- !!int "18"
- !!int "12"
- !!int "15"
- !!int "18"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "5"
"skillsaves":
  "Intimidation": !!int "7"
  "Perception": !!int "5"
"condition_immunities": "[frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "passive Perception 15"
"languages": "Common"
"cr": "6"
"traits":
- "desc": "The black gauntlet is a 5th-level spellcaster. Its spellcasting ability\
    \ is Charisma (spell save DC 15, +7 to hit with spell attacks). It has the following\
    \ cleric spells prepared:\n\nCantrips (at will): [guidance](/2-Mechanics/CLI/spells/guidance.md),\
    \ [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1st level (4 slots): [bane](/2-Mechanics/CLI/spells/bane.md), [bless](/2-Mechanics/CLI/spells/bless.md),\
    \ [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md), [guiding bolt](/2-Mechanics/CLI/spells/guiding-bolt.md)\
    \ (see \"Actions\" below)\n\n2nd level (3 slots): [blindness/deafness](/2-Mechanics/CLI/spells/blindness-deafness.md),\
    \ [hold person](/2-Mechanics/CLI/spells/hold-person.md), [silence](/2-Mechanics/CLI/spells/silence.md)\n\
    \n3rd level (2 slots): [sending](/2-Mechanics/CLI/spells/sending.md), [spirit\
    \ guardians](/2-Mechanics/CLI/spells/spirit-guardians.md)"
  "name": "Spellcasting"
- "desc": "When a hostile creature within 5 feet of the black gauntlet makes an attack\
    \ roll or a saving throw, it has disadvantage on the roll. Creatures that are\
    \ immune to the [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ condition are immune to this trait."
  "name": "Aura of Terror"
- "desc": "The black gauntlet has advantage on all ability checks and saving throws\
    \ made during combat."
  "name": "Tactical Discipline"
"actions":
- "desc": "The black gauntlet makes two attacks with its mace."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) bludgeoning damage plus 13 (3d8) necrotic damage."
  "name": "Mace"
- "desc": "Ranged Spell Attack: +7 to hit, range 120 ft., one creature. Hit:\
    \ 14 (4d6) radiant damage, and the next attack roll made against the target\
    \ before the end of the black gauntlet's next turn has advantage. If the black\
    \ gauntlet casts this spell using a spell slot of 2nd level or higher, the damage\
    \ increases by 1d6 for each slot level above 1st."
  "name": "Guiding Bolt (1st-Level Spell; Requires a Spell Slot)"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Black%20Gauntlet%20of%20Bane.webp"
```
^statblock

```encounter-table
name: Black Gauntlet of Bane
creatures:
 - 1: Black Gauntlet of Bane
```