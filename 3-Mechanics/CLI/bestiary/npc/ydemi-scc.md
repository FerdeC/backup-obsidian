---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/scc
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/human
- monster/type/humanoid/warlock
aliases: ["Y'demi"]
NoteIcon: monster
BestiaryType: humanoid (human, warlock)
SourceType: Bestiary
BookSource: Strixhaven: A Curriculum of Chaos p. 172
---
# [Y'demi](2-Mechanics\CLI\bestiary\npc/ydemi-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 172*  

The Oriq are a secret society of mages who wield forbidden magic in the service of their leader, Extus Narr. Narr was in consideration for elevation to the role of Oracle of Strixhaven, but when the Founder Dragons passed him over in favor of Jadzi, his bitterness knew no bounds. He now uses the Oriq to gather the spells and magical energy he needs to summon a devastating being, the Blood Avatar, to destroy Strixhaven.

The Oriq work in secret, infiltrating Strixhaven to search for the magic their master covets and watch for impressionable students and embittered faculty they might turn to their cause. The Oriq take pains to hide their true allegiance and wear masks to hide their identities. These masks have magical properties that function only for their intended wearers.

## Oriq Blood Mage

Oriq blood mages create deadly weapons formed of their own blood. They can also sense the life energy within nearby creatures, making the blood mages almost impossible to ambush.

```statblock
"name": "Y'demi (SCC)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, warlock"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "blood aegis"
"hp": !!int "127"
"hit_dice": "15d8 + 60"
"stats":
- !!int "11"
- !!int "14"
- !!int "18"
- !!int "20"
- !!int "12"
- !!int "12"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Wisdom": !!int "5"
  "Intelligence": !!int "9"
  "Constitution": !!int "8"
"skillsaves":
  "Medicine": !!int "5"
  "Deception": !!int "9"
  "Survival": !!int "5"
"damage_resistances": "necrotic"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion)"
"senses": "passive Perception 11"
"languages": "Common plus any four languages"
"cr": "9"
"traits":
- "desc": "The AC of Y'demi includes her Constitution modifier while she isn't wearing\
    \ armor or wielding a shield."
  "name": "Blood Aegis"
- "desc": "Y'demi wears an Oriq mask. While wearing the mask, Y'demi can't be targeted\
    \ by any divination magic or perceived through magical scrying sensors, and she\
    \ adds double her proficiency bonus to Charisma ([Deception](/2-Mechanics/CLI/rules/skills.md#Deception))\
    \ checks (included above)."
  "name": "Oriq Mask"
- "desc": "While Y'demi isn't [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
    \ she can see any creature that isn't an Undead or a Construct within 60 feet\
    \ of itself, even through total cover, heavily obscured areas, invisibility, or\
    \ any other phenomena that would prevent sight."
  "name": "Sanguine Sense"
"actions":
- "desc": "Y'demi makes two Blood Lash attacks."
  "name": "Multiattack"
- "desc": "Melee Spell Attack: +9 to hit, reach 10 ft., one target. Hit: 21\
    \ (3d10 + 5) necrotic damage. If the target is a creature, it can't regain hit\
    \ points until the start of the Y'demi's next turn."
  "name": "Blood Lash"
- "desc": "Y'demi chooses a point within 150 feet of itself, and a 20-foot radius\
    \ sphere centered on that point fills with a burst of searing, blood-red mist.\
    \ Each creature of Y'demi's choice that she can see in that area must make a DC\
    \ 17 Constitution saving throw. On a failed save, a creature takes 38 (7d10)\
    \ necrotic damage and is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ until the end of its next turn. On a success, a creature takes half as much\
    \ damage and isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated).\
    \ A creature dies if reduced to 0 hit points by this necrotic damage."
  "name": "Blood Boil (Recharge 4-6)"
"bonus_actions":
- "desc": "The blood in the copper basin disappears as tentacles of congealed blood\
    \ fill a 10-foot cube centered at a point on the ground that Y'demi can see within\
    \ 15 feet of her. The effect lasts for 1 minute, during which time that area is\
    \ difficult terrain. Any creature entering that area for the first time on a turn\
    \ or starting its turn there must succeed on a DC 13 Dexterity saving throw or\
    \ be [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained) by the tentacles.\
    \ A creature that starts its turn [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ by the tentacles takes 10 (3d6) bludgeoning damage. A creature [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ by the tentacles can use its action to make either a DC 13 Strength ([Athletics](/2-Mechanics/CLI/rules/skills.md#Athletics))\
    \ check or a DC 13 Dexterity ([Acrobatics](/2-Mechanics/CLI/rules/skills.md#Acrobatics))\
    \ check, ending the [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ condition on itself on a success."
  "name": "Sanguine Tentacles (1/Day)"
"source":
- "SCC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SCC/Y%27demi.webp"
```
^statblock

```encounter-table
name: Y'demi
creatures:
 - 1: Y'demi
```