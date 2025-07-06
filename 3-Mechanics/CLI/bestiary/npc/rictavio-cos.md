---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cos
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Rictavio"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Curse of Strahd p. 238
---
# [Rictavio](2-Mechanics\CLI\bestiary\npc/rictavio-cos.md)
*Source: Curse of Strahd p. 238*  

Several months ago, a colorfully dressed half-elf bard came to Barovia in a carnival wagon, with a pet monkey on his shoulder. He took over an abandoned tower on Lake Baratok before rolling into the town of Vallaki several months later. Claiming to be a carnival ringmaster in search of new actors, he began regaling locals with tales of distant lands.

## Monster Hunter

The half-elf ringmaster is, in fact, a legendary human vampire hunter named Rudolph van Richten. Van Richten's tale is a sad one. A scholar and doctor from a land called Darkon, he married his childhood sweetheart, Ingrid, and together they had a son, Erasmus. When he was fourteen, Erasmus was stolen away by Vistani and sold to a vampire named Baron Metus to be used as a companion. By the time van Richten found his son, it was too late: the baron had already transformed Erasmus into a vampire spawn. Erasmus begged his father to end his suffering, which van Richten did by pounding a wooden stake through his son's chest. Baron Metus avenged that deed by killing van Richten's wife, and van Richten has lived with the horror of his family's destruction ever since. After destroying Baron Metus in turn, van Richten sought revenge against the Vistani and took up a life of hunting evil monsters.

## The Waiting Game

Van Richten isn't a young man anymore. He knows his road is coming to an end, but his work isn't done. He has come to Barovia to kill Strahd von Zarovich, the greatest vampire of them all. Van Richten has studied Strahd for years and knows he can't hope to best the vampire in a straight-up confrontation: he must wait for the right moment to strike. He has good evidence to suggest that Strahd periodically hibernates in his coffin, sometimes for years, when all is quiet in the realm. While he bides his time, van Richten hides in plain sight with the aid of a hat of disguise, his thoughts protected by a ring of mind shielding. He is trying to learn more about the Keepers of the Feather - a society of wereravens that oppose Strahd - while trying not to expose the secret society to their mutual enemy. He thinks the wereravens might prove helpful when the time comes. Van Richten also wants to take out as many of Strahd's spies as he can, starting with evil Vistani.

### Man with a Plan

 Van Richten doesn't know that his former protégé, a good-aligned Vistana named Ezmerelda d'Avenir, has come to Barovia looking for him. He taught her many of his monster-hunting techniques, but she doesn't know all of his tricks and disguises. So far, their paths haven't crossed. In the event that van Richten becomes aware of Ezmerelda's presence, he does his utmost to protect her without putting his own plans in jeopardy. If he can manipulate a party of adventurers into keeping an eye on her, he will do so.

Van Richten works alone. A curse placed on him long ago by a Vistani seer brings doom to those he befriends. Furthermore, he believes too much is at stake to risk exposure. Consequently, if he thinks he's in danger of being unmasked, he retreats to his tower (see chapter 11) or some other quiet corner of Strahd's domain.

## Rictavio's Traits

### Ideal

"Evil cannot go unchallenged."

### Bond

"To protect those I love, I must keep them distant and hidden from my enemies."

### Flaw

"I am cursed. Thus, I will never have peace."

```statblock
"name": "Rictavio (CoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Good"
"ac": !!int "12"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "77"
"hit_dice": "14d8 + 14"
"stats":
- !!int "9"
- !!int "12"
- !!int "13"
- !!int "16"
- !!int "18"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "7"
  "Constitution": !!int "4"
"skillsaves":
  "Medicine": !!int "7"
  "Sleight of Hand": !!int "4"
  "Religion": !!int "6"
  "Insight": !!int "7"
  "Perception": !!int "7"
  "Arcana": !!int "9"
"senses": "passive Perception 17"
"languages": "Abyssal, Common, Elvish, Infernal"
"cr": "5"
"traits":
- "desc": "Rictavio is a 9th-level spellcaster. His spellcasting ability is Wisdom\
    \ (spell save DC 15, +7 to hit with spell attacks). Rictavio has the following\
    \ cleric spells prepared:\n\nCantrips (at will): [guidance](/2-Mechanics/CLI/spells/guidance.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md), [mending](/2-Mechanics/CLI/spells/mending.md),\
    \ [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\n1st level (4 slots):\
    \ [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md), [detect evil and good](/2-Mechanics/CLI/spells/detect-evil-and-good.md),\
    \ [protection from evil and good](/2-Mechanics/CLI/spells/protection-from-evil-and-good.md),\
    \ [sanctuary](/2-Mechanics/CLI/spells/sanctuary.md)\n\n2nd level (3 slots):\
    \ [augury](/2-Mechanics/CLI/spells/augury.md), [lesser restoration](/2-Mechanics/CLI/spells/lesser-restoration.md),\
    \ [protection from poison](/2-Mechanics/CLI/spells/protection-from-poison.md)\n\
    \n3rd level (3 slots): [magic circle](/2-Mechanics/CLI/spells/magic-circle.md),\
    \ [remove curse](/2-Mechanics/CLI/spells/remove-curse.md), [speak with dead](/2-Mechanics/CLI/spells/speak-with-dead.md)\n\
    \n4th level (3 slots): [death ward](/2-Mechanics/CLI/spells/death-ward.md),\
    \ [freedom of movement](/2-Mechanics/CLI/spells/freedom-of-movement.md)\n\n5th\
    \ level (1 slots): [dispel evil and good](/2-Mechanics/CLI/spells/dispel-evil-and-good.md)"
  "name": "Spellcasting"
- "desc": "In addition to his sword cane, Rictavio wears a [hat of disguise](/2-Mechanics/CLI/items/hat-of-disguise.md)\
    \ and a [ring of mind shielding](/2-Mechanics/CLI/items/ring-of-mind-shielding.md),\
    \ and he carries a [spell scroll](/2-Mechanics/CLI/items/spell-scroll-5th-level.md)\
    \ of [raise dead](/2-Mechanics/CLI/spells/raise-dead.md)."
  "name": "Special Equipment"
- "desc": "When Rictavio hits an undead with a weapon attack, the undead takes an\
    \ extra 10 (3d6) damage of the weapon's type."
  "name": "Undead Slayer"
"actions":
- "desc": "Rictavio makes two attacks with his sword cane."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) bludgeoning damage (wooden cane) or piercing damage (silvered sword)."
  "name": "Sword Cane"
"source":
- "CoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CoS/Rictavio.webp"
```
^statblock

```encounter-table
name: Rictavio
creatures:
 - 1: Rictavio
```