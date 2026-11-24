# CPIA-001 v1.1 — Reestructuración con andamiaje cognitivo

**Curso:** IA en Marketing Farmacéutico  
**Audiencia:** gerentes de marketing no técnicos, con conocimientos básicos de IA y ChatGPT  
**Alcance:** sesiones 3, 7 y 8; guías de aprendiz e instructor; laboratorios 7 y 8  
**Principios de diseño:** andamiaje cognitivo, división temática funcional, práctica guiada, transferencia progresiva y control humano obligatorio.

## Reglas pedagógicas transversales

- Cada sesión conserva 60 minutos síncronos.
- El trabajo autónomo total por sesión tiene un máximo de 90 minutos: preparación más consolidación.
- La preparación recupera experiencias cotidianas; no incluye configuraciones, migraciones, integraciones ni creación de carpetas complejas.
- La sesión en vivo avanza de **modelado del instructor** a **práctica guiada** y luego a **adaptación individual**.
- La consolidación se realiza en un Proyecto de ChatGPT Plus llamado **Laboratorio de Plantillas**, con Prompts Maestros listos para usar y un máximo de tres variables editables.
- No se construyen automatizaciones reales. Toda salida de IA queda en borrador hasta que una persona identificada la revise y apruebe.
- Los ejemplos y materiales de empresa deben estar anonimizados y libres de datos personales, sensibles, confidenciales o de pacientes.

---

## Sesión 3 — Estandarización asistida con SOPs rellenables

### Resultado de aprendizaje

Al finalizar, el aprendiz adapta una plantilla de SOP a un flujo sencillo de su marca, identifica insumos, responsable de revisión y criterio de aprobación, sin redactar documentación técnica desde cero.

### Distribución del tiempo

| Momento | Tiempo | Actividad del aprendiz | Andamiaje y acción del instructor | Evidencia |
| --- | ---: | --- | --- | --- |
| Preparación | 20 min | Traer un brief desorganizado o correo real anonimizado y señalar qué resultado suele pedir. | Enviar una ficha de una página con ejemplo válido y reglas de anonimización. No solicitar configuración previa. | Insumo anonimizado y una frase sobre el resultado esperado. |
| En vivo: conexión | 0–5 min | Reconocer dónde se pierde tiempo o claridad. | Presentar un caso farmacéutico cotidiano y el objetivo de estandarizar. | Dolor operativo identificado. |
| En vivo: modelado | 5–17 min | Observar cómo se completa una plantilla. | Pensar en voz alta mientras llena un único SOP de ejemplo; diferenciar dato aportado, salida de IA y decisión humana. | Plantilla modelo comprendida. |
| En vivo: práctica guiada | 17–35 min | Completar con el grupo los campos de un segundo caso. | Formular preguntas de apoyo y ofrecer opciones cerradas cuando falte información. | SOP colectivo completo. |
| En vivo: adaptación | 35–50 min | Rellenar la plantilla con su propia marca o caso anonimizado. | Dar retroalimentación sobre claridad, alcance y punto de aprobación. | Primer borrador individual. |
| En vivo: revisión | 50–57 min | Aplicar el checklist de seguridad en parejas. | Verificar que ninguna salida pueda publicarse sin aprobación. | Checklist marcado. |
| En vivo: cierre | 57–60 min | Declarar un ajuste y el responsable de aprobación. | Explicar la consolidación y mostrar el Prompt Maestro. | Próximo paso definido. |
| Consolidación | 45 min | Usar el Prompt Maestro, corregir el borrador y guardar una versión final de una página. | Proporcionar plantilla, ejemplo resuelto y checklist; resolver dudas de contenido, no de configuración. | SOP rellenable adaptado a una marca. |

**Trabajo autónomo total:** 65 minutos.

### Guía del aprendiz

1. Anonimiza nombres, correos, datos personales, información de pacientes y cifras confidenciales.
2. Elige un solo flujo repetitivo y de bajo riesgo.
3. Completa únicamente los campos entre corchetes de la plantilla proporcionada.
4. Si desconoces un dato, escribe `PENDIENTE DE VALIDAR`; no lo inventes.
5. Define siempre quién revisa y qué debe comprobar antes de usar o publicar la salida.

### Guía del instructor

- Llevar una plantilla parcialmente resuelta y otra en blanco.
- Evitar pedir varios SOPs o explicar notaciones de procesos.
- Modelar primero, completar un caso con el grupo y retirar gradualmente el apoyo.
- Reconducir cualquier intento de automatización hacia el mapa del proceso y su aprobación humana.
- Evaluar suficiencia operativa, no sofisticación técnica.

