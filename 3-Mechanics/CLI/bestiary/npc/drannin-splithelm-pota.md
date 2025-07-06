---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/7
- monster/size/medium
- monster/type/humanoid/shield-dwarf
aliases: ["Drannin Splithelm"]
NoteIcon: monster
BestiaryType: humanoid (Shield dwarf)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 210
---
# [Drannin Splithelm](2-Mechanics\CLI\bestiary\npc/drannin-splithelm-pota.md)
*Source: Princes of the Apocalypse p. 210*  

Drannin is a self-serving dwarf who has always felt that, due to his heritage, he was owed better than he received. When he didn't receive the accolades, he began to see everyone in his way as the problem, trying to keep him down, and he vowed to do whatever it took to turn the tables. He is currently intent on claiming the legendary axe Orcsplitter, the weapon buried with King Torhild Flametongue of Besilmer many centuries ago. The secret doors and puzzles of the Halls of the Hunting Axe have frustrated Drannin for a long time, but he now has a plan to dupe his cousin Gargosh into finding the axe for him (see the "Halls of the Hunting Axe" side trek in chapter 6). Drannin believes that with Orcsplitter in his possession he can establish himself as a powerful lord among his clan, and finally win the respect he thinks he deserves.

Drannin's most prized possession is his shield guardian. He stole the amulet that controls the shield guardian from a sorcerer some years back.

```statblock
"name": "Drannin Splithelm (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "Shield dwarf"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "[plate armor](/2-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "93"
"hit_dice": "11d8 + 44"
"stats":
- !!int "19"
- !!int "10"
- !!int "18"
- !!int "11"
- !!int "8"
- !!int "12"
"speed": "25 ft."
"skillsaves":
  "Intimidation": !!int "4"
  "Athletics": !!int "7"
"damage_resistances": "cold, poison"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Dwarvish"
"cr": "7"
"traits":
- "desc": "Drannin takes an additional action on his turn."
  "name": "Action Surge (Recharges after a Short or Long Rest)"
- "desc": "A melee weapon deals one extra die of its damage when Drannin hits with\
    \ it (included in the attack)."
  "name": "Brute"
- "desc": "Drannin has advantage on saving throws against poison."
  "name": "Dwarven Resilience"
- "desc": "Drannin can reroll a saving throw that he fails. He must use the new roll."
  "name": "Indomitable (Recharges after a Short or Long Rest)"
- "desc": "Drannin can use a bonus action to regain 16 (1d10 + 11) hit points."
  "name": "Second Wind (Recharges after a Short or Long Rest)"
- "desc": "Drannin wears a control amulet for his [shield guardian](/2-Mechanics/CLI/bestiary/construct/shield-guardian.md)\
    \ (see the Monster Manual) and a [ring of cold resistance](/2-Mechanics/CLI/items/ring-of-cold-resistance.md).\
    \ He also carries a [potion of frost giant strength](/2-Mechanics/CLI/items/potion-of-frost-giant-strength.md)."
  "name": "Special Equipment"
"actions":
- "desc": "Drannin makes three attacks with his greataxe."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 17\
    \ (2d12 + 4) slashing damage."
  "name": "Greataxe"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Drannin%20Splithelm.webp"
```
^statblock

```encounter-table
name: Drannin Splithelm
creatures:
 - 1: Drannin Splithelm
```