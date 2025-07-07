---
obsidianUIMode: preview
assa:
---
> [!tip]+ Crear nuevo contenido
> 
> <div style="display: flex; gap: 1em; flex-wrap: wrap;">
> 
> ```meta-bind-button
> label: New Journal Entry
> style: primary
> actions:
>   - type: templaterCreateNote
>     templateFile: "z_Templates/TemplateJournal.md"
>     fileName: NewJournal
> ```
> 
> ```meta-bind-button
> label: New Codex Entry
> style: primary
> actions:
>   - type: templaterCreateNote
>     templateFile: "z_Templates/TemplateCodex.md"
>     fileName: NewCodex
> ```
> 
> ```meta-bind-button
> label: New NPC
> style: primary
> actions:
>   - type: templaterCreateNote
>     templateFile: "z_Templates/TemplateNPC.md"
>     fileName: NewNPC
> ```
> 
> ```meta-bind-button
> label: New City
> style: primary
> actions:
>   - type: templaterCreateNote
>     templateFile: "z_Templates/TemplateCity.md"
>     fileName: NewCity
> ```
> 
> ```meta-bind-button
> label: New Location
> style: primary
> actions:
>   - type: templaterCreateNote
>     templateFile: "z_Templates/TemplateSettlement.md"
>     fileName: NewLocation
> ```
> 
> ```meta-bind-button
> label: New Guild or Group
> style: primary
> actions:
>   - type: templaterCreateNote
>     templateFile: "z_Templates/TemplateGroup.md"
>     fileName: NewGroup
> ```
> 
> ```meta-bind-button
> label: New Magic Item
> style: primary
> actions:
>   - type: templaterCreateNote
>     templateFile: "z_Templates/TemplateMagicItem.md"
>     fileName: NewMagicItem
> ```
> 
> ```meta-bind-button
> label: New Player
> style: primary
> actions:
>   - type: templaterCreateNote
>     templateFile: "z_Templates/TemplatePlayer.md"
>     fileName: NewPlayer
> ```

> `BUTTON[button_quest]`
> 
> </div>


## Afinidades


| Religión   | Favor | Estado      | Favor | 
| ---------- | ----- | ----------- | ----- |
| Ilyareth   | 0     | Varkass     | 0     |
| Nyssara    | 0     | Elkar       | 0     |
| Vharun     | 0     | Vael Torith | 0     |
| Zareth'Kal | 0     | Darran-Kar  | 0     |
|            |       | Aetheryn    | 0     |
|            |       | Seliar      | 0     |
|            |       | Velkaris    | 0     |
|            |       | Myrianor    | 0     |

## Quests

```dataview
TABLE WITHOUT ID link(file.name) AS "Quest Name", questStatus AS "Status", questGiver AS "Quest Giver", questLocationObtained AS "Location", questSessionObtained AS "Session", questLootAvail AS "Available Rewards", questLookEarned AS "Acquired Rewards"
from "2-Campaign" AND #quest SORT link(file.name) ASC

```


### 🎲 Tabla d100 – Efectos de Magia Inesperada

