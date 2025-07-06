---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/18
- monster/size/huge
- monster/type/elemental
aliases: ["Olhydra"]
NoteIcon: monster
BestiaryType: elemental
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 218
---
# [Olhydra](2-Mechanics\CLI\bestiary\npc/olhydra-pota.md)
*Source: Princes of the Apocalypse p. 218*  

Olhydra is the Princess of Evil Water. Sometimes known as the Crushing Wave, the Dark Tide, or the Well of Endless Anguish, she takes the form of a great wave, 20 feet high and 15 feet wide, with opalescent eyes. She prefers to remain in or near large bodies of water-seas, lakes, rivers, or sometimes great subterranean pools. When she needs to, she can surge onto dry land, moving much like a wave rushing up onto the shore, but only great anger or desperation would drive Olhydra to move more than a few hundred feet from her native element.

Olhydra surges forth tirelessly and relentlessly. She delights in creating dangerous and destructive manifestations of elemental water, especially maelstroms and floods. She is eager to assert her power by smashing any vessel that dares to venture into her realm, and lays waste to villages or towns established within her reach. Olhydra erodes that which she can't batter and drown; she is patient, retreating in the face of adversity only to return stronger than before.

Of all the Princes of Elemental Evil, Olhydra is the one most interested in mortals. She recognizes that pirates and raiders who redden the waters with mortal blood (and occasionally send treasure-laden ships into her clutches) are agents of her hateful outlook, whether they know it or not. Consequently, Olhydra sometimes spares the worst sort of seafarers from her wrath, patiently waiting for the day when they deliver others into her power.

## Olhydra's Lair

The Princess of Evil Water is native to the Elemental Plane of Water, where she can be found in the black depths of vast seas or enthroned among jagged reefs. Olhydra waits for the chance to enter the Material Plane through elemental water nodes or when called by the proper rituals. Whether she is in her elemental domain or temporarily occupying a water node, Olhydra commands the waters around her and can shape them to her will.

