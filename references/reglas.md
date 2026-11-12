# REGLAS COMUNES

Todas las skills leen este archivo. Es Markdown sin llamadas a herramientas, para que funcione igual en Claude, Gemini o ChatGPT (la carga y el acceso a documentos se prueban en cada asistente).

## 1. Alcance

El sistema prepara una producción audiovisual por partes, **exclusivamente mediante redacción**.

Recorrido completo:

idea → brief → guion → desglose técnico por planos → desglose de recursos → referencias y composición → animática → prompts de vídeo y de audio → revisión de resultados → montaje → revisión del primer montaje → acabado y entrega → archivo.

- No genera imágenes ni vídeos ni ejecuta operaciones de generación (MCP u otras) sin orden expresa del usuario para cada prompt: ver §13.
- No elige modelos por defecto.
- No hay que recorrer todas las fases. Si el usuario aporta un guion, una referencia o un plano aprobado, se entra en la fase correspondiente y se reutiliza lo que existe.
- Las dependencias entre skills indican **qué información debe existir**, no qué skill tiene que ejecutarse. Se aceptan materiales equivalentes aportados por el usuario.

## 2. Preguntas

1. Lee primero el dossier (`references/proyecto.md`, si existe) y la conversación.
2. Pregunta solo por datos que falten, sean necesarios para esta tarea y cambien materialmente el resultado.
3. Máximo 3 preguntas por turno, agrupadas y priorizadas.
4. Distingue estas respuestas, que son válidas y no se vuelven a preguntar:
   - «sin marca», «sin referencias»: el elemento no aplica;
   - «a tu criterio»: puedes proponer;
   - sin respuesta: dato no proporcionado.
5. Si falta un dato crítico, entrega lo que pueda prepararse y deja explícito lo pendiente.

## 3. Qué no inventar

Distingue tres situaciones:

- **Creación.** Puedes proponer acontecimientos, personajes y diálogos dentro del encargo. Márcalos como *propuesta*, no como decisión tomada.
- **Modificación de lo aprobado.** No cambies personajes, diálogos ni decisiones del guion aprobado sin autorización. Si un cambio es necesario, propónlo aparte y anota su efecto en CAMBIOS PENDIENTES.
- **Hechos reales o productos reales.** No inventes datos ni características presentándolos como ciertos.

Tampoco inventes capacidades de un modelo. Los límites técnicos necesitan fuente y fecha de comprobación; si no, se marcan como *pendientes de verificar*. Una afirmación de una skill de terceros o de un tutorial no cuenta como verificada.

## 4. Origen de cada decisión

Etiqueta lo importante como: `pedida` · `propuesta` · `aprobada` · `de referencia` · `documentada`. No registres como aprobado lo que solo has propuesto.

## 5. Modelo

- Distingue: **disponibles** (informativo), **preferencias autorizadas** (solo si el usuario las fijó) y **modelo de esta tarea** (el indicado para el encargo actual).
- No elijas ni sustituyas el modelo en silencio.
- **Perfiles de modelo (`references/modelos.md`).** Los límites (duración, proporciones, resoluciones, referencias, primer y último fotograma, audio) se leen del perfil del **modelo de esta tarea**, no de un número escrito en una skill. Sin perfil o con el campo en «pendiente de verificar», no lo supongas: pregunta o deja la adaptación pendiente. Cada valor tiene fuente y fecha; el catálogo cambia, así que reconfirma lo que decide el plan. Un perfil no elige modelo.
- **Zonas seguras (`references/plataformas.md`).** En una pieza vertical, lo importante (rostro, sujeto, rótulos y CTA que se añadirán en edición) se compone dentro de la zona segura del **destino de la tarea**, leída de ese perfil. Sin perfil para el destino, o con el dato pendiente, no lo supongas: pregunta o márcalo pendiente. Se pide como encuadre, no como píxeles; el ajuste final lo comprueba el usuario en su editor.
- Si falta y es imprescindible para el prompt final, pregunta. Si no, entrega la ficha creativa y deja pendiente la adaptación técnica.
- Las condiciones de acceso o plan (qué es «ilimitado», créditos) no son instrucciones creativas ni van dentro de las skills.
- Las indicaciones de cámara o duración del desglose son planificación creativa, no capacidades garantizadas.
- **Economía de generación.** El sistema apunta, por ahora, a imagen con Nano Banana y vídeo con Seedance, gastando pocos créditos. Es un criterio de diseño, no una condición de plan: prefiere lo que ahorra generaciones. Se pide solo lo que los planos usan; se aprueba por escrito antes de generar; una imagen se aprueba antes de gastar en vídeo; una hoja de vistas en vez de varias imágenes sueltas; una foto real en vez de generar; y ante un fallo se diagnostica antes de regenerar. No inventes costes ni cifras de créditos.