### Entregable y criterio de logro

Un SOP de una página, adaptado desde la plantilla. Se considera logrado si contiene objetivo, insumos, pasos comprensibles, límites de uso, responsable de revisión y criterio explícito de aprobación.

### Prompt Maestro — Adaptar un SOP

Variables editables: `[MARCA]`, `[TIPO_DE_INSUMO]`, `[RESULTADO_ESPERADO]`.

```text
Rol: Actúa como facilitador de operaciones de marketing farmacéutico para un usuario no técnico.

Contexto: Estoy adaptando una plantilla de procedimiento para [MARCA]. El insumo habitual es [TIPO_DE_INSUMO] y el resultado que necesito es [RESULTADO_ESPERADO].

Tarea: Ayúdame a completar únicamente los campos vacíos de la plantilla que pegaré después. Conserva sus títulos y orden. Si falta información, escribe "PENDIENTE DE VALIDAR" y formula una pregunta breve; no inventes datos.

Reglas: Usa lenguaje de negocio, mantén la salida como borrador, no incluyas datos personales ni de pacientes y exige revisión humana antes de uso o publicación.

Formato: Devuelve la misma plantilla completada y, al final, un checklist de cinco verificaciones.
```

---

## Sesión 7 — Automatizaciones seguras: lógica de marketing y control humano

### Resultado de aprendizaje

Al finalizar, el aprendiz diseña la lógica de negocio de un flujo asistido por IA e identifica el evento de inicio, la información necesaria y el punto exacto de aprobación humana, sin configurar herramientas ni integraciones.

### División temática funcional

- **Capa A — Sesión síncrona:** lógica de marketing. Responde solamente: ¿cuándo debe actuar la IA?, ¿qué información necesita para comenzar? y ¿quién valida el resultado antes de publicar?
- **Capa B — Consolidación:** representación no-code del comportamiento seguro usando lenguaje de marketing: desviación del proceso, plan de retorno seguro e historial de control de calidad.

### Distribución del tiempo

| Momento | Tiempo | Actividad del aprendiz | Andamiaje y acción del instructor | Evidencia |
| --- | ---: | --- | --- | --- |
| Preparación | 15 min | Traer un correo anonimizado de agencia o un brief desorganizado e identificar qué acción suele ocurrir después. | Enviar tres preguntas guía. Prohibir configuraciones, migraciones o pruebas con herramientas. | Insumo y acción posterior. |
| En vivo: encuadre | 0–7 min | Diferenciar ayuda de IA y decisión humana. | Mostrar un ejemplo visual de flujo seguro. | Principio de control humano comprendido. |
| En vivo: evento de inicio | 7–18 min | Definir cuándo debería comenzar la asistencia. | Modelar “llegó el correo de la agencia” como evento observable. | Primera columna de la ficha. |
| En vivo: datos mínimos | 18–30 min | Separar datos necesarios de datos deseables. | Aplicar minimización de datos y marcar ausencias críticas. | Segunda columna de la ficha. |
| En vivo: aprobación | 30–43 min | Identificar persona, momento y criterio de aprobación. | Exigir un punto exacto antes de cualquier publicación o envío. | Tercera columna de la ficha. |
| En vivo: práctica guiada | 43–54 min | Completar la Ficha de Control Visual con un caso propio. | Ofrecer preguntas y ejemplos; no introducir herramientas no-code. | Ficha en borrador. |
| En vivo: prueba oral | 54–58 min | Explicar qué ocurre si falta un dato crítico. | Introducir “detener, devolver a revisión y no enviar”. | Respuesta segura declarada. |
| En vivo: cierre | 58–60 min | Confirmar aprobador y siguiente ajuste. | Presentar la Capa B y el glosario simplificado. | Compromiso de consolidación. |
| Consolidación | 60 min | Completar la ficha y añadir una desviación, un retorno seguro y dos registros del historial de calidad mediante el Prompt Maestro. | Entregar ficha, glosario, ejemplo y sandbox textual. | Ficha final de control visual. |

**Trabajo autónomo total:** 75 minutos.

### Guía del aprendiz

