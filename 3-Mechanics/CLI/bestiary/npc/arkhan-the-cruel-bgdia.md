---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/16
- monster/size/medium
- monster/type/humanoid/dragonborn
aliases: ["Arkhan the Cruel"]
NoteIcon: monster
BestiaryType: humanoid (dragonborn)
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 111
---
# [Arkhan the Cruel](2-Mechanics\CLI\bestiary\npc/arkhan-the-cruel-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 111*  

Arkhan the Cruel is an evil dragonborn champion of Tiamat. Arkhan believes he can use the Hand of Vecna to unlock the means of freeing Tiamat from her prison in the Nine Hells, but only if the hand doesn't kill him first. The hand is slowly corrupting Arkhan's flesh and decomposing his body on one side.

In battle, Arkhan uses branding smite to channel the radiant power of Tiamat into his weapon attacks. If a fight turns against him, he uses the teleport power of the Hand of Vecna to return to his tower with as many allies as possible. Should one or more of his comrades fall in battle, Arkhan uses [revivify](/2-Mechanics/CLI/spells/revivify.md) and [raise dead](/2-Mechanics/CLI/spells/raise-dead.md) spells to bring them back to life as soon as possible.

If Arkhan finds himself overwhelmed with opposition, he orders the abishai to attack. Arkhan can also use a bonus action to call forth Asojano, a chimera lairing in the depths of the colossal dragon skull.

```statblock
"name": "Arkhan the Cruel (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "dragonborn"
"alignment": "Lawful Evil"
"ac": !!int "23"
"ac_class": "[obsidian flint dragon plate](/2-Mechanics/CLI/items/obsidian-flint-dragon-plate-bgdia.md),\
  \ [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "221"
"hit_dice": "26d8 + 104"
"stats":
- !!int "20"
- !!int "12"
- !!int "18"
- !!int "10"
- !!int "10"
- !!int "18"
"speed": "40 ft."
"saves":
  "Charisma": !!int "9"
  "Wisdom": !!int "5"
"skillsaves":
  "Intimidation": !!int "9"
  "Athletics": !!int "10"
  "Deception": !!int "9"
"damage_resistances": "fire; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"condition_immunities": "[frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "darkvision 60 ft. (can see invisible creatures out to the same range),\
  \ passive Perception 10"
"languages": "Common, Draconic"
"cr": "16"
"traits":
- "desc": "Arkhan's spellcasting ability is Charisma (spell save DC 17). He can cast\
    \ the following spells, requiring no material components:\n\n1/day each: [geas](/2-Mechanics/CLI/spells/geas.md),\
    \ [raise dead](/2-Mechanics/CLI/spells/raise-dead.md)\n\n3/day each: [animate\
    \ dead](/2-Mechanics/CLI/spells/animate-dead.md), [branding smite](/2-Mechanics/CLI/spells/branding-smite.md)\
    \ (at 4th level), [revivify](/2-Mechanics/CLI/spells/revivify.md)"
  "name": "Innate Spellcasting"
- "desc": "While Arkhan isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated),\
    \ he and all fiends and undead within 30 feet of him deal 4 extra damage whenever\
    \ they hit with a melee weapon attack (already factored into Arkhan's attacks).\
    \ This extra damage is of the same type as the weapon's damage type."
  "name": "Aura of Hate"
- "desc": "The [Hand of Vecna](/2-Mechanics/CLI/items/hand-of-vecna.md) has 8 charges\
    \ and regains 1d4 + 4 expended charges daily at dawn. Arkhan can cast the following\
    \ spells from the hand by expending the specified number of charges (spell save\
    \ DC 18): [finger of death](/2-Mechanics/CLI/spells/finger-of-death.md) (5 charges),\
    \ [sleep](/2-Mechanics/CLI/spells/sleep.md) (1 charge), [slow](/2-Mechanics/CLI/spells/slow.md)\
    \ (2 charges), and [teleport](/2-Mechanics/CLI/spells/teleport.md) (3 charges)."
  "name": "Hand of Vecna"
- "desc": "Arkhan wields [Fane-Eater](/2-Mechanics/CLI/items/fane-eater-bgdia.md)\
    \ and wears a suit of [Obsidian Flint Dragon Plate](/2-Mechanics/CLI/items/obsidian-flint-dragon-plate-bgdia.md).\
    \ The armor gives Arkhan advantage on ability checks and saving throws made to\
    \ avoid or end the [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled) condition\
    \ on him."
  "name": "Special Equipment"
"actions":
- "desc": "Arkhan makes three weapon attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +13 to hit, reach 5 ft., one target. Hit: 16\
    \ (1d8 + 12) slashing damage, or 17 (1d10 + 12) slashing damage when used\
    \ with two hands, plus 9 (2d8) cold damage. If the target is a creature and\
    \ Arkhan rolls a 20 on the attack roll, the creature takes an extra 9 (2d8)\
    \ necrotic damage, and Arkhan regains an amount of hit points equal to the necrotic\
    \ damage dealt."
  "name": "Fane-Eater (Battleaxe)"
- "desc": "Melee or Ranged Weapon Attack: +10 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 8 (1d6 + 5) piercing damage, plus 4 piercing damage\
    \ and 9 (2d8) cold damage if the javelin was used to make a melee attack."
  "name": "Javelin"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Arkhan%20the%20Cruel.webp"
```
^statblock

```encounter-table
name: Arkhan the Cruel
creatures:
 - 1: Arkhan the Cruel
```