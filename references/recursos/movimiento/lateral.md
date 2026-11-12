# Ficha: Lateral

Alias: truck, trucking (Videomaker; Wikipedia). `truckLeft` solo como valor de un modelo (ver «Capacidad del modelo»), no como alias.
Familia: desplazamiento de cámara.
Estado: primera tanda. El estado de cada afirmación consta en «Fuente y localizador».

## Resultado visible
La cámara se desplaza de lado, a la izquierda o a la derecha del sujeto, manteniendo su orientación: el cuadro recorre la escena en horizontal y los elementos cercanos se desplazan por el cuadro más deprisa que los lejanos. Cambia la posición de la cámara, no hacia dónde mira.

## Qué es y qué no es
- Es **desplazamiento de la cámara hacia un lado** (truck). Videomaker lo define como mover la cámara físicamente hacia la izquierda o la derecha manteniendo la relación perpendicular; Wikipedia («Tracking shot») lo recoge como la cámara que se mueve a izquierda o derecha respecto al sujeto.
- **No es una panorámica (pan).** En la panorámica la cámara gira sobre su eje y solo se mueve el objetivo; en el truck se mueve la cámara entera (Videomaker). No hay ficha de panorámica.
- **No es una vista lateral del sujeto.** «Lateral» también puede significar ver al sujeto de lado; eso es la orientación del sujeto respecto a la cámara y tiene su ficha (`references/recursos/encuadre/sujeto-de-perfil.md`). Esta ficha solo cubre el desplazamiento. La entrada original aparece en la fila «Movimiento» de `references/estilos/redes.md`, junto a otros movimientos, lo que sugiere desplazamiento, pero no lo dice: lectura adoptada por la biblioteca (síntesis propia).
- No es el **seguimiento**: en el seguimiento la cámara acompaña a un sujeto que se mueve (Wikipedia, «Tracking shot»); aquí la cámara se mueve de lado, con el sujeto quieto o no. La ficha de seguimiento es de otro bloque.
- No es el **movimiento del sujeto**: un sujeto que cruza el cuadro ante una cámara quieta no es un desplazamiento lateral de cámara.

## Decisiones a concretar
- Dirección: izquierda o derecha.
- Velocidad y recorrido: cuánto se desplaza.
- Distancia constante o variable respecto al sujeto o a la escena durante el desplazamiento.
- Si la cámara mantiene la orientación (truck) o gira además (movimiento combinado, que no es esta ficha).
- Qué cruza o qué se descubre al desplazarse (obstáculos en primer término, personajes, paredes).
- Si el sujeto está quieto o se mueve.

## Se combina con · No confundir con
- Se combina con: cualquier escala de las fichas de encuadre (`references/recursos/encuadre/plano-medio.md`, `references/recursos/encuadre/plano-general.md`); oclusión en primer término (`references/recursos/encuadre/oclusion-en-primer-termino.md`) cuando hay elementos que cruzan el cuadro; cámara en mano (`references/recursos/movimiento/camara-en-mano.md`).
- No confundir con: panorámica (pan, sin ficha); sujeto de perfil (`references/recursos/encuadre/sujeto-de-perfil.md`); seguimiento; cámara fija (`references/recursos/movimiento/camara-fija.md`); acercamiento y retroceso (`references/recursos/movimiento/acercamiento.md`, `references/recursos/movimiento/retroceso.md`), que son movimientos hacia el sujeto o desde él.
- No se asigna emoción ni significado al desplazamiento lateral.

## Ejemplo descriptivo
Ejemplo propio, ilustrativo.
«Desplazamiento lateral hacia la derecha. La cámara se mueve despacio de lado, paralela a la barra de un bar, y va pasando ante cada cliente sentado; no gira, solo se desplaza.»

## Capacidad del modelo
Pendiente de comprobar. `references/modelos.md` (Seedance 2.0, fila «Movimiento de cámara») nombra el valor literal `truckLeft`: correspondencia específica de ese modelo **sin verificar**. Que sea un desplazamiento hacia la izquierda y no una vista lateral o un giro no está probado; el nombre del valor no prueba qué hace el modelo. La dirección derecha no tiene valor nombrado en el repositorio y no se infiere. Describir dirección y qué debe cruzarse.

## Fuente y localizador
| Afirmación | Fuente | Localizador | Estado |
|---|---|---|---|
| Truck: mover la cámara físicamente a un lado manteniendo su relación perpendicular; distinto del pan, en el que solo gira el objetivo | Kyle Cassidy, «Camera movement: 11 techniques you should master», Videomaker (sin fecha visible) | apartado «Truck» | `[definición respaldada]` (fuente secundaria) |
| Trucking: la cámara se mueve a izquierda o derecha respecto al sujeto | Wikipedia, «Tracking shot» (consultada en 2026) | apartado «Terminology» | `[definición respaldada]` (el artículo lo llama término menos común) |
| Tracking shot: la cámara sigue hacia atrás, hacia delante o se mueve junto al sujeto | Wikipedia, «Tracking shot» | introducción | `[definición respaldada]` (para distinguir el seguimiento) |
| Vista lateral del sujeto como entrada aparte | `references/recursos/encuadre/sujeto-de-perfil.md` | ficha | `[definición respaldada]` por esa ficha |
| Adoptar «lateral» como desplazamiento y no como vista de lado | entrada «lateral» (A7) de la fila «Movimiento» de `references/estilos/redes.md` | — | `[síntesis propia]`: la entrada original no lo dice |
| Paralaje (lo cercano se mueve más deprisa en el cuadro que lo lejano) | — | — | `[síntesis propia]`: sin fuente consultada |
| Ejemplo | — | — | `[ejemplo propio]` |
| Respuesta del modelo a `truckLeft` o al desplazamiento lateral | `references/modelos.md` | fila «Movimiento de cámara» | `[capacidad pendiente]` |

Límite declarado: una fuente secundaria de cine y un artículo de enciclopedia; ninguna es manual técnico. «Lateral» como nombre en español no consta en ninguna fuente consultada.
