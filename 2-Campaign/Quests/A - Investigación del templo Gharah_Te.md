---
questObtained: 2025-06-15T00:00:00-06:00
questStatus: In Progress
questGiver: clériga Ithira Vonn
questLocationObtained: Thalmyr (Varkass)
questSessionObtained: "[[5-Session Journals/0. Llegada a Thalmyr.md|0. Llegada a Thalmyr]]"
questNotes: Investigar la falta de respuesta del templo Gharah'Te a las afueras de Sazseki, en el estado de Varkass.
questLootAvail: Nota con lore
questLookEarned: CX-053
NoteIcon: quest
obsidianUIMode: preview
tags:
  - quest
---

# `=this.file.name`

> [!infobox]+
> # `=this.file.name`
> ## Quest Details
> Type |  Stat |
> ---|---|
> Date Obtained | `INPUT[datePicker:questObtained]` |
> Status | `INPUT[inlineSelect(option(Not Started), option(In Progress), option(Complete)):questStatus]` |
> Quest Giver | `INPUT[suggester(optionQuery(#npc)):questGiver]` |
> Quest Location | `INPUT[suggester(optionQuery(#Category/Settlement)):questLocationObtained]` |
> Session Obtained | `INPUT[suggester(optionQuery(#journal)):questSessionObtained]` |
> Available Loot | `INPUT[suggester(optionQuery(#item)):questLootAvail]` |
> Acquired Loot | `INPUT[suggester(optionQuery(#item)):questLookEarned]` |

> **"El templo de _Gharah'Tel_, ubicado en las afueras de [[Sazseki (Varkass)]], no ha enviado señales ni comunicaciones en cinco días. Ni humo, ni mensajes rituales, ni vuelos de corceles alados. Esto... no es común."**

La clériga Ithira Vonn desenrolla un **pergamino grueso**, con bordes decorados en tinta azul, y lo extiende sobre la mesa con cuidado reverente. Señala con una fina vara de bronce el puerto de Thalmyr, y traza lentamente un recorrido con la punta.

> **"Desde estas costas marcadas por la sal y la historia, el sendero más sabio desciende hacia el sur, donde el murmullo del mar aún acompaña los pasos. Tras unas horas de viaje encontrarán _Delinok_, hermana menor de este puerto, con gentes toscas pero generosas, forjadas por la pesca y el comercio de altura."**

Mueve la vara hacia el interior del mapa.

> **"Desde allí, el camino se adentra hacia _Ykorteli_, un cruce de mercaderes y voces extranjeras, donde los trueques hablan más que las palabras. No es una tierra de reposo, pero sí de tránsito."**

> **"Más adelante, el sendero los lleva a través del corazón del campo, cruzando el humilde asentamiento de _Aslan_. Son granjeros y pastores, más cerca de la tierra que del oro, pero sus muros saben proteger al viajero cansado."**

Se detiene un instante en un punto más al oeste.

> **"En _Kesenkay_, la hospitalidad se ofrece con pan y pólvora. Es un pueblo mercante, de raíces viejas y ánimos alertas. Allí podrán reabastecerse, descansar… y decidir si desean continuar."**

Su vara marca el punto final, más al suroeste.

> **"Finalmente, alcanzarán _Sazseki_, donde el templo de _Gharah’Tel_ reposa entre humedales y cantos de aves sagradas. O al menos... así era. Hoy, sus cantos han cesado."**

Ithira deja la vara a un lado, sus ojos ahora serios.

> **"Hay, sin embargo, otra ruta. Más breve, más densa, más incierta."**  
> **"Atravesando los bosques del sur, desde las afueras de Thalmyr hasta Kesenkay, pueden ahorrar medio día de camino. Pero los árboles de esas tierras no siempre susurran cosas buenas. Hay cosas que caminan cuando la luna no las ve."**

Les mira, con un dejo de respeto.

> **"Ambos caminos llevan al mismo final. Uno los prueba en paciencia. El otro, en valor."**

Enrolla el mapa con suavidad y lo entrega a quien parezca más atento del grupo.

> **"Decidan con sabiduría. La Llama del Equilibrio no enciende dos veces la misma antorcha."**

### 🗺️ **Ruta hacia Sazseki** – _Tabla de Asentamientos_

|Nombre|Tipo de Lugar|Población|Descripción Breve|Observaciones|
|---|---|---|---|---|
|**Thalmyr**|Ciudad portuaria|—|Puerto mayor de Varkass; punto de partida de la misión.|Oficinas del clero, aduana y punto de entrada oficial.|
|**Delinok**|Ciudad costera|9,187|Hermana menor de Thalmyr, dedicada a la pesca y pequeño comercio marítimo.|Lugar seguro para reponer víveres. Posadas modestas.|
|**Ykorteli**|Pueblo mercader|10,402|Cruce de caminos; bullicioso y lleno de forasteros y trueques.|Algunos mercaderes podrían ofrecer rumores o mercancías útiles.|
|**Aslan**|Asentamiento rural|1,624|Campesinado sencillo y aislado, dedicado a la agricultura.|Lugar de paso; hospitalidad básica.|
|**Kesenkay**|Pueblo mercante|9,509|Bastión comercial más desarrollado, punto de reabastecimiento antes del final.|Último punto seguro del camino. Guardias atentos, muchas tiendas.|
|**Sazseki**|Poblado religioso|2,685|Dedicado al culto y a la meditación, hogar del templo de Gharah’Tel.|El templo ha dejado de responder. Pueblo actualmente en silencio o tensión.|

### 🧭 Rutas posibles

- **Camino Seguro**: Thalmyr → Delinok → Ykorteli → Aslan → Kesenkay → Sazseki
    
    - ⏳ Más largo (5 días aprox.)
        
    - ✅ Más seguro
        
    - 🛌 Posadas y víveres en cada etapa
        
- **Camino Rápido (y Riesgoso)**: Thalmyr → Bosques del Oeste → Kesenkay → Sazseki
    
    - ⏳ Más corto (3½ días aprox.)
        
    - ⚠️ Riesgo alto de encuentros salvajes o desvíos
        
    - 🌲 Terreno boscoso, poco transitado y sin protección
        


### Quest Objective

- Investigar lo ocurrido en el templo de Gharah'Te
- Reportar lo encontrado en alguna oficina local del clero en Varkass.

### Rewards

- Token de derecho de paso (permite el libre tránsito por Varkass a quien lo porta, ya sea individuo o grupo).
- 100 monedas de plata.
- +1 en afinidad con el clero de **Vharun**, navegante de las mareas.