```statblock
"name": "Olhydra (PotA)"
"size": "Huge"
"type": "elemental"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "324"
"hit_dice": "24d12 + 168"
"stats":
- !!int "21"
- !!int "22"
- !!int "24"
- !!int "17"
- !!int "18"
- !!int "23"
"speed": "50 ft., swim 100 ft."
"saves":
  "Wisdom": !!int "10"
  "Strength": !!int "11"
  "Constitution": !!int "13"
"damage_resistances": "lightning; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "acid, cold, poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone), [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)"
"senses": "blindsight 120 ft., passive Perception 14"
"languages": "Aquan"
"cr": "18"
"traits":
- "desc": "Olhydra's innate spellcasting ability is Charisma (spell save DC 20, +12\
    \ to hit with spell attacks). She can innately cast the following spells, requiring\
    \ no material components:\n\nAt will: [wall of ice](/2-Mechanics/CLI/spells/wall-of-ice.md)\n\
    \n1/day: [storm of vengeance](/2-Mechanics/CLI/spells/storm-of-vengeance.md)\n\
    \n3/day: [ice storm](/2-Mechanics/CLI/spells/ice-storm.md)"
  "name": "Innate Spellcasting"
- "desc": "Olhydra's slam attacks are treated as magical for the purpose of bypassing\
    \ resistance and immunity to nonmagical attacks."
  "name": "Empowered Attacks"
- "desc": "If Olhydra fails a saving throw, she can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Olhydra has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Olhydra can enter a hostile creature's space and stop there. She can move\
    \ through a space as narrow as 1 inch wide without squeezing."
  "name": "Water Form"
"actions":
- "desc": "Olhydra makes two slam attacks or two water jet attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 21\
    \ (3d10 + 5) bludgeoning damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 19). Olhydra can grapple up to four targets. When Olhydra moves,\
    \ all creatures she is grappling move with her."
  "name": "Slam"
- "desc": "Ranged Weapon Attack: +12 to hit, range 120 ft., one target. Hit:\
    \ 21 (6d6) bludgeoning damage, and the target is knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)\
    \ if it fails a DC 19 Strength saving throw."
  "name": "Water Jet"
- "desc": "Olhydra summons up to three [water elementals](/2-Mechanics/CLI/bestiary/elemental/water-elemental.md)\
    \ and loses 30 hit points for each elemental she summons. Summoned elementals\
    \ have maximum hit points, appear within 100 feet of Olhydra, and disappear if\
    \ Olhydra is reduced to 0 hit points."
  "name": "Summon Elementals (1/Day)"
"legendary_actions":
- "desc": "One creature that Olhydra is grappling is crushed for 21 (3d10 + 5) bludgeoning\
    \ damage."
  "name": "Crush"
- "desc": "Olhydra releases one creature she is grappling by flinging the creature\
    \ up to 60 feet away from her, in a direction of her choice. If the flung creature\
    \ comes into contact with a solid surface, such as a wall or floor, the creature\
    \ takes 1d6 bludgeoning damage for every 10 feet it was flung."
  "name": "Fling (Costs 2 Actions)"
- "desc": "Olhydra transforms her watery body into acid. This effect lasts until Olhydra's\
    \ next turn. Any creature that comes into contact with Olhydra or hits her with\
    \ a melee attack while standing within 5 feet of her takes 11 (2d10) acid damage.\
    \ Any creature [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled) by Olhydra\
    \ takes 22 (4d10) acid damage at the start of its turn."
  "name": "Water to Acid (Costs 3 Actions)"
"lair_actions":
- "desc": "Olhydra can command the waters around herself to take lair actions on the\
    \ Elemental Plane of Water, or in any elemental water node (such as the Plunging\
    \ Torrents, described in chapter 5). On initiative count 20 (losing initiative\
    \ ties), Olhydra uses her lair action to cause one of the following effects:"
  "name": ""
- "desc": "- Pools of water in the lair surge outward in a grasping tide. Any creature\
    \ within 20 feet of such a pool must succeed on a DC 20 Strength saving throw\
    \ or be pulled up to 20 feet into the water and knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone).\
    \  \n- Water within 120 feet of Olhydra becomes murky and opaque until initiative\
    \ count 20 of the next round. A creature with [darkvision](/2-Mechanics/CLI/rules/senses.md#darkvision)\
    \ can't see through the water, and light can't illuminate it.  \n- A freezing\
    \ fog fills a 40-foot-radius sphere within 120 feet of Olhydra, lasting until\
    \ initiative count 20 of the next round. Creatures and objects within or beyond\
    \ the fog are heavily obscured. A creature that enters the freezing cloud for\
    \ the first time on a turn or starts its turn there takes 10 (3d6) cold damage.\
    \  "
  "name": ""
"regional_effects":
- "desc": "Olhydra's presence in an elemental node creates a number of widespread\
    \ effects—bad weather, strong tides, and increasing aggression from dangerous\
    \ sea life."
  "name": ""
- "desc": "- Violent downpours become frequent within 10 miles of the lair. A downpour\
    \ occurs once every 2d12 hours, and lasts 1d3 hours. Downpours are so heavy\
    \ that creatures moving overland travel at half normal speed  \n- Within 5 miles\
    \ of the lair, currents and tides are exceptionally strong and treacherous. Any\
    \ ability checks made to safely navigate or control a vessel moving through these\
    \ waters has disadvantage.  \n- Aquatic creatures that have an Intelligence score\
    \ of 2 or lower within 1 mile of the lair must succeed on a DC 15 Wisdom saving\
    \ throw when they enter the area. If the saving throw succeeds, the creature is\
    \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened) and attempts to\
    \ leave the area, remaining [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ while within it. On a failure, the creature becomes highly aggressive and remains\
    \ in the area for 24 hours. While in this state, the creature gains advantage\
    \ on saving throws against charm and fear effects.  \n- Natural springs and pools\
    \ within 1 mile of the lair form intermittent portals to the Elemental Plane of\
    \ Water, allowing elemental creatures into the mortal world to dwell near those\
    \ points.  "
  "name": ""
- "desc": "If Olhydra is destroyed or banished back to her home plane, the regional\
    \ effects fade over the next 1d10 days."
  "name": ""
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Olhydra.webp"
```
^statblock

```encounter-table
name: Olhydra
creatures:
 - 1: Olhydra
```