---
<<<<<<< HEAD
xpActual: 1700
nivel: 3
=======
obsidianUIMode: preview
nivel: 3
xpActual: 2000
>>>>>>> origin/master
---


%% This note is designed to be dragged into the left side panel and assumes you are using DnD5e Notes created by the [CLI Process](https://obsidianttrpgtutorials.com/Obsidian+TTRPG+Tutorials/Plugin+Tutorials/TTRPG-Convert-CLI/TTRPG-Convert-CLI+5e). This creates a simple icon that can be used to quickly access links to commonly used rules. Add to this with whatever you need. %%

| Name             | Effect                              |  
| ---------------- | ----------------------------------- | 
| Experiencia:     | `=this.xpActual`                    | 
| Nivel            | `=this.nivel`                       |
| Xp para sig. nivel| inserta el codigo aqui                       |
| Resistance       | 1/2 dmg                             | 
| Immunity         | 0 damage                            | 
| Vulnerable       | x2 damage                           |
| Half-Cover       | +2 ac                               |
| 3/4 Cover        | +5 ac                               | 
| Total Cover      | Can't be targeted directly          |
| Obscured         | Disadvantage                        |
| Lightly Obscured | Disadvantage on Wisdom (Perception) |

<br>

>[!info]+ Progreso de experiencia
>```dataviewjs
>const sideScreenNotePath = "1-DM Toolkit/DnD5e-SideScreen.md";
>
>// Obtener los datos del personaje
>const sideScreenPage = dv.page(sideScreenNotePath);
>
>if (!sideScreenPage) {
>    dv.paragraph(`⚠️ No se encontró la nota: "${sideScreenNotePath}"`);
>} else {
>    const xpActual = Number(sideScreenPage.xpActual ?? 0);
>    const nivelActual = Number(sideScreenPage.nivel ?? 1);
>
>    // Tabla de experiencia
>    const xpTable = [
>        { nivel: 1, xp: 0 },
>        { nivel: 2, xp: 300 },
>        { nivel: 3, xp: 900 },
>        { nivel: 4, xp: 2700 },
>        { nivel: 5, xp: 6500 },
>        { nivel: 6, xp: 14000 },
>        { nivel: 7, xp: 23000 },
>        { nivel: 8, xp: 34000 },
>        { nivel: 9, xp: 48000 },
>        { nivel: 10, xp: 64000 },
>        { nivel: 11, xp: 85000 },
>        { nivel: 12, xp: 100000 },
>        { nivel: 13, xp: 120000 },
>        { nivel: 14, xp: 140000 },
>        { nivel: 15, xp: 165000 },
>        { nivel: 16, xp: 195000 },
>        { nivel: 17, xp: 225000 },
>        { nivel: 18, xp: 265000 },
>        { nivel: 19, xp: 305000 },
>        { nivel: 20, xp: 355000 }
>    ];
>
>    let xpNextLevel, xpFaltante, nivelDestino;
>
>    if (nivelActual >= 20) {
>        xpNextLevel = "Ya eres nivel máximo";
>        xpFaltante = "0";
>        nivelDestino = "20";
>    } else {
>        const nextEntry = xpTable.find(row => row.nivel === nivelActual + 1);
>        xpNextLevel = nextEntry?.xp ?? "Desconocido";
>        xpFaltante = nextEntry ? nextEntry.xp - xpActual : "Desconocido";
>        nivelDestino = nextEntry?.nivel ?? "Desconocido";
>    }
>
>    // Render
>    dv.paragraph(`**XP para el Siguiente Nivel:** ${xpNextLevel}`);
>    dv.paragraph(`**XP Faltante:** ${xpFaltante}`);
>}
>```


> [!info]- Tabla de experiencia
| Nivel | XP Requerida | Nivel | XP Requerida |
| :---- | :----------- | :---- | :----------- |
| 1     | 0            | 11    | 85,000       |
| 2     | 300          | 12    | 100,000      |
| 3     | 900          | 13    | 120,000      |
| 4     | 2,700        | 14    | 140,000      |
| 5     | 6,500        | 15    | 165,000      |
| 6     | 14,000       | 16    | 195,000      |
| 7     | 23,000       | 17    | 225,000      |
| 8     | 34,000       | 18    | 265,000      |
| 9     | 48,000       | 19    | 305,000      |
| 10    | 64,000       | 20    | 355,000      |

> [!info]- Abilities
> [[08-using-ability-scores#Dexterity|Dexterity]]
> [[08-using-ability-scores#Strength|Strength]]
> [[08-using-ability-scores#Constitution|Constitution]]
> [[08-using-ability-scores#Intelligence|Intelligence]]
> [[08-using-ability-scores#Wisdom|Wisdom]]
> [[08-using-ability-scores#Charisma|Charisma]]

> [!info]- Checks
> [[09-adventuring#Vision and Light|Vision and Light]]
> [[detect-magic|Detect Magic]]
> [[08-using-ability-scores#Advantage and Disadvantage|Advantage and Disadvantage]]
> [[08-using-ability-scores#Proficiency Bonus|Proficiency Bonus]]
> [[08-using-ability-scores#Ability Checks|Ability Checks]]
> [[08-using-ability-scores#Contests|Contests]]
> [[08-using-ability-scores#Skills|Skills]]
> [[08-using-ability-scores#Lifting and Carrying|Lifting and Carrying]]

> [!info]- Conditions
> [[Conditions#Blinded|Blinded]]
> [[Conditions#Charmed|Charmed]]
> [[Conditions#Concentration|Concentration]]
> [[Conditions#Deafened|Deafened]]
> [[Conditions#Exhaustion|Exhaustion]]
> [[Conditions#Frightened|Frightened]]
> [[Conditions#Grappled|Grappled]]
> [[Conditions#Incapacitated|Incapacitated]]
> [[Conditions#Invisible|Invisible]]
> [[Conditions#Paralyzed|Paralyzed]]
> [[Conditions#Petrified|Petrified]]
> [[Conditions#Poisoned|Poisoned]]
> [[Conditions#Prone|Prone]]
> [[Conditions#Restrained|Restrained]]
> [[Conditions#Stunned|Stunned]]
> [[Conditions#Unconscious|Unconscious]]

> [!info]- Combat Actions
> [[actions#Actions#Activate an Item|Activate an Item]]
> [[actions#Actions#Attack|Attack]]
> [[actions#Actions#Cast a Spell|Cast a Spell]]
> [[actions#Actions#Dash|Dash]]
> [[actions#Actions#Disengage|Disengage]]
> [[actions#Actions#Dodge|Dodge]]
> [[actions#Actions#Help|Help]]
> [[actions#Actions#Hide|Hide]]
> [[actions#Actions#Ready|Ready]]
> [[actions#Actions#Search|Search]]
> [[actions#Actions#Use an Object|Use an Object]]
> [[actions#Actions#Escape a Grapple|Escape a Grapple]]

> [!info]- Misc. Combat
> [[10-combat#Surprise|Surprise]]
> [[10-combat#Initiative|Initiative]]
> [[10-combat#Reactions|Reactions]]
> [[10-combat#Moving around Other Creatures|Moving around Other Creatures]]
> [[10-combat#Unseen Attackers and Targets|Unseen Attackers and Targets]]
> [[10-combat#Grappling|Grappling]]
> [[10-combat#Shoving a Creature|Shoving a Creature]]
> [[10-combat#Two-Weapon Fighting|Two-Weapon Fighting]]
> [[06-equipment#Improvised Weapons|Improvised Weapons]]
> [[10-combat#Being Prone|Being Prone]]
> [[10-combat#Ranged Attacks in Close Combat|Ranged Attacks in Close Combat]]
> [[10-combat#Mounted Combat|Mounted Combat]]

> [!info]- Movement
> [[09-adventuring#Movement|Movement]]
> [[09-adventuring#Difficult Terrain|Difficult Terrain]]
> [[09-adventuring#Movement#Travel Pace|Travel Pace]]
> [[09-adventuring#Movement#Forced March|Forced March]]
> [[09-adventuring#Movement#Mounts and Vehicles|Mounts and Vehicles]]
> [[09-adventuring#Movement#Difficult Terrain|Difficult Terrain]]
> [[09-adventuring#Movement#Special Types of Movement|Special Types of Movement]]
> [[09-adventuring#Movement#Climbing, Swimming, and Crawling|Climbing, Swimming, and Crawling]]
> [[09-adventuring#Movement#Jumping|Jumping]]
> [[09-adventuring#Movement#Activity While Traveling|Activity While Traveling]]

> [!info]- Resting
> [[09-adventuring#Food and Water|Food and Water]]
> [[09-adventuring#Resting|Resting]]
> [[09-adventuring#Short Rest|Short Rest]]
> [[09-adventuring#Long Rest|Long Rest]]
> [[09-adventuring#Recuperating|Recuperating]]

> [!info]- Healing and Death
> [[10-combat#Damage and Healing#Healing|Healing]]
> [[10-combat#Dropping to 0 Hit Points#Instant Death|Instant Death]]
> [[10-combat#Dropping to 0 Hit Points#Falling Unconscious|Falling Unconscious]]
> [[10-combat#Dropping to 0 Hit Points#Death Saving Throws|Death Saving Throws]]
> [[10-combat#Dropping to 0 Hit Points#Stabilizing a Creature|Stabilizing a Creature]]
> [[10-combat#Dropping to 0 Hit Points#Monsters and Death|Monsters and Death]]

> [!info]- Weapons and Armor
> [[weapons|Weapons]]
> [[armor-and-shields-armor|Armor and Shields]]

> [!info]- Magic Schools
> [[wizard-school-of-abjuration|Abjuration]]
> [[wizard-school-of-conjuration|Conjuration]]
> [[wizard-school-of-divination|Divination]]
> [[wizard-school-of-enchantment|Enchantment]]
> [[wizard-school-of-evocation|Evocation]]
> [[wizard-school-of-illusion|Illusion]]
> [[wizard-school-of-necromancy|Necromancy]]
> [[wizard-school-of-transmutation|Transmutation]]

> [!info]- Skills
> [[Skills#Acrobatics|Acrobatics]]
> [[Skills#Animal Handling|Animal Handling]]
> [[Skills#Arcana|Arcana]]
> [[Skills#Athletics|Athletics]]
> [[Skills#Deception|Deception]]
> [[Skills#History|History]]
> [[Skills#Insight|Insight]]
> [[Skills#Intimidation|Intimidation]]
> [[Skills#Investigation|Investigation]]
> [[Skills#Medicine|Medicine]]
> [[Skills#Nature|Nature]]
> [[Skills#Perception|Perception]]
> [[Skills#Performance|Performance]]
> [[Skills#Persuasion|Persuasion]]
> [[Skills#Religion|Religion]]
> [[Skills#Sleight of Hand|Sleight of Hand]]
> [[Skills#Stealth|Stealth]]
> [[Skills#Survival|Survival]]
