---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Gar Shatterkeel"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 208
---
# [Gar Shatterkeel](2-Mechanics\CLI\bestiary\npc/gar-shatterkeel-pota.md)
*Source: Princes of the Apocalypse p. 208*  

Gar Shatterkeel is the water prophet of Elemental Evil and the dour leader of the Crushing Wave cult. He is embittered by a life of suffering at the hands of others. Pirates killed his family when he was young, he was forced into servitude aboard a merchant ship, and then another band of pirates left him to die at sea, where he lost his arm to a shark. Gar sees the elemental power of water as the only thing of value in his life and has gathered others who feel as he does.

Gar bears the elemental weapon Drown. His missing arm has been replaced by an artificial limb in the shape of a crab's claw. As the leader of Olhydra's cult, he wields her innate magic. Other Crushing Wave cultists sense her power in him and follow him out of fear.

## In the Water Node

When it becomes clear that the Temple of the Crushing Wave is no longer secure, Gar retreats to the Plunging Torrents, the water node. Within this node, Gar gains one additional use of his Legendary Resistance trait.

```statblock
"name": "Gar Shatterkeel (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "97"
"hit_dice": "15d8 + 45"
"stats":
- !!int "15"
- !!int "15"
- !!int "16"
- !!int "12"
- !!int "18"
- !!int "13"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Nature": !!int "9"
  "Survival": !!int "8"
"damage_resistances": "cold"
"senses": "passive Perception 14"
"languages": "Aquan, Common"
"cr": "9"
"traits":
- "desc": "Gar is a 9th-level spellcaster. His spellcasting ability is Wisdom (spell\
    \ save DC 16, +8 to hit with spell attacks). He has the following druid spells\
    \ prepared:\n\nCantrips (at will): [mending](/2-Mechanics/CLI/spells/mending.md),\
    \ [resistance](/2-Mechanics/CLI/spells/resistance.md), [shape water](/2-Mechanics/CLI/spells/shape-water-xge.md)\n\
    \n1st level (4 slots): [create or destroy water](/2-Mechanics/CLI/spells/create-or-destroy-water.md),\
    \ [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md), [fog cloud](/2-Mechanics/CLI/spells/fog-cloud.md),\
    \ [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md)\n\n2nd level (3 slots):\
    \ [darkvision](/2-Mechanics/CLI/spells/darkvision.md), [hold person](/2-Mechanics/CLI/spells/hold-person.md),\
    \ [protection from poison](/2-Mechanics/CLI/spells/protection-from-poison.md)\n\
    \n3rd level (3 slots): [call lightning](/2-Mechanics/CLI/spells/call-lightning.md),\
    \ [sleet storm](/2-Mechanics/CLI/spells/sleet-storm.md), [tidal wave](/2-Mechanics/CLI/spells/tidal-wave-xge.md)\n\
    \n4th level (3 slots): [control water](/2-Mechanics/CLI/spells/control-water.md),\
    \ [ice storm](/2-Mechanics/CLI/spells/ice-storm.md)\n\n5th level (1 slots):\
    \ [scrying](/2-Mechanics/CLI/spells/scrying.md)"
  "name": "Spellcasting"
- "desc": "Gar can breathe air and water."
  "name": "Amphibious"
- "desc": "If Gar fails a saving throw, he can choose to succeed instead."
  "name": "Legendary Resistance (2/Day)"
- "desc": "Gar can stand and move on liquid surfaces as if they were solid ground."
  "name": "Water Walk"
- "desc": "When Gar drops to 0 hit points, his body collapses into a pool of inky\
    \ water that rapidly disperses. Anything he was wearing or carrying is left behind."
  "name": "Watery Fall"
"actions":
- "desc": "Gar makes two melee attacks, one with his claw and one with [Drown](/2-Mechanics/CLI/items/drown-pota.md)."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 9 (2d6\
    \ + 2) bludgeoning damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 13). Until the grapple ends, Gar can't attack other creatures with\
    \ his claw."
  "name": "Claw"
- "desc": "Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 6 (1d6 + 3) piercing damage plus 4 (1d8) cold damage."
  "name": "Drown"
"lair_actions":
- "desc": "If Gar is in the water node while [Olhydra](/2-Mechanics/CLI/bestiary/npc/olhydra-pota.md)\
    \ isn't, he can take lair actions. On initiative count 20 (losing initiative ties),\
    \ Gar uses a lair action to use his Multiattack or cast one of his spells, up\
    \ to 3rd level, without using components or a spell slot. He can't cast the same\
    \ spell two rounds in a row, but he can continue to concentrate on a spell he\
    \ previously cast using a lair action. He can take no other lair actions while\
    \ concentrating on a spell cast as a lair action. His favorite use of this capability\
    \ is casting [inflict wounds](/2-Mechanics/CLI/spells/inflict-wounds.md) or [call\
    \ lightning](/2-Mechanics/CLI/spells/call-lightning.md)."
  "name": ""
- "desc": "If Gar casts [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md) using\
    \ this lair action, he regains the maximum number of hit points from the spell\
    \ (28)."
  "name": ""
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Gar%20Shatterkeel.webp"
```
^statblock

```encounter-table
name: Gar Shatterkeel
creatures:
 - 1: Gar Shatterkeel
```