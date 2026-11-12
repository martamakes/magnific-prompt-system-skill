# Ficha: Órbita

Alias: ninguno declarado. Otras fuentes llaman «arc shot» o «360 shot» (StudioBinder) a un movimiento descrito de forma parecida; esta ficha las cita como términos de esa fuente, no como alias automáticos. `orbitLeft` solo como valor de un modelo (ver «Capacidad del modelo»), no como alias.
Familia: desplazamiento de cámara.
Estado: primera tanda. El estado de cada afirmación consta en «Fuente y localizador».

## Resultado visible
La cámara recorre una trayectoria curva alrededor de un sujeto o punto de referencia y, mientras lo hace, sigue encuadrándolo: cambia la posición de la cámara y, con ella, el fondo que se ve detrás del sujeto, que va mostrándose desde ángulos sucesivos. Se reconoce porque la cámara **se desplaza por el espacio**; si solo girase el objetivo desde un punto fijo, el fondo no cambiaría de perspectiva de esa manera (síntesis propia).

## Qué es y qué no es
- Es **recorrido curvo de la cámara en torno a un sujeto**. Wikipedia («Tracking shot») recoge que un tracking shot puede moverse de forma circular o semicircular, rotando alrededor del sujeto y manteniéndose equidistante; StudioBinder describe el «arc shot» como la cámara que orbita al sujeto siguiendo un arco, normalmente con el sujeto quieto.
- **No es una rotación desde posición fija (panorámica o pan).** En la panorámica la cámara gira sobre su eje y solo se mueve el objetivo; en un desplazamiento se mueve la cámara entera (Videomaker, apartado «Truck», que contrasta ambos). Una cámara que gira sobre sí misma mientras el sujeto permanece en el centro no hace órbita. No hay ficha de panorámica.
- **No es el sujeto que gira.** Un sujeto que da vueltas ante una cámara quieta, o que se gira sobre sí mismo, no es una órbita de cámara.
- No es el **desplazamiento lateral** (`references/recursos/movimiento/lateral.md`): el truck mueve la cámara en línea, paralela a la escena y sin curvar en torno a un punto; la órbita curva su trayectoria alrededor de un centro (síntesis propia).
- No es un **acercamiento ni un retroceso** (`references/recursos/movimiento/acercamiento.md`, `references/recursos/movimiento/retroceso.md`): en esos la distancia al sujeto cambia; en la órbita descrita por Wikipedia se mantiene (equidistante), aunque la ficha no lo exige (ver decisiones).
- No es el **seguimiento** (`references/recursos/movimiento/seguimiento.md`): en el seguimiento la cámara depende del movimiento del sujeto; en la órbita descrita por StudioBinder el sujeto está normalmente quieto y es la cámara la que aporta el movimiento. Una órbita alrededor de un sujeto que además se mueve combina ambas ideas.
- No es el **ángulo de vista**: no equivale a `references/recursos/encuadre/sujeto-de-perfil.md`, `references/recursos/encuadre/sujeto-de-espaldas.md` ni `references/recursos/encuadre/sujeto-de-tres-cuartos.md`, que son orientaciones fijas del sujeto; una órbita puede pasar por varias.

## Decisiones a concretar
Las fuentes consultadas no fijan estos parámetros como requisito de la órbita; son decisiones del plano:
- **Centro o sujeto de referencia**: en torno a qué gira la cámara (un personaje, un objeto, un punto del espacio) y si ese centro está quieto o se mueve. Wikipedia y StudioBinder hablan de «sujeto»; un punto sin sujeto no consta en ellas.
- **Radio**: distancia a la que orbita la cámara y si se mantiene constante. Wikipedia menciona la equidistancia en la variante circular; StudioBinder no trata el radio. La ficha no fija ni constancia ni valor.
- **Arco**: cuánto del recorrido se hace (un tramo corto, una media vuelta, una vuelta completa). StudioBinder define el arc shot como «al menos un semicírculo»; Wikipedia admite circular o semicircular. Esta ficha no impone vuelta completa ni mínimo: el arco es una decisión, y un tramo menor que el semicírculo queda fuera del «arc shot» de StudioBinder aunque siga siendo un recorrido curvo (diferencia terminológica declarada).
- **Sentido**: hacia qué lado recorre la cámara el arco. Ninguna fuente fija un sentido ni una convención para expresarlo. Debe indicarse con una referencia explícita, porque «izquierda» o «derecha» solas son ambiguas (desde la cámara, desde el sujeto o desde arriba). Convención de trabajo propuesta, no regla universal ni procedente de las fuentes (síntesis propia): «horario» o «antihorario visto desde arriba», con el sujeto de referencia en el centro. No se elige un sentido por defecto.
- Velocidad: constante, que se acelera o se frena.
- Encuadre inicial y final (qué se ve al empezar y al terminar el arco) y qué fondo se descubre por el camino.
- Si el sujeto está quieto o se mueve durante la órbita.
- Si hay cámara fija en su trayectoria o cámara en mano (`references/recursos/movimiento/camara-en-mano.md`).