- Describe el flujo con lenguaje cotidiano; no necesitas conocer Make, Zapier, Power Automate, APIs ni programación.
- Limita el caso a una tarea de marketing y a una sola aprobación final claramente ubicada.
- Si falta información crítica, la IA debe detenerse y devolver el borrador a revisión.
- Ningún contenido, claim o recomendación se libera automáticamente.

### Guía del instructor

- Mantener los 60 minutos en la Capa A. No demostrar integraciones ni pantallas de configuración.
- Usar tarjetas o notas adhesivas para representar inicio, datos y aprobación.
- Preguntar repetidamente: “¿quién responde por esta decisión?” y “¿qué impediría publicar?”.
- Introducir la Capa B solo al explicar la consolidación, mediante las equivalencias del glosario.
- Validar primero el control humano; la eficiencia es secundaria.

### Laboratorio aplicado 7 — Automatización que debe fallar bien

**Reto:** diseñar una Ficha de Control Visual, no construir un flujo ni una integración.

| ¿Qué inicia el flujo? | ¿Qué datos usa la IA? | ¿En qué punto exacto intervengo yo para aprobar? |
| --- | --- | --- |
| [Evento observable, por ejemplo: llegó un correo de la agencia] | [Brief, guía de marca y claims aprobados; sin datos personales] | [Rol + momento + criterio, por ejemplo: gerente revisa claims antes de mover a “Aprobado”] |

**Prueba de fallo seguro:** si `[DATO_CRÍTICO]` falta o es inconsistente, la IA detiene el trabajo, marca la desviación y devuelve el borrador a `[ROL_REVISOR]`; no publica, envía ni reemplaza archivos aprobados.

**Criterios de éxito:**

- El inicio es observable y no ambiguo.
- Los datos son suficientes, autorizados y mínimos.
- La intervención humana está ubicada antes de publicar o enviar.
- La desviación produce detención y retorno a revisión.
- El historial permite saber qué se probó, qué falló y quién decidió.

### Prompt Maestro — Ficha de Control Visual

Variables editables: `[EVENTO]`, `[DATOS]`, `[APROBADOR]`.

```text
Rol: Actúa como facilitador de control de calidad para marketing farmacéutico.

Contexto: El trabajo empieza cuando ocurre [EVENTO]. La IA puede consultar únicamente [DATOS]. La persona que debe aprobar es [APROBADOR].

Tarea: Completa una Ficha de Control Visual de tres columnas: 1) qué inicia el flujo, 2) qué datos usa la IA y 3) en qué punto exacto interviene la persona para aprobar.

Seguridad: Propón una desviación por falta de información, un plan de retorno seguro que no publique ni envíe nada y dos entradas de historial de control de calidad. No propongas código, integraciones ni ejecución automática.

Formato: Una tabla de tres columnas seguida de “Si algo sale mal” e “Historial de control de calidad”.
```

---

## Sesión 8 — Simulación final: Manual de Bolsillo de IA Segura

### Resultado de aprendizaje

Al finalizar, el aprendiz integra las decisiones esenciales del curso en un Manual de Bolsillo de máximo tres páginas —o un checklist visual equivalente— que permita usar IA con su marca de forma consistente, revisable y segura.

### Distribución del tiempo

| Momento | Tiempo | Actividad del aprendiz | Andamiaje y acción del instructor | Evidencia |
| --- | ---: | --- | --- | --- |
| Preparación | 20 min | Traer nombre de una marca, tres tareas frecuentes y un ejemplo anonimizado de pieza o brief. | Enviar lista simple de insumos y un ejemplo de manual. No pedir compilación de historiales ni carpetas. | Tres tareas priorizadas. |
| En vivo: criterio de liberación | 0–8 min | Reconocer qué nunca debe decidir la IA sola. | Modelar un checklist antes/después. | Límites identificados. |
| En vivo: selección | 8–18 min | Elegir una sola tarea para la simulación. | Ayudar a reducir alcance según frecuencia, valor y riesgo. | Caso acotado. |
| En vivo: simulación guiada | 18–38 min | Recorrer entrada, borrador de IA, revisión y aprobación. | Pausar en cada decisión humana y representar una desviación. | Flujo seguro ensayado. |
| En vivo: construcción | 38–50 min | Completar el esqueleto del Manual de Bolsillo. | Facilitar bloques prediseñados y ejemplos breves. | Manual al 70 %. |
| En vivo: prueba cruzada | 50–57 min | Intercambiar el checklist y detectar una ambigüedad. | Usar cuatro preguntas de revisión y limitar la retroalimentación a una mejora prioritaria. | Mejora identificada. |
| En vivo: cierre | 57–60 min | Declarar cuándo y con quién probará el manual. | Explicar entrega y rúbrica. | Plan de aplicación. |
| Consolidación | 60 min | Usar el Prompt Maestro para completar, reducir y revisar el manual; entregar máximo tres páginas o un checklist visual. | Proporcionar plantilla, ejemplo, rúbrica y sandbox textual. | Manual de Bolsillo final. |