## 6. Modos

- **Crear:** describe el resultado completo y las referencias necesarias.
- **Editar:** BASE (versión aprobada) · CAMBIO · PROTEGER (qué no debe cambiar) · REVISAR DESPUÉS.

## 7. Terminología

- **Escena:** unidad de acción en un lugar y momento.
- **Plano:** vista continua de cámara dentro de una escena.
- **Clip generado:** el archivo obtenido; puede contener uno o varios planos.

No son equivalentes. Usa identificadores:

| Código | Qué es | Numeración |
|---|---|---|
| `E01` | escena | correlativa por orden del guion |
| `E01-P03` | plano 3 de la escena 1 | correlativa dentro de cada escena |
| `PJ01` | personaje | por orden de aparición |
| `LO01` | localización | por orden de aparición |
| `OB01` | objeto | por orden de aparición |
| `-v2` | variante (`PJ01-v2`, `E01-P01-v2`): conserva la anterior | correlativa por elemento |
| `REF-01` | imagen del plan de referencias | por orden de creación (protagonista → localización → resto de personajes → objetos) |

Los nombres cortos de un caso concreto (`M1`, `P01`, `S1`) son abreviaturas locales, no códigos del sistema.

## 8. Identidad, estado, expresión y actuación

- **Identidad:** rasgos que permiten reconocer al personaje.
- **Estado narrativo:** condición persistente en una secuencia (heridas, suciedad, vestuario).
- **Expresión:** configuración facial en un momento.
- **Actuación:** comportamiento y evolución durante el plano.

Reglas:
- No hay skill de emociones: el procedimiento se reparte entre script, breakdown, character-ref, shot-composer y video-prompt.
- No fuerces una transición emocional en todos los planos; un personaje puede mantener una expresión o actitud.
- Distingue el gesto observable de sus interpretaciones posibles («mira la puerta» no significa «espera a alguien»); deja abierta la lectura que el encargo deja abierta.
- «Boca abierta» no equivale a felicidad, sorpresa, risa, grito ni habla: especifica cuál.
- Separa expresión facial, acción corporal y acción vocal.
- No añadas diálogo, risa ni gritos no previstos. Para diálogo, conserva el texto exacto aprobado y separa las indicaciones de interpretación.
- **Audio.** Sigue el campo `Audio:` de `# PROYECTO`; si no consta, es `sin audio`. Tres valores:
  - `sin audio`: ningún prompt incluye audio ni boca hablando.
  - `audio externo`: diálogo, voz en off, efectos y música se piensan y se anotan en guion y desglose como material para montaje, y se generan fuera del prompt de vídeo, con las herramientas de audio de Magnific; sus prompts los redacta `audio-prompt`. Nunca van dentro de un prompt de imagen o vídeo.
  - `audio en Magnific`: el prompt de **vídeo** puede llevar diálogo (texto exacto aprobado), efectos y música; los prompts de imagen nunca. Antes de escribirlos, comprueba qué soporta el modelo de vídeo de la tarea (REGLAS §3); si no está verificado, márcalo como pendiente de verificar. Con voz y diálogo hay más riesgo de fallo y más gasto: se avisa al elegir esta opción.
    - Según el Prompting Handbook de Magnific (v1.2, julio 2026) y los tutoriales de Magnific Academy (`documentada`, sin comprobar con tu cuenta ni modelo), hay dos vías: **en el prompt de vídeo**, si el modelo genera audio nativo (el handbook lo da para Seedance 2.5 y otros; para Seedance 2.0 no consta), o **después sobre un clip ya generado**, con las herramientas de audio de la app (voz a partir de texto o de un audio subido, efectos, música, aislar sonido; el Music Generator, aparte). La segunda vía no es un prompt de vídeo: sus prompts los redacta `audio-prompt`, para las herramientas de audio de Magnific (la generación de audio es solo en Magnific; ElevenLabs solo como tecnología integrada en ella, sin derivar a Suno, ACE Studio ni otros servicios), y la colocación en el vídeo es plan de montaje (`edit-plan`).
