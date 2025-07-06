---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/23
- monster/size/gargantuan
- monster/type/elemental
aliases: ["Maegera the Dawn Titan"]
NoteIcon: monster
BestiaryType: elemental
SourceType: Bestiary
BookSource: Storm King's Thunder p. 241
---
# [Maegera the Dawn Titan](2-Mechanics\CLI\bestiary\npc/maegera-the-dawn-titan-skt.md)
*Source: Storm King's Thunder p. 241*  

Maegera is powerful elemental that has been trapped in the forges of Gauntlgrym for millennia. About fifty years ago, Maegera briefly escaped and triggered the eruption of Mount Hotenow. Lava from the volcano flowed toward the coast, laying waste to Neverwinter. The city is still rebuilding in the wake of that catastrophe.

The fire giant duke Zalto recently sent a team of drow to infiltrate Gauntlgrym and trap Maegera in an iron flask . Zalto needs the primordial to ignite an adamantine forge beneath the Ice Spires. Returning Maegera to Gauntlgrym is one way to thwart the fire giant's plans.

Maegera looks like a 50-foot-tall, multi-limbed beast made of flame, with smoldering black pits for eyes.

```statblock
"name": "Maegera the Dawn Titan (SKT)"
"size": "Gargantuan"
"type": "elemental"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"hp": !!int "341"
"hit_dice": "22d20 + 110"
"stats":
- !!int "21"
- !!int "22"
- !!int "20"
- !!int "10"
- !!int "10"
- !!int "19"
"speed": "50 ft."
"saves":
  "Charisma": !!int "11"
  "Wisdom": !!int "7"
  "Constitution": !!int "12"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned), [prone](/2-Mechanics/CLI/rules/conditions.md#prone),\
  \ [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)"
"senses": "blindsight 120 ft., passive Perception 10"
"languages": "Ignan"
"cr": "23"
"traits":
- "desc": "Maegera casts [fireball](/2-Mechanics/CLI/spells/fireball.md) (spell save\
    \ DC 19), requiring no material components and using Charisma as the spellcasting\
    \ ability.\n"
  "name": "Spellcasting"
- "desc": "Maegera's slam attacks are treated as magical for the purpose of overcoming\
    \ resistance and immunity to damage from nonmagical attacks."
  "name": "Empowered Attacks"
- "desc": "At the start of each of Maegera's turns, each creature within 30 feet of\
    \ it takes 35 (10d6) fire damage, and flammable objects in the aura that aren't\
    \ being worn or carried ignite. A creature also takes 35 (10d6) fire damage\
    \ from touching Maegera or from hitting it with a melee attack while within 10\
    \ feet of it, and a creature takes that damage the first time on a turn that Maegera\
    \ moves into its space. Nonmagical weapons that hit Maegera are destroyed by fire\
    \ immediately after dealing damage to it."
  "name": "Fire Aura"
- "desc": "Maegera can enter a hostile creature's space and stop there. It can move\
    \ through a space as narrow as 1 inch wide without squeezing if fire could pass\
    \ through that space."
  "name": "Fire Form"
- "desc": "Maegera sheds bright light in a 120-foot radius and dim light in an additional\
    \ 120 ft.."
  "name": "Illumination"
- "desc": "Maegera has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Maegera makes three slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 15 ft., one target. Hit: 15\
    \ (3d6 + 5) bludgeoning damage plus 35 (10d6) fire damage"
  "name": "Slam"
"legendary_actions":
- "desc": "Maegera targets one creature that it can see within 60 feet of it. Any\
    \ resistance or immunity to fire damage that the target gains from a spell or\
    \ magic item is suppressed. The effect lasts until the end of Maegera's next turn."
  "name": "Quench Magic"
- "desc": "Maegera exhales a billowing cloud of hot smoke and embers that fills a\
    \ 60 feet cube. Each creature in the area takes 11 (2d10) fire damage. The cloud\
    \ lasts until the end of Maegera's next turn. Creatures completely in the cloud\
    \ are [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded) and can't be seen."
  "name": "Smoke Cloud (Costs 2 Actions)"
- "desc": "Maegera's hit points are reduced by 50 as part of it separates and becomes\
    \ a [fire elemental](/2-Mechanics/CLI/bestiary/elemental/fire-elemental.md) with\
    \ 102 hit points. The fire element appears in an unoccupied space within 15 feet\
    \ of Maegera and acts on Maegera's initiative count. Maegera can't use this action\
    \ if it has 50 hit points or fewer. The fire element obeys Maegera's commands\
    \ and fights until destroyed."
  "name": "Create Fire Elemental (Costs 3 Actions)"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Maegera%20the%20Dawn%20Titan.webp"
```
^statblock

```encounter-table
name: Maegera the Dawn Titan
creatures:
 - 1: Maegera the Dawn Titan
```