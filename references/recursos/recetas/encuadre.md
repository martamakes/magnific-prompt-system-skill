# Recetas de encuadre

Una receta combina fichas existentes y explica el resultado de la combinación. No es una ficha ni una técnica formalmente definida: los nombres compuestos son etiquetas descriptivas adoptadas por la biblioteca, tomadas de las listas originales aportadas al proyecto. Las fichas enlazadas respaldan los principios; la combinación concreta es propuesta de la biblioteca. Las recetas de iluminación (#24) reutilizan este formato.

## Formato de receta

Cada receta tiene estos apartados, en este orden y breves:

1. **Nombre.** Nombre en español y expresión original entre paréntesis.
2. **Combinación propuesta.** Qué fichas se juntan y qué resultado visible da la unión, en una o dos frases.
3. **Fichas que utiliza.** Enlaces a las fichas existentes. La receta no crea fichas.
4. **Principios respaldados / combinación propuesta.** Qué dicen las fichas (respaldado por ellas) y qué añade la biblioteca al juntarlas.
5. **Decisiones a concretar.** Lo que debe fijar quien escribe el prompt.
6. **Ejemplo descriptivo.** Ejemplo propio, ilustrativo.
7. **Límites y ambigüedades.** Lo que la combinación no resuelve, lo que la lista original no precisa y la capacidad del modelo.

Estados: `[principio respaldado por ficha]` · `[combinación propuesta]` (propuesta de la biblioteca, sin fuente que defina la combinación) · `[ejemplo propio]` · `[capacidad pendiente]`.

## Ejes que no hay que confundir

Las recetas de encuadre combinan decisiones de ejes distintos. Cada receta dice a qué eje pertenece cada ficha:

- **Posición de cámara:** dónde está (distancia al sujeto, altura).
- **Orientación:** hacia dónde mira (ángulo: picado, contrapicado, cenital).
- **Escala:** cuánto del sujeto llena el cuadro (primer plano, plano general).
- **Óptica:** campo de visión y proyección (gran angular, ojo de pez).

Acercar físicamente la cámara, cambiar la óptica y recortar la imagen son tres operaciones distintas. Acercar la cámara cambia la posición; usar un gran angular cambia la óptica; recortar cambia solo la escala. Que la perspectiva cambie con la posición y no con el recorte es síntesis propia, sin fuente en las fichas. Un prompt no controla la focal ni la distancia reales: describe el aspecto pedido.

---

## 1. Cenital con ojo de pez (Overhead fisheye)

**Combinación propuesta.** Orientación cenital (cámara sobre la vertical mirando hacia abajo) más óptica de ojo de pez (proyección no rectilínea de campo muy amplio): una vista desde arriba en la que las rectas del suelo y los bordes se curvan.

**Fichas.** `references/recursos/encuadre/plano-cenital.md` (orientación) · `references/recursos/encuadre/ojo-de-pez.md` (óptica).

**Principios respaldados / combinación propuesta.**
- `[principio respaldado por ficha]` Cenital: cámara directamente sobre la escena, mirando verticalmente hacia abajo. Ojo de pez: proyección no rectilínea, campo muy amplio, rectas curvadas.
- `[combinación propuesta]` Juntarlos da una escena entera vista desde arriba con la curvatura propia de la proyección. La ficha de ojo de pez ya cita las combinaciones con nombre propio como recetas y no las desarrolla.

**Decisiones a concretar.**
- Qué entra en el cuadro y a qué altura se imagina la cámara (posición).
- Si la imagen es circular (esquinas negras) o llena el cuadro.
- Qué rectas se curvan (suelo, paredes, bordes de una mesa) y que la curvatura siga una sola proyección.
- Dónde están las figuras: cerca del borde o del centro; la deformación afecta sobre todo a lo cercano a cámara y a los bordes.
- Orientación del conjunto en el cuadro.

**Ejemplo descriptivo.** Ejemplo propio, ilustrativo.
«Plano cenital con ojo de pez. La cámara, sobre la pista, mira recto hacia abajo: las líneas blancas del suelo se curvan hacia los bordes y los jugadores, pequeños, rodean el círculo central.»

**Límites y ambigüedades.**
- La entrada original no dice si «overhead» es cenital o aéreo; aquí se usa como cenital, que es como la ficha de cenital trata ese alias. El plano aéreo (`references/recursos/encuadre/plano-aereo.md`) se define por el medio, no por el ángulo.
- `[capacidad pendiente]` `references/modelos.md` no recoge el ojo de pez; no prometer curvatura, ángulo ni geometría exactos.

---

## 2. Primer plano con gran angular (Wide-angle close-up)

**Combinación propuesta.** Escala de primer plano (el sujeto llena el cuadro) más óptica de gran angular (campo amplio que agranda lo cercano): un sujeto muy cerca de la cámara, grande en el cuadro, con más entorno detrás que en un primer plano de óptica normal.

**Fichas.** `references/recursos/encuadre/primer-plano.md` (escala) · `references/recursos/encuadre/gran-angular.md` (óptica).

**Principios respaldados / combinación propuesta.**
- `[principio respaldado por ficha]` Primer plano: un sujeto llena el cuadro y el entorno apenas aparece. Gran angular: mucho entorno, lo cercano muy grande, lo moderadamente lejano pequeño; rostros cerca de cámara agrandan la parte más cercana.
- `[combinación propuesta]` Conseguir un primer plano con gran angular exige la cámara muy cerca del sujeto: la escala la fija la proximidad (posición) y el gran angular fija la perspectiva. Un primer plano recortado de una imagen amplia no tiene esa perspectiva. Ambas lecturas son síntesis propia.

**Decisiones a concretar.**
- Dónde corta el encuadre y cuánto aire queda.
- Cuánto entorno aparece detrás del sujeto: la combinación admite más entorno que un primer plano normal; lo declara quien escribe el prompt.
- Qué parte del sujeto queda más cerca de cámara y se agranda (nariz, manos, objeto).
- Si las rectas del entorno siguen rectas (gran angular rectilíneo) o se curvan (sería ojo de pez, otra receta).
- Cuánta deformación del rostro se acepta.

**Ejemplo descriptivo.** Ejemplo propio, ilustrativo.
«Primer plano con gran angular. La cámara, a un palmo de Lucía, encuadra su cara y las manos adelantadas, algo grandes; detrás, la calle se abre y los edificios se ven pequeños.»

**Límites y ambigüedades.**
- La ficha de gran angular tiene una sola fuente (Wikipedia, fotografía fija) y no describe la deformación de bordes en sujetos cercanos como efecto general.
- No se fija focal ni distancia numéricas.
- `[capacidad pendiente]` `references/modelos.md` no recoge control de la focal ni el gran angular. Rostros o manos que cambian de identidad por la cercanía son errores de generación, no el efecto buscado.

---

## 3. Primer plano con ojo de pez (Fisheye close-up)

**Combinación propuesta.** Escala de primer plano más óptica de ojo de pez: un sujeto muy cerca, con la deformación no rectilínea fuerte en lo cercano y en los bordes.

**Fichas.** `references/recursos/encuadre/primer-plano.md` (escala) · `references/recursos/encuadre/ojo-de-pez.md` (óptica).

**Principios respaldados / combinación propuesta.**
- `[principio respaldado por ficha]` Primer plano: sujeto llena el cuadro. Ojo de pez: rectas curvadas, centro abultado, lo cercano agrandado; con rostros y manos cerca, la deformación afecta a la identidad.
- `[combinación propuesta]` Es la combinación en que la deformación del ojo de pez recae sobre el propio sujeto. Se trata como una decisión de proyección buscada, no como un fallo.

**Decisiones a concretar.**
- Qué parte del sujeto queda en el centro abultado y cuál hacia el borde.
- Si la imagen es circular o llena el cuadro.
- Cuánto entorno aparece curvado alrededor.
- Cómo se mantienen la identidad y la anatomía: la curvatura debe seguir una sola proyección.
- Distancia a cámara: cuanto más cerca, más deformación (síntesis propia).

**Ejemplo descriptivo.** Ejemplo propio, ilustrativo.
«Primer plano con ojo de pez. La cámara, muy cerca de Mateo, abulta su nariz y su frente; las paredes de la habitación se curvan alrededor de su cara.»

**Límites y ambigüedades.**
- `references/estilos/redes.md` recomienda comprobar la identidad cuando el ojo de pez está sobre rostros y manos.
- La entrada original no dice si el ojo de pez es circular o de encuadre completo.
- `[capacidad pendiente]` ojo de pez sin confirmar en `references/modelos.md`.

---

## 4. Primer plano en picado (High-angle close-up)

**Combinación propuesta.** Escala de primer plano más orientación en picado (cámara más alta que el sujeto, mirando hacia abajo): el sujeto llena el cuadro visto desde arriba.

**Fichas.** `references/recursos/encuadre/primer-plano.md` (escala) · `references/recursos/encuadre/picado.md` (orientación).

**Principios respaldados / combinación propuesta.**
- `[principio respaldado por ficha]` Primer plano: sujeto llena el cuadro. Picado: cámara por encima del sujeto, mirando hacia abajo, con grados; no tiene por qué estar sobre su vertical.
- `[combinación propuesta]` La escala (cuánto llena el cuadro) y el ángulo (hacia dónde mira la cámara) son ejes independientes; la receta fija los dos. El fondo visible tras el sujeto es el plano inferior (suelo, mesa), pero en primer plano ocupa poco espacio.

**Decisiones a concretar.**
- Cuánto mira hacia abajo (leve o pronunciado).
- Dónde corta el encuadre y cuánto aire queda.
- Qué se ve detrás del sujeto, si algo.
- Altura de la cámara declarada, si importa (decisión aparte, sin ficha todavía).
- Qué parte del sujeto queda más cerca (frente, hombros).

**Ejemplo descriptivo.** Ejemplo propio, ilustrativo.
«Primer plano en picado. La cámara, por encima de Ana, mira hacia abajo: su rostro, levantado, llena el cuadro y detrás solo se ve el suelo.»

**Límites y ambigüedades.**
- No es un plano cenital: si la cámara está directamente sobre el sujeto y mira en vertical, es otra ficha (`references/recursos/encuadre/plano-cenital.md`).
- No se atribuye ningún significado al ángulo.
- `[capacidad pendiente]` `references/modelos.md` no recoge ángulos de cámara.

---

## 5. Primer plano en contrapicado (Low-angle close-up)

**Combinación propuesta.** Escala de primer plano más orientación en contrapicado (cámara por debajo del sujeto, mirando hacia arriba): el sujeto llena el cuadro visto desde abajo.

**Fichas.** `references/recursos/encuadre/primer-plano.md` (escala) · `references/recursos/encuadre/contrapicado.md` (orientación).

**Principios respaldados / combinación propuesta.**
- `[principio respaldado por ficha]` Primer plano: sujeto llena el cuadro. Contrapicado: cámara por debajo del sujeto, mirando hacia arriba, con grados.
- `[combinación propuesta]` Igual que el picado, la receta fija a la vez escala y ángulo. El fondo visible es lo que hay por encima (techo, cielo).

**Decisiones a concretar.**
- Cuánto mira hacia arriba (leve o pronunciado).
- Dónde corta el encuadre y cuánto aire queda.
- Qué se ve detrás del sujeto, si algo (techo, cielo).
- Altura de la cámara declarada, si importa (decisión aparte, sin ficha todavía).
- Qué parte del sujeto queda más cerca (barbilla, nariz).

**Ejemplo descriptivo.** Ejemplo propio, ilustrativo.
«Primer plano en contrapicado. La cámara, por debajo de Clara, mira hacia arriba: su rostro llena el cuadro y detrás solo se ve el techo.»

**Límites y ambigüedades.**
- No confundir con el plano a ras de suelo (`references/recursos/encuadre/plano-a-ras-de-suelo.md`) ni con la vista de gusano (`references/recursos/encuadre/vista-de-gusano.md`), entradas distintas.
- La fuente de la ficha de contrapicado asocia el ángulo con un sujeto poderoso o amenazante; depende de la escena y no se adopta como propiedad.
- `[capacidad pendiente]` `references/modelos.md` no recoge ángulos de cámara.