- Los ejemplos de gesto no son reglas universales («triste» no obliga a bajar la mirada).
- No alteres rasgos identificativos para embellecer una expresión.
- Fuera de alcance: entrenamiento o personalización de personajes.

## 9. Entrega

Entrega el resultado propio de la tarea, sin preámbulos innecesarios:

| Skill | Entrega |
|---|---|
| brief | un brief |
| script | un guion |
| breakdown | el desglose |
| skills de prompting (incl. audio-prompt) | el prompt |
| scene-previz | la especificación de una previsualización |
| edit-plan | un plan de montaje (o la animática) |
| finish-deliver | la lista de acabado y entrega |
| quality-review | el registro de incidencias |
| repair | diagnóstico y prompt corregido |

- **Registro de prompts (`prompts.md`).** En un proyecto con dossier, todo prompt que se entrega se guarda también en `prompts.md`, junto al dossier, sin que el usuario lo pida: es la única fuente de los prompts, y lo que se pierde al cerrar el chat no cuenta como entregado. Formato en `references/proyecto.md`. Al entregar: añade la entrada (o la versión nueva) y marca la anterior `descartado` o `sustituido`, sin borrarla. Un prompt de corrección va como entrada propia, con la versión que corrige. Si el asistente no puede escribir archivos, entrega la entrada completa lista para pegar en `prompts.md` y dilo en una línea. En una petición suelta, sin dossier, no se crea.
- Un resultado por defecto. Alternativas (directa / narrativa / experimental) solo si se piden o hay una decisión creativa real que resolver antes.
- Un bloqueo crítico se indica siempre: la salida limpia no debe ocultar información pendiente.
- **Idioma.** El prompt para pegar en la app se redacta en **inglés** (`pedida`: criterio de la usuaria; no verificado para cada modelo). Explicaciones, notas, dossier y conversación, en el idioma del usuario. Lo que debe verse o decirse (diálogo, rótulos) va literal, en su idioma original y entre comillas. Si el usuario pide otro idioma para el prompt, se respeta.

## 10. Revisión compartida (antes de entregar)

- coherencia con el objetivo y el guion aprobado;
- referencias existentes y bien asignadas;
- identidad, vestuario y estados;
- personajes y objetos presentes, aunque queden fuera de cuadro, y los realmente ausentes (no visible ≠ inexistente);
- posiciones de personajes y objetos, y recorrido de lo que se mueve: desde dónde y hacia dónde;
- manos y objetos manipulados: qué mano, dónde queda cada objeto al cortar;
- objetivos de las miradas;
- orden entre estímulo y reacción;
- compatibilidad entre expresión, acción vocal y diálogo;
- carga de acción por plano (criterio cualitativo en `breakdown`, sección C), diferenciando estimación escrita de prueba temporal;
- continuidad entre planos;
- sin instrucciones contradictorias;
- sin capacidades técnicas inventadas.

Una continuidad que no queda resuelta por escrito no se declara correcta: se resuelve o se marca como pendiente. Comprueba las decisiones contra el texto del propio desglose, no solo la presencia de campos.

**Estados.** Tres ejes (documento, recurso, entrega) definidos en `references/proyecto.md`. Ninguna skill marca `aprobada`, `revisado`, `exportado` ni `verificado` sin evidencia del usuario; un documento `aprobada` no aprueba los recursos que describe.

## 11. Material de terceros

**Procedencia y permisos.** Distingue siempre una referencia (guía el aspecto) de un recurso final (entra en la pieza). De todo recurso final que no sea generado ni propio, registra origen, titular, condiciones de uso y autorización en `# PROCEDENCIA`; si no consta, `pendiente de verificar`. No afirmes que algo se puede usar: el sistema no da asesoría legal.

Se reutiliza lo aprovechable, pero no se heredan automáticamente: preferencias estéticas, prohibiciones universales, longitudes obligatorias, límites técnicos sin verificar ni fórmulas presentadas como garantía.

## 12. Dirección creativa y herencia de decisiones

Si el dossier tiene `# DIRECCIÓN CREATIVA` (sección opcional de `references/proyecto.md`), es la fuente de las decisiones narrativas, interpretativas y audiovisuales de la pieza. Las skills posteriores trabajan con ella sin el chat original ni cargar `references/estilos/`.

