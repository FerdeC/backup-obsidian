---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/7
- monster/size/medium
- monster/type/fey/elf
aliases: ["Smiler the Defiler"]
NoteIcon: monster
BestiaryType: fey (elf)
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 133
---
# [Smiler the Defiler](2-Mechanics\CLI\bestiary\npc/smiler-the-defiler-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 133*  

Smiler has an unnerving smile—hence his name.

A more apt name for this eladrin would be Smiler the Beguiler, as he's constantly trying to intoxicate others with his relentless optimism and shocking recklessness. Smiler thinks he can accomplish anything with a positive attitude and some death-defying stunt. Although he admits others might end up getting killed by his actions, he believes he can bend the multiverse to his whims if he tries hard enough. He's really quite insane.

One of Smiler's favorite antics is to use a [hallucinatory terrain](/2-Mechanics/CLI/spells/hallucinatory-terrain.md) spell to create a little bit of the Feywild in Avernus: a beautiful woodland glade in which to lose himself for a few hours while he meditates and plots.

This eladrin adventurer from the Feywild became stranded in Avernus after his companions abandoned him. He has spent the past seventy years roaming Avernus, making deals with fiends to survive. Smiler eventually sold his soul to a pit fiend, who gave him the means to topple a nycaloth warlord named Yarrasto. Smiler took control of the nycaloth's warband and their infernal war machines. Smiler's gang came to be known as Smiler's Defilers, and their ferocity terrified the other warlords of Avernus for a while.

Three of Smiler's rivals—Bitter Breath, Feonor, and Princeps Kovik—joined forces to wipe out Smiler's Defilers. Smiler escaped and tears around Avernus on a Devil's Ride, looking for adventurers willing to help him get revenge on the warlords who ganged up on him. Mad Maggie remains his only ally, though he refuses to join her gang.

```statblock
"name": "Smiler the Defiler (BGDIA)"
"size": "Medium"
"type": "fey"
"subtype": "elf"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "[+2 leather armor](/2-Mechanics/CLI/items/2-armor.md)"
"hp": !!int "165"
"hit_dice": "22d8 + 66"
"stats":
- !!int "14"
- !!int "20"
- !!int "16"
- !!int "18"
- !!int "11"
- !!int "18"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "7"
  "Persuasion": !!int "7"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Elvish, Sylvan"
"cr": "7"
"traits":
- "desc": "Smiler's innate spellcasting ability is Charisma (spell save DC 15). He\
    \ can innately cast the following spells, requiring no material components:\n\n\
    At will: [charm person](/2-Mechanics/CLI/spells/charm-person.md), [Tasha's\
    \ hideous laughter](/2-Mechanics/CLI/spells/tashas-hideous-laughter.md)\n\n1/day\
    \ each: [hallucinatory terrain](/2-Mechanics/CLI/spells/hallucinatory-terrain.md),\
    \ [Otto's irresistible dance](/2-Mechanics/CLI/spells/ottos-irresistible-dance.md)\n\
    \n3/day each: [confusion](/2-Mechanics/CLI/spells/confusion.md), [enthrall](/2-Mechanics/CLI/spells/enthrall.md),\
    \ [suggestion](/2-Mechanics/CLI/spells/suggestion.md)"
  "name": "Innate Spellcasting"
- "desc": "As a bonus action, Smiler can teleport up to 30 feet to an unoccupied space\
    \ that he can see or to the empty seat of his infernal war machine."
  "name": "Fey Step (Recharge 4-6)"
- "desc": "Smiler has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Smiler wears +2 leather armor. He carries seven soul coins in a bag and\
    \ a +1 shortsword"
  "name": "Equipment"
"actions":
- "desc": "Smiler makes two weapon attacks. He can cast a spell in place of one of\
    \ these attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 9 (1d6\
    \ + 6) piercing damage."
  "name": "+1 Shortsword"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Smiler%20the%20Defiler.webp"
```
^statblock

```encounter-table
name: Smiler the Defiler
creatures:
 - 1: Smiler the Defiler
```