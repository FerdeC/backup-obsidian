---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cos
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Vistana Bandit Captain"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Curse of Strahd p. 28
---
# [Vistana Bandit Captain](2-Mechanics\CLI\bestiary\humanoid/vistana-bandit-captain-cos.md)
*Source: Curse of Strahd p. 28*  

```statblock
"name": "Vistana Bandit Captain (CoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Lawful alignment"
"ac": !!int "15"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "15"
- !!int "16"
- !!int "14"
- !!int "14"
- !!int "11"
- !!int "14"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "2"
  "Strength": !!int "4"
"skillsaves":
  "Athletics": !!int "4"
  "Deception": !!int "4"
"senses": "passive Perception 10"
"languages": "any two languages"
"cr": "2"
"actions":
- "desc": "The captain makes three melee attacks: two with its scimitar and one with\
    \ its dagger. Or the captain makes two ranged attacks with its daggers."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Scimitar"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage."
  "name": "Dagger"
- "desc": "12\n\n- The target is unable to perform a certain kind of act involving\
    \ fine motor control, such as tying knots, writing, playing an instrument, sewing,\
    \ or casting spells that have somatic components. When this curse ends, the Vistana\
    \ takes 1d6 psychic damage.  \n- The target's appearance changes in a sinister\
    \ yet purely cosmetic way. For example, the curse can place a scar on the target's\
    \ face, turn the target's teeth into yellow fangs, or give the target bad breath.\
    \ When this curse ends, the Vistana takes 1d6 psychic damage.  \n- A nonmagical\
    \ item in the target's possession (chosen by the DM) disappears and can't be found\
    \ until the curse ends. The lost item can weigh no more than 1 pound. When this\
    \ curse ends, the Vistana takes 1d6 psychic damage.  \n- The target gains vulnerability\
    \ to a damage type of the Vistana's choice. When this curse ends, the Vistana\
    \ takes 3d6 psychic damage.  \n- The target has disadvantage on ability checks\
    \ and saving throws tied to one ability score of the Vistana's choice. When this\
    \ curse ends, the Vistana takes 3d6 psychic damage.  \n- The target's attunement\
    \ to one magic item (chosen by the DM) ends, and the target can't attune to the\
    \ chosen item until the curse ends. When this curse ends, the Vistana takes 5d6\
    \ psychic damage.  \n- The target is [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
    \ [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened), or both. When this\
    \ curse ends, the Vistana takes 5d6 psychic damage.  \n\nThe curse lasts until\
    \ ended with a [greater restoration](/2-Mechanics/CLI/spells/greater-restoration.md)\
    \ spell, a [remove curse](/2-Mechanics/CLI/spells/remove-curse.md) spell, or similar\
    \ magic. It doesn't end when the target dies. If a cursed target is returned to\
    \ life, the curse remains in effect."
  "name": "Curse (Recharges After a Long Rest)"
- "desc": "12\n\nA Vistana who uses Evil Eye can't use it again before finishing a\
    \ short or long rest. Once a target succeeds on a saving throw against a Vistana's\
    \ Evil Eye, it is immune to the Evil Eye of all Vistani for 24 hours."
  "name": "Evil Eye (Recharges after a Short or Long Rest)"
"reactions":
- "desc": "The captain adds 2 to its AC against one melee attack that would hit it.\
    \ To do so, the captain must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "CoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CoS/Vistana%20Bandit%20Captain.webp"
```
^statblock

```encounter-table
name: Vistana Bandit Captain
creatures:
 - 1: Vistana Bandit Captain
```