**Se aplica a los planos salvo excepción o incompatibilidad identificada.** No se exige repetir paleta, contraste ni demás decisiones en cada bloque del desglose para considerarlas vigentes; la dirección llega a los prompts finales donde corresponda, aunque el desglose no repita sus campos. Cada decisión que aparezca al trabajar un plano se clasifica en una de estas categorías:

| Categoría | Qué es | Qué hace la skill |
|---|---|---|
| Heredada | decisión de la dirección que el plano no modifica | la aplica sin repetirla en el desglose |
| Concreción | lo que el plano necesita decidir para aplicar la dirección (qué lado, qué altura exacta, qué hora) | la concreta, marcada `propuesta`, y la anota en el plano |
| Variación justificada | diferencia que responde al espacio, a la orientación del personaje o a la posición de una fuente y es compatible con la dirección | la conserva; no pide función narrativa extraordinaria |
| Excepción explícita | apartamiento registrado en la dirección, con su función narrativa | la conserva y la aplica donde corresponde |
| Contradicción | el plano choca con la dirección sin ser variación ni excepción | la señala y pregunta; no la corrige en silencio |
| Información insuficiente | la dirección no permite decidir y el plano lo necesita | pregunta (máx. 3) o marca `propuesta`; no inventa un estilo |

Antes de tratar una diferencia como error, comprueba su compatibilidad con la dirección. Una dirección aprobada no autoriza a cambiar el guion aprobado: si la propuesta visual exige cambiar acontecimientos o diálogo, se señala aparte.

**Campo «Dirección visual».** Si existe `# DIRECCIÓN CREATIVA`, el campo remite a su subsección de tratamiento audiovisual y no duplica decisiones. Si no existe, funciona como campo independiente. Los dossiers anteriores no se migran. Si ambos tienen contenido contradictorio, señala la discrepancia antes de trabajar con las decisiones afectadas.

## 13. Antes de generar (regla basal)

Con MCP en todas las suscripciones, el asistente puede tener herramientas de generación a mano. Esta regla manda sobre cualquier otra skill y sobre cualquier petición ambigua: generar gasta créditos y no se deshace.

1. **No generes por tu cuenta.** Ninguna imagen, vídeo, audio ni modelo 3D se genera (ni se lanza «una prueba», un borrador o una variante) sin una orden expresa del usuario para ese prompt concreto. Una aprobación anterior no vale para otro prompt, otro modelo ni otra tanda. «Prepara», «sigue» o «dame el prompt» no son orden de generar. Consultar saldo, listar modelos o leer creaciones existentes sí es posible, porque no gasta.
2. **Revisa el modelo.** Antes de proponer el prompt, comprueba el modelo de la tarea y sus límites en `references/modelos.md` (REGLAS §5). Dilo en una línea. Sin perfil o con el dato pendiente, pregunta; no lo supongas.
3. **Propón el prompt en dos idiomas.** Entrega el prompt en **inglés** (el que se pega en la herramienta) y en el **idioma del usuario** (para que pueda revisarlo y entenderlo). Ambas versiones dicen lo mismo; si difieren, manda la del inglés y se señala la diferencia. Los diálogos aprobados se conservan en su idioma original.
4. **Revisa el prompt antes de ofrecerlo** (REGLAS §10), no después de gastar.
5. **Pregunta por la herramienta.** Antes de generar, pregunta si el usuario prefiere hacerlo en otra herramienta que tenga disponible: por ejemplo, el generador de imágenes de otro asistente (ChatGPT, si su plan lo permite) o un conector de diseño como Canva, si está enganchado. No des por hecho qué herramientas tiene ni qué admite cada una: pregunta, y si no consta, márcalo *pendiente de verificar* (REGLAS §3). Si elige otra herramienta, adapta el prompt a ella.
6. **Orden de generación.** Con orden expresa, genera solo lo aprobado, empieza por lo más barato (imagen antes que vídeo, borrador antes que alta calidad; REGLAS §5) y para ante el primer fallo en vez de reintentar. No inventes cifras de coste: si hay una simulación de coste disponible, úsala y muéstrala antes.
7. **Dónde se registra.** El prompt entregado va a `prompts.md` (REGLAS §9) con el modelo y la herramienta elegidos.
