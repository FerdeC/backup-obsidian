---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/1
- monster/environment/desert
- monster/environment/swamp
- monster/environment/underdark
- monster/size/tiny
- monster/type/fiend
aliases: ["Vargouille"]
NoteIcon: monster
BestiaryType: fiend
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 251, Volo's Guide to Monsters p. 195
---
# [Vargouille](2-Mechanics\CLI\bestiary\fiend/vargouille-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 251, Volo's Guide to Monsters p. 195*  

Shrieking, flapping, and hideous to behold—with a body like a severed head and wings in place of ears—vargouilles boil out of the Abyss to infest other planes of existence, such as Carceri, where they are a menace. Each vargouille carries a disease that creates more of its kind; a flock of vargouilles on the wing is a plague of chaos and evil.

Swarms of vargouilles flap through the caverns and skies of the Abyss. They are given little regard by powerful and intelligent demons since vargouilles can do them no harm. Even the weakest demon, such as a manes or a dretch, fears vargouilles only if they appear in great numbers. In the Lower Planes, vargouilles rarely get the chance to eat live prey other than vermin. More often, they lap up the ichor left behind when one Fiend kills another.

Because of their hunger for living prey, vargouilles are eager to escape the Lower Planes. On rare occasions, summoning a demon to another plane can bring a vargouille along for the ride, attached like a tick. The precautions a mortal takes to control a summoned demon rarely account for a stowaway, enabling the vargouille to escape into the world.

Vargouilles that roam free on the Material Plane are a dire threat to all creatures. Their awful shrieking can paralyze other creatures with fear, which also makes the creatures susceptible to the vargouille's curse. If the curse is allowed to run its course, an abyssal spirit invades the person's body, causing a gruesome transformation. Over a period of hours, the victim's head takes on fiendish aspects, such as fangs, tentacles, and horns. At the same time, the person's ears grow larger, expanding into wing-like appendages. In the final moments, the victim's head tears away from the body in a fountain of blood, becoming another vargouille, which often then eagerly laps up the blood spilling from its former body. Sunlight or the brilliant illumination of a [daylight](/2-Mechanics/CLI/spells/daylight.md) spell can delay this transformation; otherwise, only magic can overcome the curse. 

```statblock
"name": "Vargouille (MPMM)"
"size": "Tiny"
"type": "fiend"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "12"
"hp": !!int "18"
"hit_dice": "4d4 + 8"
"stats":
- !!int "6"
- !!int "14"
- !!int "14"
- !!int "4"
- !!int "7"
- !!int "2"
"speed": "5 ft., fly 40 ft."
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 8"
"languages": "understands Abyssal, Infernal, and any languages it knew before becoming\
  \ a vargouille but can't speak"
"cr": "1"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage plus 10 (3d6) poison damage."
  "name": "Bite"
- "desc": "The vargouille targets one [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ Humanoid within 5 feet of it. The target must succeed on a DC 12 Charisma saving\
    \ throw or become cursed. The cursed target loses 1 point of Charisma after each\
    \ hour, as its head takes on fiendish aspects. The curse doesn't advance while\
    \ the target is in sunlight or the area of a [daylight](/2-Mechanics/CLI/spells/daylight.md)\
    \ spell; don't count that time. When the cursed target's Charisma becomes 2, it\
    \ dies, and its head tears from its body and becomes a new vargouille. Casting\
    \ [remove curse](/2-Mechanics/CLI/spells/remove-curse.md), [greater restoration](/2-Mechanics/CLI/spells/greater-restoration.md),\
    \ or a similar spell on the target before the transformation is complete can end\
    \ the curse. Doing so undoes the changes made to the target by the curse."
  "name": "Abyssal Curse"
- "desc": "The vargouille shrieks. Each Humanoid and Beast within 30 feet of the vargouille\
    \ and able to hear it must succeed on a DC 12 Wisdom saving throw or be [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ of the vargouille until the end of the vargouille's next turn. While [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ in this way, a target is [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned).\
    \ If a target's saving throw is successful or the effect ends for it, the target\
    \ is immune to the Stunning Shriek of all vargouilles for 1 hour."
  "name": "Stunning Shriek (Recharge 5-6)"
"source":
- "MPMM"
- "VGM"
- "AATM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPMM/Vargouille.webp"
```
^statblock

```encounter-table
name: Vargouille
creatures:
 - 1: Vargouille
```

## Environment

desert, swamp, underdark