**Trabajo autónomo total:** 80 minutos.

### Guía del aprendiz

- Elige una tarea frecuente y controlable; no intentes documentar toda la operación.
- Reutiliza las plantillas de las sesiones anteriores.
- Escribe instrucciones que un colega pueda seguir sin conocimientos técnicos.
- Mantén el documento en tres páginas como máximo o usa un checklist visual de una página.
- Incluye siempre datos permitidos/prohibidos, revisión humana, desviación y retorno seguro.

### Guía del instructor

- Presentar un manual modelo de tres páginas y un checklist visual alternativo.
- Evaluar capacidad de decisión segura y aplicabilidad, no volumen ni tecnicismo.
- Simular una ausencia crítica —por ejemplo, claim no validado— y observar si el aprendiz detiene la liberación.
- Evitar ampliar el proyecto a un manual operativo completo o roadmap tecnológico.

### Laboratorio aplicado 8 — Simulación final

**Entregable:** Manual de Bolsillo de IA Segura para mi Marca, máximo tres páginas, o checklist de liberación visual.

Estructura mínima:

1. **Para qué sí y para qué no usamos IA:** una tarea autorizada y dos límites.
2. **Antes de empezar:** insumos mínimos y datos que nunca se deben cargar.
3. **Antes de liberar:** responsable, criterios de aprobación y evidencia que se conserva.
4. **Si algo falta o sale mal:** detención, desviación y retorno seguro.
5. **Checklist de liberación:** cinco a siete casillas observables.

Checklist sugerido:

- [ ] El objetivo y la audiencia están claros.
- [ ] Solo se usaron datos autorizados, mínimos y anonimizados.
- [ ] Los claims y referencias coinciden con fuentes aprobadas.
- [ ] La salida fue revisada por la persona responsable.
- [ ] Las correcciones quedaron registradas en el historial de calidad.
- [ ] No existe contenido pendiente marcado como `PENDIENTE DE VALIDAR`.
- [ ] La persona autorizada aprobó la liberación.

### Prompt Maestro — Manual de Bolsillo

Variables editables: `[MARCA]`, `[TAREA]`, `[APROBADOR]`.

```text
Rol: Actúa como diseñador de una guía ejecutiva de IA segura para marketing farmacéutico.

Contexto: La marca es [MARCA], la tarea autorizada es [TAREA] y quien aprueba antes de liberar es [APROBADOR].

Tarea: Crea un Manual de Bolsillo breve con: uso permitido, límites, insumos mínimos, datos prohibidos, pasos de revisión, una desviación frecuente, plan de retorno seguro y checklist de liberación.

Reglas: Usa lenguaje para un gerente no técnico. No inventes políticas, claims ni responsables. Marca faltantes como "PENDIENTE DE VALIDAR". La IA nunca publica, envía o aprueba por sí sola.

Formato: Máximo 900 palabras, diseñado para caber en tres páginas, con títulos breves y un checklist final de cinco a siete casillas.
```

---

## Glosario simplificado del Módulo 7

| Término técnico | Lenguaje de marketing | Explicación funcional | Ejemplo farmacéutico |
| --- | --- | --- | --- |
| Trigger / disparador | **Evento de Inicio de Campaña** | Hecho observable que indica que puede comenzar la asistencia. | Llegó un correo de la agencia con el brief. |
| Input / entrada | **Información necesaria para comenzar** | Documentos o datos autorizados que la IA necesita. | Brief anonimizado, guía de marca y claims aprobados. |
| Condition / condición | **Regla de decisión de marketing** | Pregunta de negocio que determina el siguiente paso. | ¿El claim aparece en la lista aprobada? |
| Exception / excepción | **Desviación del Proceso** | Situación que impide continuar de manera normal y requiere revisión. | Falta el claim regulatorio en el brief. |
| Human-in-the-loop | **Punto de aprobación humana** | Momento exacto en que una persona revisa y decide. | El gerente valida contenido y claims antes de liberar. |
| Rollback / reversión | **Plan de Retorno Seguro** | Acción para volver a un estado de revisión sin publicar ni perder la versión válida. | Regresar el borrador a la carpeta de revisión sin enviar nada. |
| Test logs / logs de prueba | **Historial de Control de Calidad** | Registro comprensible de lo probado, el resultado y la decisión. | “Faltó referencia; se detuvo; Ana devolvió a agencia”. |
| Output / salida | **Borrador de trabajo** | Resultado provisional producido por la IA. | Primera versión de un correo para revisión. |
| Fail-safe | **Detención segura** | Comportamiento que evita avanzar cuando hay duda o información crítica ausente. | No generar pieza final si el claim no está validado. |