|d100|Efecto Caótico Mágico|
|---|---|
|01|El hechizo falla por completo, pero se consume el espacio de conjuro.|
|02|El hechizo tiene el efecto opuesto (curar daña, fuego se vuelve hielo, etc).|
|03|El conjurador se convierte en una estatua de mármol durante 1 minuto (consciente).|
|04|Una bandada de mariposas mágicas aparece y vuela en círculos durante 1 minuto.|
|05|El lanzador se encoge a la mitad de su tamaño por 10 minutos.|
|06|El lanzador se vuelve invisible por 1 minuto (concentración no requerida).|
|07|El hechizo se duplica y afecta a un objetivo adicional aleatorio.|
|08|El lanzador se teletransporta 30 pies en una dirección aleatoria.|
|09|Todas las criaturas a 10 pies del conjurador oyen música celestial durante 1 minuto.|
|10|El conjurador flota 10 cm sobre el suelo durante 1 hora.|
|11|Todos los objetos no mágicos en 10 pies flotan durante 1 minuto.|
|12|El lanzador cambia de género durante 24 horas.|
|13|El hechizo se lanza con éxito y no consume espacio de conjuro.|
|14|El siguiente hechizo del conjurador tiene desventaja automática.|
|15|Una planta brota de los pies del lanzador y crece 1 metro en 6 segundos.|
|16|Un aura de luz brilla alrededor del conjurador por 1 minuto (20 pies).|
|17|El conjurador habla un idioma aleatorio por 1 hora.|
|18|Todos los colores dentro de 10 pies se tornan en escala de grises por 1 minuto.|
|19|Un duplicado ilusorio del conjurador aparece y lo imita durante 1 minuto.|
|20|El hechizo es tan potente que inflige daño máximo (si corresponde).|
|21|Aparece una pequeña tormenta sobre la cabeza del conjurador (truenos, sin daño).|
|22|El hechizo afecta al lanzador en lugar del objetivo.|
|23|El conjurador queda mudo por 1 minuto.|
|24|El conjurador puede volar (velocidad 10 pies) durante 1 minuto.|
|25|El objetivo del hechizo cambia aleatoriamente a otra criatura visible.|
|26|El lanzador envejece o rejuvenece 1d10 años (a elección del DM).|
|27|Una risa histérica incontrolable afecta al lanzador por 1 turno.|
|28|El hechizo genera una explosión de confeti y luces, sin efecto real.|
|29|Una flor brota de la palma del lanzador.|
|30|El lanzador recibe inspiración bardica (1d6) por 10 minutos.|
|31|El conjurador ve el aura mágica de todo durante 1 minuto.|
|32|El hechizo se duplica, pero el segundo tiene efecto reducido (mitad).|
|33|El lanzador crece el doble de su tamaño por 1 minuto (sin cambiar estadísticas).|
|34|La ropa del conjurador cambia de color aleatoriamente.|
|35|Todas las monedas del conjurador se convierten en hojas por 1 hora.|
|36|El lanzador lanza un hechizo distinto de su lista (al azar).|
|37|El conjurador pierde la memoria de los últimos 10 minutos.|
|38|Una criatura extraplanar menor aparece (inofensiva, curiosa).|
|39|El conjurador adquiere visión en la oscuridad por 1 hora.|
|40|El lanzador queda cegado por luces brillantes durante 1 turno.|
|41–50|El hechizo ocurre normalmente, sin efectos adicionales.|
|51|El lanzador se vuelve incorpóreo durante 6 segundos (ignora colisiones).|
|52|Todas las armas metálicas en 10 pies se magnetizan entre sí.|
|53|El conjurador obtiene resistencia al daño mágico por 1 minuto.|
|54|El hechizo afecta un área el doble de lo normal.|
|55|El lanzador olvida cómo lanzar ese hechizo por 1 día.|
|56|El conjurador emite chispas de luz al hablar durante 1 hora.|
|57|El conjurador queda envuelto en llamas ilusorias (sin daño).|
|58|El lanzador puede respirar bajo el agua durante 10 minutos.|
|59|El conjurador habla como si tuviera eco profundo durante 1 hora.|
|60|El lanzador lanza involuntariamente un _Prestidigitación_.|
|61|El hechizo funciona mejor: +1d4 al daño o +1 a la CD si aplica.|
|62|El hechizo cambia a uno de igual nivel del mismo tipo, al azar.|
|63|El lanzador escucha voces etéreas durante 1 minuto.|
|64|Todas las plantas en 30 pies crecen rápidamente durante 1 minuto.|
|65|El hechizo se lanza al doble de su duración normal.|
|66|El conjurador estornuda y un pequeño rayo sale de su nariz.|
|67|El conjurador obtiene +2 a la CA durante 1 minuto.|
|68|El conjurador ve el futuro inmediato (ventaja en la siguiente tirada).|
|69|El lanzador queda paralizado de la cintura para abajo por 1 turno.|
|70|El conjurador huele a flores intensamente durante 1 hora.|
|71|La sombra del lanzador cobra vida y baila durante 1 minuto.|
|72|El hechizo salta a un enemigo cercano adicional.|
|73|El conjurador olvida su propio nombre por 1 hora.|
|74|El lanzador absorbe parte de la energía mágica y sana 1d8 PV.|
|75|El conjurador se rodea de una niebla densa durante 30 segundos.|
|76|El lanzador invoca sin querer un cubo de gelatina (hostil o no).|
|77|Un portal efímero se abre a otro plano durante 1 turno (sin criaturas).|
|78|El conjurador escucha el nombre de una entidad olvidada.|
|79|El lanzador brilla como una antorcha durante 1 hora.|
|80|El hechizo se lanza sin necesidad de componentes.|
|81–90|El hechizo ocurre normalmente.|
|91|El lanzador lanza el mismo hechizo otra vez al siguiente turno, gratis.|
|92|El conjurador se siente eufórico: ventaja en todas tiradas por 1 minuto.|
|93|El lanzador se cura 2d10 puntos de vida al lanzar el hechizo.|
|94|El hechizo afecta a todas las criaturas enemigas visibles.|
|95|El conjurador entra en trance: no puede ser sorprendido durante 1 hora.|
|96|El lanzador comprende todos los idiomas por 1 hora.|
|97|El siguiente hechizo lanzado en 1 minuto se lanza como si fuera de nivel superior.|
|98|El conjurador gana un punto de inspiración (DMG).|
|99|Un deseo menor se concede (elige un efecto menor de "Deseo", DM decide).|
|100|El lanzador se convierte brevemente en un ser de pura magia: lanza cualquier hechizo de su lista sin coste. Luego queda exhausto (nivel 3).|

---

¿Deseas que esta tabla tenga un estilo visual para imprimir o usar en pantalla? También puedo hacerte una versión reducida o temática (por escuela de magia, por ejemplo).



# TEST 
## botones old 

```dataview
TABLE WITHOUT ID link(file.name) AS "Character Name", Player, hp, ac, pasperc As "Spells used"
from "1-Party"
where contains(Role, "Player") 
where contains(Status, "Active")
```

```meta-bind-button
label: New Journal Entry
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateJournal.md"
    fileName: NewJournal
```

```meta-bind-button
label: New Codex Entry
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateCodex.md"
    fileName: NewCodex
```

```meta-bind-button
label: New NPC
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateNPC.md"
    fileName: NewNPC
```

```meta-bind-button
label: New City
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateCity.md"
    fileName: NewCity
```

```meta-bind-button
label: New Location
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateSettlement.md"
    fileName: NewLocation
```

```meta-bind-button
label: New Guild or Group
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateGroup.md"
    fileName: NewGroup
```

```meta-bind-button
label: New Magic Item
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateMagicItem.md"
    fileName: NewMagicItem
```

```meta-bind-button
label: New Player
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplatePlayer.md"
    fileName: NewPlayer
```

`BUTTON[button_quest]` 