## Se combina con · No confundir con
- Se combina con: primer plano (`references/recursos/encuadre/primer-plano.md`) o plano medio (`references/recursos/encuadre/plano-medio.md`) como escala mantenida durante el recorrido; cámara en mano (`references/recursos/movimiento/camara-en-mano.md`).
- No confundir con: panorámica (pan, sin ficha); desplazamiento lateral (`references/recursos/movimiento/lateral.md`); acercamiento y retroceso; seguimiento (`references/recursos/movimiento/seguimiento.md`); cámara fija (`references/recursos/movimiento/camara-fija.md`); sujeto de perfil, de espaldas o de tres cuartos (orientaciones del sujeto).
- No se asigna emoción ni significado a la órbita. StudioBinder le atribuye usos (centrar la atención, dar energía): son usos que describe esa fuente, no propiedades del movimiento.

## Ejemplo descriptivo
Ejemplo propio, ilustrativo.
«Órbita lenta de media vuelta en plano medio. La cámara describe un arco alrededor de Lucía, que permanece quieta junto a la ventana, siempre a la misma distancia y mirando hacia ella; el recorrido es en sentido horario visto desde arriba, con Lucía en el centro, y, a medida que avanza, el fondo pasa de la pared de la cocina a la ventana.»

## Capacidad del modelo
Pendiente de comprobar. `references/modelos.md` (Seedance 2.0, fila «Movimiento de cámara») cita el valor literal `orbitLeft`: correspondencia específica de ese modelo **sin verificar**. El nombre no prueba que el modelo recorra un arco con la cámara y no gire desde un punto fijo, ni que respete radio, arco o sentido; su significado exacto (qué lado, desde qué referencia) no está verificado y no se traduce a la convención «horario / antihorario visto desde arriba»; no se infiere ningún otro valor (de los 52 solo se citan cuatro). `references/estilos/redes.md` menciona órbitas en ejemplos oficiales de Seedance 2.5 sin fuente localizada, que no se trasladan a 2.0. Describir el sujeto de referencia, el sentido con su referencia explícita y qué debe quedar en cuadro.

## Fuente y localizador
| Afirmación | Fuente | Localizador | Estado |
|---|---|---|---|
| Un tracking shot puede moverse de forma circular o semicircular, rotando en torno al sujeto y manteniéndose equidistante | Wikipedia, «Tracking shot» (consultada en 2026) | introducción | `[definición respaldada]` |
| Arc shot: la cámara orbita al sujeto en un arco; «al menos un semicírculo»; el sujeto suele estar quieto; se hace normalmente con dolly curva o Steadicam; también llamado 360 shot o 360 tracking shot | Kyle DeGuzman, «The Arc Shot — Examples and Camera Movements Explained», StudioBinder (20-2-2025) | apartados «Arc shot definition» y «Centralize the audience's focus» | `[definición respaldada]` (fuente secundaria) |
| El pan solo mueve el objetivo; el truck mueve la cámara entera | Kyle Cassidy, «Camera movement: 11 techniques you should master», Videomaker (sin fecha visible) | apartado «Truck» | `[definición respaldada]` (fuente secundaria); sirve para la distinción movimiento/rotación, no define la órbita |
| Radio, sentido y arco como decisiones no fijadas; convención «horario / antihorario visto desde arriba» | Wikipedia y StudioBinder | — | `[síntesis propia]`: las fuentes no los fijan; StudioBinder fija un mínimo solo para su «arc shot» |
| Que el fondo muestre ángulos sucesivos por el cambio de posición | — | — | `[síntesis propia]`: las fuentes consultadas no explican la perspectiva |
| Adoptar «órbita» como nombre en español del recorrido curvo y no declarar «arc shot» como alias | entrada «órbita» (A3) de la fila «Movimiento» de `references/estilos/redes.md` | — | `[síntesis propia]`: la entrada original (`references/estilos/redes.md`, fila «Movimiento») no define el término |
| Ejemplo | — | — | `[ejemplo propio]` |
| Respuesta del modelo a `orbitLeft` o a la órbita | `references/modelos.md` | fila «Movimiento de cámara» | `[capacidad pendiente]` |

Límite declarado: una fuente secundaria de cine (un blog) y un artículo de enciclopedia; ninguna es manual técnico y ninguna usa el término «órbita» en español. Videomaker no trata el arco ni la órbita. No se consultó la página de StudioBinder sobre el tracking shot (404).
