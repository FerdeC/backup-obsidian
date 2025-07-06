---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Fist of Bane"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 232
---
# [Fist of Bane](2-Mechanics\CLI\bestiary\humanoid/fist-of-bane-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 232*  

Bane's devoted followers are warriors who seek to rule through martial strength and intimidation, cruel tyrants who use threats and gifts as needed to ensure loyalty. They enslave those too weak to resist them and shower the strong with gifts and promises of power to turn them into loyal vassals.

## Cruel Tyrants

Whenever Bane's followers gain power, they institute draconian measures to ensure that their rule is unquestioned. They stamp out all opposition while richly rewarding those who swear fealty.

## Warrior Cult

Cultists of Bane are warriors who wear heavy armor and wield maces, swords, spears, and crossbows. They paint the right gauntlet of their armor black in honor of their patron. Bane's clerics wield black maces with heads shaped to look like a closed fist.

## Cult Ranks

Bane's cultists operate according to strict military hierarchies. The lowest rank consists of the fists of Bane, foot soldiers who obey all orders without hesitation. They are led by iron consuls, cunning field officers who excel at coordinating the fists in combat. The black gauntlets are the priests who command the consuls.

```statblock
"name": "Fist of Bane (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[chain mail](/2-Mechanics/CLI/items/chain-mail.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"stats":
- !!int "16"
- !!int "11"
- !!int "13"
- !!int "10"
- !!int "12"
- !!int "11"
"speed": "30 ft."
"condition_immunities": "[frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "passive Perception 11"
"languages": "Common"
"cr": "1/2"
"traits":
- "desc": "The fist of Bane has advantage on all ability checks and saving throws\
    \ made during combat."
  "name": "Tactical Discipline"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) bludgeoning damage."
  "name": "Mace"
- "desc": "Ranged Weapon Attack: +2 to hit, range 150/600 ft., one target. Hit:\
    \ 4 (1d8) piercing damage."
  "name": "Longbow"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Fist%20of%20Bane.webp"
```
^statblock

```encounter-table
name: Fist of Bane
creatures:
 - 1: Fist of Bane
```