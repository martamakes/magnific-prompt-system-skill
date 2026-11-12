# Estilo: AUTOR-MOTIVO (tema, motivo y primer plano)

Tipo: enfoque
Alcance: piezas narrativas o de marca con intención de significado (cortos, videoclips, piezas con personaje y tema) cuyo desglose cuenta la acción pero no dice de qué trata. No se aplica a anuncios de impacto rápido (ahí, `references/estilos/redes.md`) ni a piezas que funcionan sin una capa de significado añadida.

Borrador sin validar. Todo es `propuesta` hasta que un caso de prueba ejecutado diga otra cosa. Las capacidades del modelo siguen sin verificar (`references/modelos.md`).

<!-- Adaptado a la plantilla en #3. Se conserva el contenido anterior reordenado. Lo que antes eran condiciones («aparece al menos tres veces», «el final devuelve el motivo del inicio») pasa a preguntas y recursos posibles. -->

## Qué ayuda a revisar
Que el desglose diga de qué trata la pieza: si el tema cabe en una frase, si hay un objeto, imagen o gesto que lleve significado, si el primer plano presenta personaje, lugar y tono, si los lugares sirven al tema y si las pausas y el sonido tienen función. Entra en `review` tras el diagnóstico del desglose. Un tema que se desprende de la acción sin motivo repetido es un resultado válido.

## Cómo orientar una propuesta
Se parte del tema (una frase) y se busca el recurso más simple que lo haga visible. Un motivo bien elegido pesa más que varios; no se añaden símbolos por acumulación.
- **Planos y composición.** El primer plano puede presentar personaje, lugar y tono a la vez, o plantear una pregunta. Para el arranque, hasta 3 opciones distintas, solo si el actual no cumple esa función: detalle que plantea una pregunta · imagen que resume el tema · gesto cotidiano que se cargará de sentido. Indica qué información de personaje, lugar y tono lleva cada una.
- **Cámara.** Un plano fijo sirve para tensión, intimidad o lectura de la escenografía (movimiento solo dentro del encuadre, entrada y salida de personajes, foco que pasa de un sujeto a otro). El movimiento de cámara se justifica donde lo hay.
- **Luz, color y lugar.** El mismo lugar con otra luz, o un color asociado a un personaje, puede marcar el cambio de estado sin añadir objetos. Los lugares se eligen porque sirven al tema, no por ser intercambiables.
- **Puesta en escena y motivo.** Un objeto, forma o gesto que vuelve y cambia de sentido (mismo símbolo, tratamiento distinto según el estado del personaje). Cuántas veces aparezca lo decide la pieza: dos apariciones pueden bastar si la segunda cambia el sentido; más sirven cuando la duración lo permite y cada una añade algo. Debe verse igual entre planos: pide continuidad de objeto.
- **Montaje.** Corte entre fijos para ritmo, mantener el plano para tensión, repetir un encuadre para anticipar. Devolver al final el motivo del inicio con otro sentido es una opción, no la única forma de cerrar.
- **Sonido.** Música en contraste con la imagen, silencio o sonido que anticipa, con intención. Distingue lo escrito en el desglose de lo que se espera que el espectador perciba.
- **Variantes.** Variantes que cambien una sola decisión (el motivo, el lugar o el primer plano), diciendo qué se quiere aprender. No afirmar que una variante «funciona» sin haberla generado y revisado.

## Preguntas de análisis
Son preguntas para orientar la revisión, no condiciones de aprobado.
1. ¿Se puede decir el tema en una frase? Si no, ¿qué parte de la pieza lo está diciendo ya?
2. ¿Hay un objeto, imagen o gesto que lleve significado? Si lo hay, ¿cambia de sentido a lo largo de la pieza o es decoración? ¿Cuántas veces hace falta que aparezca para que se lea?
3. ¿El motivo varía según el estado del personaje (mismo símbolo, tratamiento distinto)?
4. ¿El primer plano presenta personaje, lugar y tono a la vez, o plantea una pregunta?
5. ¿Cada lugar elegido sirve al tema, o es intercambiable?
6. ¿Hay planos fijos o pausas con función (tensión, intimidad, lectura de la escenografía)? ¿Se justifica el movimiento de cámara donde lo hay?
7. ¿Cómo cierra la pieza respecto al inicio? ¿Necesita devolver el motivo, o cierra bien de otro modo?
8. ¿La música o el sonido refuerza el tema, o contrasta con la imagen con intención?
9. ¿Qué está escrito en el desglose y qué se espera que perciba el espectador?

## Recursos posibles y cuándo sirven
Describe resultado visible, no etiquetas.

