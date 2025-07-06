---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mot
- monster/cr/21
- monster/size/huge
- monster/type/monstrosity
aliases: ["Arasta"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Mythic Odysseys of Theros p. 248
---
# [Arasta](2-Mechanics\CLI\bestiary\npc/arasta-mot.md)
*Source: Mythic Odysseys of Theros p. 248*  

A victim of the gods' petty rivalries, Arasta was once one of Nylea's most beloved dryad companions. Phenax's bitterness saw her transformed into an arachnid monstrosity and driven into the darkest depths of the Nessian Wood. Now she broods on her unjust fate and the fickleness of the gods who left her cursed with monstrous immortality.

Arasta appears as a gigantic spiderlike creature, her few humanoid features made monstrous by cruel magic and ages of hatred. Webs fill her lair deep in the Nessian Wood, sticky strands made not of silk but of her own endless hair. In her darkened realm, Arasta broods on her hatred of the gods and their servants. She doesn't do so alone, though, as innumerable arachnids fawn over her, serving as her eyes throughout the wilderness, disposing of victims trapped within her hair, and sacrificing themselves in her defense if they must.

See "Myths of Nylea" in chapter 2 for more details on the tragedy of Arasta.

```statblock
"name": "Arasta (MOT)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "300"
"hit_dice": "24d12 + 144"
"stats":
- !!int "24"
- !!int "16"
- !!int "23"
- !!int "15"
- !!int "22"
- !!int "17"
"speed": "40 ft., climb 40 ft."
"saves":
  "Dexterity": !!int "10"
  "Wisdom": !!int "13"
  "Constitution": !!int "13"
"skillsaves":
  "Nature": !!int "9"
  "Intimidation": !!int "10"
  "Deception": !!int "10"
  "Stealth": !!int "10"
  "Perception": !!int "13"
  "Arcana": !!int "9"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "acid, poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 23"
"languages": "Celestial, Common, Sylvan"
"cr": "21"
"traits":
- "desc": "If Arasta is reduced to 0 hit points, she doesn't die or fall [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious).\
    \ Instead, she regains 200 hit points. In addition, Arasta's children immediately\
    \ swarm over her body to protect her, granting her 100 temporary hit points."
  "name": "Armor of Spiders (Mythic Trait; Recharges after a Short or Long Rest)"
- "desc": "If Arasta fails a saving throw, she can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Arasta has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Arasta can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
- "desc": "Arasta ignores movement restrictions caused by webbing."
  "name": "Web Walker"
"actions":
- "desc": "Arasta makes three attacks: one with her bite and two with her claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +14 to hit, reach 5 ft., one creature. Hit:\
    \ 20 (3d8 + 7) piercing damage, and the target must make a DC 21 Constitution\
    \ saving throw, taking 32 (5d12) poison damage on a failed save, or half as\
    \ much damage on a successful one. If the damage reduces the target to 0 hit points,\
    \ the target is stable but [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 hour, even after regaining hit points, and is [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed)\
    \ while [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) in this way."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +14 to hit, reach 5 ft., one target. Hit: 17\
    \ (3d6 + 7) slashing damage."
  "name": "Claws"
- "desc": "Arasta unleashes her hair in the form of webbing that fills a 30-foot cube\
    \ next to her. The web is difficult terrain, its area is lightly obscured, and\
    \ it lasts for 1 minute. Any creature that moves into the web or that starts its\
    \ turn there must make a DC 21 Dexterity saving throw. On a failed save, the creature\
    \ is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained) while in the\
    \ web. A creature can use an action to make a DC 21 Strength check. On a success,\
    \ it can free itself or a creature within 5 feet of it that is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ by the web. This webbing is immune to all damage except magical fire. A 5-foot\
    \ cube of the web is destroyed if it takes at least 20 fire damage from a spell\
    \ or other magical source on a single turn."
  "name": "Web of Hair (Recharge 4-6)"
"legendary_actions":
- "desc": "Arasta makes one attack with her claws."
  "name": "Claws"
- "desc": "Arasta causes two [swarms of spiders](/2-Mechanics/CLI/bestiary/beast/swarm-of-spiders.md)\
    \ to appear in unoccupied spaces within 5 feet of her."
  "name": "Swarm (Costs 2 Actions)"
- "desc": "Each creature [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ by Arasta's Web of Hair takes 18 (4d8) poison damage."
  "name": "Toxic Web (Costs 3 Actions)"
"lair_actions":
- "desc": "On initiative count 20 (losing initiative ties), Arasta can take a lair\
    \ action to cause one of the following effects. She can't use the same effect\
    \ two rounds in a row."
  "name": ""
- "desc": "- Arasta learns about any creature touching her webs. Each creature [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)\
    \ by a web or Arasta's Web of Hair must make a DC 21 Intelligence saving throw.\
    \ On a failed save, Arasta gains knowledge of a creature's name, race, where they\
    \ consider home, and what brought them to her web.  \n- Arasta casts the [giant\
    \ insect](/2-Mechanics/CLI/spells/giant-insect.md) spell (spiders only). It lasts\
    \ until she uses this lair action again or until she dies.  "
  "name": ""
"regional_effects":
- "desc": "The region containing Arasta's lair is warped by her presence, which creates\
    \ one or more of the following effects:"
  "name": ""
- "desc": "- Spiders and insects within 1 mile of Arasta's lair serve as her eyes\
    \ and ears. Birds and other flying creatures are absent from the skies and occasionally\
    \ found trapped in webs.  \n- Within 1 mile of Arasta's lair, webs fill all 10-foot\
    \ cubes of open space, so long as the webs can be anchored between two solid masses\
    \ (such as walls or trees). The webs are flammable. Any webs exposed to fire burn\
    \ away in 1 round. Any destroyed webs are magically repaired at the next dawn.\
    \  "
  "name": ""
- "desc": "If Arasta dies, the spiders and insects lose their supernatural link to\
    \ her. The webs remain, but they dissolve within 1d10 days."
  "name": ""
"mythic_encounter":
- "desc": "Arasta is a formidable enemy under normal circumstances, but to give characters\
    \ a truly mythic challenge, you can have her call on her Armor of Spiders. Her\
    \ use of this trait signals a drastic turn in the encounter, as Arasta summons\
    \ her arachnid children to protect her. While she has temporary hit points from\
    \ this trait, she can choose one of her mythic actions when she uses a legendary\
    \ action."
  "name": ""
- "desc": "Read or paraphrase the following text when Arasta uses her Armor of Spiders\
    \ trait:"
  "name": ""
- "desc": "\n> The nightmarish arachnid unleashes a shriek that sounds like a thousand\
    \ spider carapaces scarring slate. In response, the ground ripples and bursts\
    \ over the monster, revealing itself as a [wave](/2-Mechanics/CLI/items/wave.md)\
    \ of countless spiders. The tiny arachnids swarm the larger horror, girding it\
    \ in skittering bodies."
  "name": ""
- "desc": "Fighting Arasta as a mythic encounter is equivalent to taking on two challenge\
    \ rating 21 creatures in one encounter. Award a party 66,000 XP for defeating\
    \ Arasta after she uses Armor of Spiders."
  "name": ""
"source":
- "MOT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MOT/Arasta.webp"
```
^statblock

```encounter-table
name: Arasta
creatures:
 - 1: Arasta
```