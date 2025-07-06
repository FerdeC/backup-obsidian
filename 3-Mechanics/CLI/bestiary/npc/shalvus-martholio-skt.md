---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/
- monster/size/medium
- monster/type/humanoid/turami-human
aliases: ["Shalvus Martholio"]
NoteIcon: monster
BestiaryType: humanoid (Turami human)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 250
---
# [Shalvus Martholio](2-Mechanics\CLI\bestiary\npc/shalvus-martholio-skt.md)
*Source: Storm King's Thunder p. 250*  

Nalaskur Thaelond of Bargewright Inn has entrusted the shepherd Shalvus with an important assignment: to figure out the best way by which Goldenfields can be brought under the Black Network's control. Shalvus believes that success will ensure his swift rise through the Zhentarim ranks.

Ideal:"I'll do what it takes to prove myself to the Zhentarim."

Bond:"I love animals, and I'm very protective of them."

Flaw:"I can't resist taking risks to feed my ambitions."

```statblock
"name": "Shalvus Martholio (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Turami human"
"alignment": "Neutral"
"ac": !!int "13"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "27"
"hit_dice": "6d8"
"stats":
- !!int "10"
- !!int "15"
- !!int "10"
- !!int "12"
- !!int "14"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Sleight of Hand": !!int "4"
  "Deception": !!int "4"
  "Stealth": !!int "4"
  "Investigation": !!int "3"
  "Insight": !!int "4"
  "Perception": !!int "4"
"senses": "passive Perception 12"
"languages": "Common, Elvish"
"traits":
- "desc": "Shalvus deals an extra 7 (2d6) damage when he hits a target with a weapon\
    \ attack and has advantage on the attack roll, or when the target is within 5\
    \ feet of an ally of Shalvus that isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ and Shalvus doesn't have disadvantage on the attack roll."
  "name": "Sneak Attack (1/Turn)"
- "desc": "Nalaskur Thaelond of Bargewright Inn has entrusted the shepherd Shalvus\
    \ with an important assignment: to figure out the best way by which Goldenfields\
    \ can be brought under the Black Network's control. Shalvus believes that success\
    \ will ensure his swift rise through the Zhentarim ranks.\n\nIdeal: \"I'll do\
    \ what it takes to prove myself to the Zhentarim.\"\n\nBond: \"I love animals,\
    \ and I'm very protective of them.\"\n\nFlaw: \"I can't resist taking risks to\
    \ feed my ambitions.\""
  "name": "Roleplaying Information"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 3 (1d6)\
    \ bludgeoning damage, or 4 (1d8) bludgeoning damage if used with both hands."
  "name": "Quarterstaff"
- "desc": "Ranged Weapon Attack: +2 to hit, range 30/120 ft., one target. Hit:\
    \ 5 (1d6 + 2) piercing damage. Shalvus carries ten crossbow bolts."
  "name": "Hand Crossbow"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Shalvus%20Martholio.webp"
```
^statblock

```encounter-table
name: Shalvus Martholio
creatures:
 - 1: Shalvus Martholio
```