| Familia | Recurso | Cuándo sirve | Cuándo no |
|---|---|---|---|
| Motivo | objeto repetido · forma recurrente · color asociado a un personaje · sonido que vuelve | el tema necesita un soporte tangible que cambie de sentido | si el tema ya se lee en la acción; si el objeto es pequeño, con texto o detalle (falla en vídeo) |
| Variación | mismo objeto en distinto estado · mismo encuadre con otro significado · mismo lugar con otra luz | mostrar un cambio de estado sin diálogo ni explicación | si el cambio no existe en la historia |
| Primer plano | detalle que plantea una pregunta · imagen que resume el tema · mirada a cámara · gesto cotidiano cargado | el desglose abre sin decir tono, lugar o personaje | si la pieza ya abre con una acción que los presenta |
| Plano fijo | cámara bloqueada · movimiento solo dentro del encuadre · entrada y salida de personajes · foco que pasa de un sujeto a otro | tensión, intimidad, lectura de la escenografía | si nada cambia dentro del plano |
| Montaje | corte entre fijos para ritmo · mantener el plano para tensión · repetir un encuadre para anticipar | cuando el encuadre repetido aporta una lectura nueva | si repite sin variación y solo busca simetría |
| Cierre | devolver el motivo del inicio con otro sentido · cierre abierto · cortar en la reacción | el tema pide resolución simétrica / el tema pide ambigüedad | un cierre circular impuesto a una pieza que cierra bien de otro modo |
| Sonido | música en contraste con la imagen · silencio · sonido que anticipa | reforzar o complicar el tema con intención | si compite con diálogo o con el audio ya aprobado |

Ejemplo válido: «Plano fijo de la mesa de la cocina; una taza vacía en primer término. En el último plano, el mismo encuadre con la taza llena y otra persona sentada.»
Ejemplo no válido: «símbolos profundos con atmósfera de autor».

## Estado de las capacidades
Sin verificar. Mantener el mismo objeto reconocible entre planos, repetir un encuadre exacto o variar solo un detalle depende de las referencias y del modelo (`coherencia`, `prop-ref`, `location-ref`); no prometer una sola generación. Un plano fijo es más fácil de pedir que uno complejo, pero la estabilidad real está sin probar. Todo es `propuesta`; no hay capacidad verificada, y `references/modelos.md` no recoge nada específico para estos recursos.

## Riesgos de cliché o aplicación mecánica
- Aplicado sin criterio, el perfil lleva a meter un objeto simbólico en cada pieza, repetirlo un número fijo de veces y cerrar en círculo. El motivo explícito o forzado se lee como adorno; si no cambia de sentido, es decoración.
- Objetos pequeños, textos y símbolos detallados fallan con facilidad en vídeo; usar formas simples.
- Lo que se repite debe verse igual: el motivo exige continuidad de objeto entre planos.
- Demasiada intención de significado puede ralentizar piezas cortas; reservar pausas para donde sirvan.
- Situación que contradice el cliché: una pieza cuyo tema se entiende sin un objeto repetido tres veces y sin cierre circular. `review` debe respetarla y limitarse a problemas reales. Caso en `pruebas/autor-motivo.md`.

## Qué no debe imponer ni modificar
- Historia, diálogos, audio, destino, restricciones y decisiones aprobadas del dossier (`references/reglas.md`).
- No impone un motivo, un número de apariciones, un cierre circular ni símbolos nuevos.
- No añade objetos o texto a la pieza para «dar significado» sin señalarlo como `propuesta` y sin que el problema esté identificado.

## Fuentes y alcance de la evidencia
- Fuente: resúmenes propios de vídeos de análisis de StudioBinder (primeros planos, plano fijo, motivos); títulos y vídeos concretos no registrados · Localizador: pendiente — sin título ni código de tiempo no cuenta como consultada. No son documentación de ningún modelo.
- Etiquetas: no hay `[observado]` (ninguna obra concreta registrada) ni `[fuente explica]` atribuible mientras falte el localizador. Las preguntas, los recursos y los «cuándo sirve / cuándo no» son `[criterio propuesto]`, derivados de esos resúmenes y de lo que `review` necesita.
- Sin fuente para: número de apariciones de un motivo, función del cierre circular, eficacia de ningún recurso. No se afirman.
- Para completar: registrar título, autor y código de tiempo (mm:ss–mm:ss) de cada vídeo revisado, y marcar lo que cada uno explica.

## Caso de prueba
`pruebas/autor-motivo.md`: pieza cuyo tema se entiende sin tres apariciones de un objeto ni cierre circular. Su estado (diseñado o ejecutado) figura en el propio archivo.
