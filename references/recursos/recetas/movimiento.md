# Recetas de movimiento y recorrido

Usa el formato de `recetas/encuadre.md` (nombre, combinación propuesta, fichas, principios respaldados / combinación propuesta, decisiones, ejemplo, límites; mismos estados). Una receta combina fichas existentes y explica el resultado; no es una ficha ni una técnica formalmente definida. Los nombres compuestos son etiquetas descriptivas adoptadas por la biblioteca, tomadas de la fila «Recorrido» de `references/estilos/redes.md`. Las fichas respaldan sus componentes; no demuestran que un modelo ejecute la combinación.

## Alcance de este archivo

Contiene dos recetas, A9 y A10: las entradas «atravesar un objeto» y «de macro a paisaje» de la fila «Recorrido» de `references/estilos/redes.md`. A11 («entrar por una pantalla y salir a otro espacio») no tiene receta: ver «Pendiente».

Cada receta es **una versión concreta propuesta** de una entrada cuyo texto original es ambiguo. Ninguna afirma resolver el significado original.

---

## 1. Atravesar una abertura (atravesar un objeto)

**Combinación propuesta.** Una cámara que avanza en un solo plano hacia una abertura de un objeto (un hueco que ya existe: cerradura, ventana, puerta entreabierta, arco) y la cruza, de modo que el borde de la abertura tapa parte del cuadro antes de pasar y, al otro lado, aparece otro espacio.

**Versión elegida y lo que no cubre.** La entrada original dice «atravesar un objeto» y no distingue entre dos cosas:
- **Pasar por un hueco** del objeto (versión de esta receta, propuesta).
- **Atravesar la materia** del objeto como si no la hubiera. Esta receta solo desarrolla el paso por una abertura; no desarrolla atravesar materia.

**Fichas que utiliza.** `references/recursos/movimiento/acercamiento.md` (movimiento) · `references/recursos/encuadre/oclusion-en-primer-termino.md` (el borde de la abertura como elemento de primer término).

**Principios respaldados / combinación propuesta.**
- `[principio respaldado por ficha]` Acercamiento: la cámara se desplaza físicamente hacia delante; no es un cambio de focal, y el cambio de posición altera la relación entre lo cercano y lo lejano. Oclusión en primer término: un elemento entre la cámara y el sujeto tapa parte del cuadro; la ficha pide decidir qué queda visible.
- `[combinación propuesta]` Leer el borde de la abertura como ese elemento de primer término, y el avance de la cámara como el movimiento que lo cruza. Las fichas no tratan atravesar aberturas.

**Decisiones a concretar.**
- **Trayectoria:** recta o con curva suave; si la cámara se mantiene en un eje o corrige la altura. Una caída o un descenso no se da por incluido (A5 sigue abierta).
- **Abertura:** qué es, su tamaño respecto a la cámara y si deja ver algo al otro lado antes de cruzarla.
- **Relación con el sujeto:** qué hay al otro lado (un espacio, un personaje, un objeto) y si el sujeto está ya visible o aparece tras el cruce.
- Qué escala tiene el espacio de llegada y qué debe quedar legible al salir.
- Velocidad del avance y qué ocurre cuando el borde cubre el cuadro.

**Ejemplo descriptivo.** Ejemplo propio, ilustrativo.
«Acercamiento lento hacia una puerta entreabierta. La cámara avanza en línea recta y el marco oscuro de la puerta ocupa los bordes del cuadro; al cruzar la rendija, el cuadro se abre a un salón iluminado donde una mujer espera junto a la ventana.»

**Límites y ambigüedades.**
- La fila «Recorrido» de `redes.md` da el ejemplo de la cerradura, que baja desde un cenital; esta versión no incluye ese descenso, así que no coincide con él.
- `redes.md` avisa de que atravesar objetos puede romper la continuidad entre planos y exigir varias generaciones; no se promete continuidad, geometría ni que la abertura conserve su forma al cruzarla.
- Las fichas no dicen que un mismo plano pueda pasar de un lado a otro sin corte; si el modelo no lo mantiene, la unión sería otra construcción (ver «Pendiente»).
- `[capacidad pendiente]` `references/modelos.md` no confirma que el modelo atraviese una abertura ni que respete trayectoria, tamaño o el espacio de llegada.

---

## 2. Del detalle al espacio abierto (de macro a paisaje)

**Combinación propuesta.** Un plano continuo que empieza con aspecto de plano macro sobre un detalle y retrocede hasta mostrar el espacio en que se encuentra, con aspecto de plano general o más abierto.