---

## Plantilla de SOP rellenable — Módulo 3

> Instrucción: completa solo los campos entre corchetes. Si no conoces una respuesta, escribe `PENDIENTE DE VALIDAR`. Extensión máxima: una página.

### SOP breve: preparación asistida de un borrador de marketing

**Marca:** `[MARCA]`  
**Nombre del flujo:** `[NOMBRE_COTIDIANO_DEL_FLUJO]`  
**Responsable del proceso:** `[ROL_RESPONSABLE]`  
**Versión/fecha:** `[VERSIÓN_Y_FECHA]`

#### 1. ¿Para qué sirve?

Cuando recibimos `[TIPO_DE_INSUMO]`, usamos IA para preparar `[RESULTADO_EN_BORRADOR]`, con el fin de `[OBJETIVO_DE_NEGOCIO]`.

#### 2. ¿Qué necesito antes de empezar?

- Insumo principal: `[DOCUMENTO_O_INFORMACIÓN]`.
- Fuente aprobada de marca o claims: `[FUENTE_APROBADA]`.
- Información que debe eliminarse o anonimizarse: `[DATOS_PROHIBIDOS_O_SENSIBLES]`.

#### 3. Pasos

1. `[ROL]` revisa que el insumo esté completo y anonimizado.
2. `[ROL]` pega el insumo autorizado en el Prompt Maestro `[NOMBRE_DEL_PROMPT]`.
3. La IA produce únicamente un **borrador** de `[RESULTADO]`.
4. `[ROL_REVISOR]` compara el borrador con `[CRITERIOS_O_FUENTES_APROBADAS]`.
5. Si cumple, `[ROL_AUTORIZADO]` aprueba su liberación por medio de `[MECANISMO_DE_APROBACIÓN]`.

#### 4. ¿Qué nunca debe hacer la IA?

- `[LÍMITE_1]`.
- `[LÍMITE_2]`.
- Publicar, enviar o aprobar el contenido por sí sola.

#### 5. Si falta información o algo no coincide

Detener el proceso, marcar `[ELEMENTO_FALTANTE]` como `PENDIENTE DE VALIDAR` y devolver el borrador a `[ROL_RESPONSABLE]`. No publicar ni enviar nada.

#### 6. Criterio de aprobación

El borrador solo puede liberarse cuando `[ROL_APROBADOR]` confirme que:

- [ ] usa únicamente información autorizada;
- [ ] respeta la guía de marca;
- [ ] los claims y referencias están validados;
- [ ] no contiene datos personales, sensibles ni de pacientes;
- [ ] no quedan campos `PENDIENTE DE VALIDAR`.

#### 7. Evidencia mínima

Guardar `[VERSIÓN_DEL_BORRADOR]`, `[NOMBRE_O_ROL_DEL_APROBADOR]`, `[FECHA]` y `[DECISIÓN: APROBADO / DEVUELTO]` en `[UBICACIÓN_AUTORIZADA]`.

### Rúbrica rápida de revisión

| Criterio | Sí | Aún no |
| --- | :---: | :---: |
| El flujo cubre una sola tarea y cabe en una página. | [ ] | [ ] |
| Los insumos y datos prohibidos son claros. | [ ] | [ ] |
| La salida de IA está definida como borrador. | [ ] | [ ] |
| Existe un responsable y un punto de aprobación. | [ ] | [ ] |
| La ausencia de información produce detención segura. | [ ] | [ ] |

---

## Verificación de carga autónoma

| Sesión | Preparación | Consolidación | Total autónomo | Cumple máximo de 90 min |
| --- | ---: | ---: | ---: | :---: |
| 3 | 20 min | 45 min | 65 min | Sí |
| 7 | 15 min | 60 min | 75 min | Sí |
| 8 | 20 min | 60 min | 80 min | Sí |

