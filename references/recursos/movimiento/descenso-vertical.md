# Ficha: Descenso vertical

Alias: pedestal down (Videomaker, para el movimiento vertical de la cámara hacia abajo). «Caída» **no** se declara alias: es el término de la entrada A5 de `references/estilos/redes.md`, que las fuentes no respaldan (ver «Entrada A5 abierta»).
Familia: desplazamiento de cámara.
Estado: primera tanda. Esta ficha documenta una **interpretación candidata** de la entrada A5 «caída»; no la resuelve. El estado de cada afirmación consta en «Fuente y localizador».

## Resultado visible
Lo que sí está respaldado es el **descenso vertical de la cámara**: su posición pasa de más alta a más baja durante el plano, sin que cambie hacia dónde mira. Que la «caída» de `references/estilos/redes.md` sea exactamente eso no consta; esta ficha describe solo el descenso, y las demás lecturas posibles se separan abajo.

## Entrada A5 abierta
La entrada original dice solo «caída», en la lista de la fila «Movimiento» de `references/estilos/redes.md`; no la define. El único contexto del repositorio es un ejemplo del propio perfil: «La cámara desciende desde un cenital, atraviesa el hueco de una cerradura…», que describe un descenso, pero no llama «caída» a ese descenso. Tres lecturas posibles:
1. **Inverso de la elevación**: descenso vertical de la cámara (pedestal hacia abajo). Es el único movimiento de esa familia que las fuentes consultadas definen (Videomaker: mover la cámara arriba o abajo).
2. **Descenso brusco o caída libre**: una cámara que baja con aceleración, como si cayera. Ninguna fuente fiable consultada lo define como técnica de cámara ni lo nombra «caída»; la búsqueda solo devolvió un glosario de prompts de IA con una definición propia («falling»: cámara en caída libre), cuya página no se leyó y que no se adopta.
3. **Inclinación hacia abajo (tilt down)**: la cámara gira el objetivo hacia abajo sin moverse. Es otro movimiento, no un descenso (Videomaker, «Tilt»).

La ficha **no** declara que «caída» sea ninguna de las tres y no sustituye a la entrada original. Para el prompt, hace falta decir qué se quiere (ver decisiones) en lugar de escribir solo «caída».

## Qué es y qué no es
- Es, en lo respaldado, un **desplazamiento vertical hacia abajo** de la cámara; el resto (brusquedad, caída libre) queda como decisión que declara quien escribe el prompt.
- No es **inclinar la cámara hacia abajo** (tilt down); no es un ángulo **picado** o **cenital** (`references/recursos/encuadre/picado.md`, `references/recursos/encuadre/plano-cenital.md`), que describen hacia dónde mira la cámara.
- No es la **caída de un sujeto u objeto**: eso es movimiento del sujeto, no de la cámara.
- No es el inverso garantizado de la elevación (`references/recursos/movimiento/elevacion.md`): la lectura 1 lo trata como tal, pero la entrada original no lo dice. Ambas fichas delimitan el movimiento vertical simple.

## Decisiones a concretar
- Si se pide un descenso controlado (lectura 1) o una caída brusca (lectura 2); si se pide lo segundo, declararlo con palabras («cae con aceleración», «baja de golpe»), no con el nombre solo.
- Altura inicial y altura final; si termina cerca del suelo, de un objeto o de un espacio nuevo.
- Si la cámara mantiene hacia dónde mira o se reorienta al bajar: la ficha delimita el descenso vertical simple; si se combina con una inclinación hay dos componentes (descenso y tilt), cada uno con su decisión.
- Velocidad y recorrido.
- Si hay un efecto de impacto o parada al final: es una decisión de puesta en escena, no está en las fuentes.

## Se combina con · No confundir con
- Se combina con: plano cenital (`references/recursos/encuadre/plano-cenital.md`) como encuadre de partida, según el ejemplo del perfil de redes; plano macro (`references/recursos/encuadre/plano-macro.md`) o primer plano (`references/recursos/encuadre/primer-plano.md`) como llegada.
- No confundir con: inclinación hacia abajo (tilt, sin ficha); picado (ángulo); elevación (`references/recursos/movimiento/elevacion.md`); la entrada «caída» (A5, abierta); caída de un sujeto; atravesar un objeto (entrada de recorrido, otro bloque).
- No se asigna emoción ni significado.

## Ejemplo descriptivo
Ejemplo propio, ilustrativo, de la lectura 1 (descenso controlado), no de la lectura 2.
«Descenso lento de la cámara. Empieza por encima de una mesa y baja en vertical, siempre mirando al frente, hasta quedar a ras de la superficie, entre las tazas.»

## Capacidad del modelo
Pendiente de comprobar. `references/modelos.md` no nombra ningún valor del catálogo de Seedance 2.0 que corresponda al descenso vertical ni a la caída (solo se citan cuatro de los 52 valores); no se infiere ninguno. No prometer ni brusquedad ni altura concretas.

## Fuente y localizador
| Afirmación | Fuente | Localizador | Estado |
|---|---|---|---|
| Pedestal: mover la cámara arriba o abajo sin cambiar su eje vertical ni horizontal | Kyle Cassidy, «Camera movement: 11 techniques you should master», Videomaker (sin fecha visible) | apartado «Pedestal» | `[definición respaldada]` (fuente secundaria): respalda el descenso vertical, no el nombre «caída» |
| Tilt: mover el objetivo arriba o abajo; distinto del pedestal | Videomaker, mismo artículo | apartado «Tilt» | `[definición respaldada]` |
| La entrada «caída» no está definida en el repositorio; su único contexto es un ejemplo de descenso | `references/estilos/redes.md` | fila «Movimiento»; ejemplo válido | hecho del repositorio, no fuente externa |
| «Caída» como término de cámara | — | — | **No consta en la documentación consultada** (búsqueda estándar sin resultados fiables) |
| Un glosario de prompts de IA define «falling» como caída libre de cámara | resultado de búsqueda (página no leída) | — | incidencia de investigación: no adoptado |
| Documentar la lectura 1 como interpretación candidata y única que la ficha describe | entrada «caída» (A5) de la fila «Movimiento» de `references/estilos/redes.md`; interpretación abierta, no resuelve la entrada original | — | `[síntesis propia]` |
| Ejemplo | — | — | `[ejemplo propio]` |
| Respuesta del modelo a la caída | — | — | `[capacidad pendiente]` |

Límite declarado: una sola fuente secundaria respalda el descenso vertical; ninguna define «caída». La entrada A5 queda abierta y no se resuelve por semejanza de nombre.