**Versión elegida y lo que no cubre.** La entrada original habla de «cambio de escala» y no dice cómo se hace. Esta receta propone **un retroceso de cámara**; no es la única forma. No se da por incluido un zoom (cambio de focal) ni un corte entre dos planos.

**Tres cosas que no se confunden:**
- **Escala de plano** (qué parte llena el cuadro): macro al principio, general al final.
- **Posición de cámara** (dónde está): se aleja, lo que hace la ficha de retroceso.
- **Focal** (óptica): no se pide cambiarla. Que la escala cambie no implica que la focal cambie ni que la cámara se mueva.

**Fichas que utiliza.** `references/recursos/encuadre/plano-macro.md` (escala de partida) · `references/recursos/encuadre/plano-general.md` (escala de llegada) · `references/recursos/movimiento/retroceso.md` (movimiento que une las dos).

**Principios respaldados / combinación propuesta.**
- `[principio respaldado por ficha]` Plano macro: aspecto de un objeto o parte pequeña que llena el cuadro con mucho detalle; en una imagen generada describe el aspecto pedido, no una ampliación medida. Plano general: el sujeto y su entorno se leen a la vez; la ficha tiene como decisión mostrar un gran plano general cuando el sujeto es ya pequeño frente al espacio. Retroceso: la cámara se aleja, la distancia aumenta y entra más espacio alrededor.
- `[combinación propuesta]` Unir esas dos escalas con un retroceso continuo. Que la imagen de partida y la de llegada puedan unirse en un solo plano es una suposición de la receta; las fichas no lo respaldan.

**Decisiones a concretar.**
- **Qué detalle** abre el plano (una textura, un ojo, un objeto pequeño) y qué espacio revela al alejarse; el espacio debe poder contenerlo.
- **«Paisaje»:** la receta pide el espacio abierto en el que cae el detalle. El plano general de la ficha muestra un sujeto en su entorno; si el espacio debe dominar al sujeto, es la decisión de gran plano general de esa ficha, no una escala nueva.
- Qué queda nítido al principio y al final (el enfoque cambia al alejarse y no está garantizado).
- Velocidad del retroceso y si el recorrido se hace en un solo plano o se divide por montaje.
- Luz sobre el detalle y sobre el espacio de llegada, si hay que coordinarlas.

**Ejemplo descriptivo.** Ejemplo propio, ilustrativo.
«Retroceso lento desde un plano macro. La cámara empieza sobre una gota de rocío en una hoja; al retroceder, la hoja, la planta y el prado entran en el cuadro hasta quedar una mujer pequeña, de pie, al fondo del valle.»

**Límites y ambigüedades.**
- Las fichas no dicen que el recorrido entre un macro y un general pueda hacerse en un plano continuo con geometría coherente. `redes.md` lista los «cambios extremos de escala» como «sin evidencia» y recomienda prever solución por montaje; esta receta no resuelve ese riesgo.
- La definición técnica de macro (ampliación ≥ 1:1) no es comprobable en una imagen generada; aquí cuenta solo el aspecto.
- `[capacidad pendiente]` `references/modelos.md` no recoge que el modelo mantenga un retroceso continuo de ese alcance, ni la coherencia entre detalle y espacio, ni el enfoque a lo largo del recorrido.

---

## Pendiente

**A11 · entrar por una pantalla y salir a otro espacio: sin receta.** No se ha delimitado e implementado una versión de A11 con los recursos existentes; permanece pendiente.

Dependencias de las versiones consideradas (no son las únicas construcciones posibles):
- **Cámara continua** que cruza una pantalla visible: la receta 1 solo desarrolla el paso por una abertura, y no está establecido que una pantalla se comporte como tal. Esta versión no queda delimitada con las fichas actuales.
- **Dos planos unidos** (uno en la pantalla, otro en el espacio de llegada): necesitan una ficha de unión entre planos. Las opciones propuestas en M5 son **alternativas entre sí**, no requisitos acumulativos: corte por coincidencia (A12) **o** unión por oclusión (A13). Ninguna de las dos fichas existe.
- No se sustituye una dependencia real con instrucciones improvisadas dentro de la receta. `references/recursos/iluminacion/luz-de-pantalla.md` no se enlaza: su iluminación no forma parte de ningún tratamiento delimitado aquí.
- No se crea una versión nueva de A11 en esta entrega.
