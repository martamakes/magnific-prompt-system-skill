# Ficha: Luz volumétrica

Alias: volumetric lighting, volumetric light, god rays (Wikipedia).
Familia: efecto atmosférico.
Estado: primera tanda. El estado de cada afirmación consta en «Fuente y localizador».

## Resultado visible
Haces de luz visibles en el aire: la luz se ve a sí misma atravesando el espacio, como un cono o rayos con volumen, porque hay partículas (bruma, niebla, humo, polvo) que la dispersan. Se reconoce por el haz visible, no por el nombre.

## Por qué se ve un haz en el aire
- Principio físico: la luz dispersada por partículas del medio hacia la cámara hace visible la iluminación del foco (Pharr, Jakob y Humphreys, §11.1). El haz se ve en el aire aunque no haya una superficie que lo refleje; sin partículas que lo dispersen, ese trayecto de luz no se ve.
- Representación en gráficos 3D: Wikipedia lo trata como técnica de infografía que modela el cono de luz como un volumen con un aerosol (niebla, polvo, humo, vapor). Es un método de representación, no la explicación física, y la ficha no desarrolla el renderizado.
- Condiciones propuestas para componer el ejemplo (síntesis propia, a partir de FilmDaft): que la luz tenga una dirección reconocible y un fondo menos brillante que la luz dispersada hacen más legible el haz del ejemplo. No se presentan como requisitos de cualquier efecto volumétrico: la fuente las da como comprobaciones prácticas, y aquí solo sirven para que el haz se lea en el ejemplo.

Cómo se produce el medio en un rodaje o en un render no es lo que describe el prompt y la ficha no lo desarrolla.

## Decisiones a concretar
- De dónde viene el haz y hacia dónde apunta; si es contraluz o luz lateral.
- Qué medio se ve en el aire (bruma fina, niebla densa, humo, polvo): FilmDaft los distingue por aspecto, con la bruma fina y pareja, la niebla más espesa y el humo con vetas y direccional.
- Cuánto se ve el haz: tenue o marcado, y cuánto del cuadro ocupa.
- Cuánto contraste con el fondo: en el ejemplo, un fondo más oscuro ayuda a que el haz se lea; es una decisión de legibilidad, no un requisito.
- Dureza de la luz y forma del haz (abierto, estrecho): las fuentes no la fijan.
- Color de la luz: no se fija.

## Se combina con · No confundir con
- Se combina con: luz de contorno (`references/recursos/iluminacion/luz-de-contorno.md`) o contraluz, luz de ventana (`references/recursos/iluminacion/luz-de-ventana.md`) con polvo o bruma visibles, clave baja (`references/recursos/iluminacion/clave-baja.md`) como fondo oscuro, luz dura (`references/recursos/iluminacion/luz-dura.md`).
- No confundir con: luz de persiana (`references/recursos/iluminacion/luz-de-persiana.md`) y luz moteada (`references/recursos/iluminacion/luz-moteada.md`), que son patrones de sombra proyectados sobre superficies; la volumétrica es el haz visto en el aire; luz suave (`references/recursos/iluminacion/luz-suave.md`), que no forma haces definidos.
- FilmDaft señala que puede aportar profundidad y dirección o bajar el contraste si se abusa: es una advertencia de esa fuente, no una propiedad. No se le atribuye ambiente ni emoción.

## Ejemplo descriptivo
Ejemplo propio, ilustrativo.
«Plano general. En un almacén con bruma ligera, un haz de luz entra desde una ventana alta y se ve atravesar el aire hasta el suelo; el fondo está oscuro y el haz destaca contra él.»

## Capacidad del modelo
Pendiente de comprobar. `references/modelos.md` no recoge control de iluminación. No prometer forma ni intensidad exactas del haz; describir el medio visible y el haz, no solo el nombre.

## Fuente y localizador
| Afirmación | Fuente | Localizador | Estado |
|---|---|---|---|
| La luz dispersada por partículas del medio hacia la cámara hace visible la iluminación del foco (pie de la Figura 11.1) | Matt Pharr, Wenzel Jakob y Greg Humphreys, *Physically Based Rendering*, 3.ª ed., §11.1 «Volume Scattering Processes» (pbr-book.org/3ed-2018) | introducción y pie de la Figura 11.1 | `[definición respaldada]` (fuente técnica; la sección no habla de rodaje ni de máquinas de bruma) |
| Luz visible en el aire porque partículas (bruma, niebla, humo, polvo) la dispersan; aspecto distinto de bruma, niebla y humo | Jan Sørup, FilmDaft (19-12-2025) | definición; «Choose haze, fog, or smoke» | `[definición respaldada]` (fuente secundaria) |
| Dirección y fondo menos brillante como ayuda de legibilidad del haz del ejemplo | FilmDaft, «How volumetric lighting works» | — | `[síntesis propia]`: condición de composición del ejemplo, no requisito general |
| «God rays»; cono de luz que atraviesa un aerosol (niebla, polvo, humo, vapor); término que parece provenir de la cinematografía | Wikipedia, «Volumetric lighting» (consultada en 2026) | introducción | `[definición respaldada]` (el artículo la trata como técnica de gráficos 3D; no explica la dispersión) |
| Procedimientos de rodaje o de renderizado | — | — | fuera del alcance de la ficha; no se desarrollan |
| Efectos sobre profundidad o contraste | FilmDaft, «What volumetric lighting changes in the frame» | — | cita de la fuente, no propiedad del recurso |
| Ejemplo | — | — | `[ejemplo propio]` |
| Respuesta del modelo a la luz volumétrica | — | — | `[capacidad pendiente]` |

Límite declarado: un texto técnico de renderizado (explica el principio físico, no el rodaje), una fuente secundaria de cine y un artículo de enciclopedia centrado en gráficos 3D; sin medidas de densidad ni intensidad.
