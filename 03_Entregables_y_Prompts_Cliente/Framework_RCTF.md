# Componentes del Framework RCTF para Prompts

## R (Rol)

**¿Qué es?**
Define la identidad, nivel de experiencia y perspectiva que debe asumir el modelo para responder. El rol orienta el conocimiento, el lenguaje y el enfoque de la respuesta.

**Objetivo:**
Indicar **quién es** el modelo durante la ejecución de la tarea.

**Ejemplos:**

* Actúa como un Director de Marketing Pharma Senior.
* Actúa como un arquitecto de software especializado en microservicios.
* Actúa como un abogado experto en derecho laboral.
* Actúa como un científico de datos con 10 años de experiencia.

---

## C (Contexto)

**¿Qué es?**
Proporciona toda la información necesaria para que el modelo comprenda el escenario en el que debe trabajar.

**Objetivo:**
Explicar **en qué situación** debe actuar el modelo.

**Puede incluir:**

* Producto o servicio.
* Industria o dominio.
* Público objetivo.
* Objetivos del negocio.
* Regulaciones o restricciones.
* Información relevante disponible.

**Ejemplo:**

* Producto: Plataforma de banca digital.
* Público objetivo: Clientes entre 25 y 45 años.
* Industria: Servicios financieros.
* Regulación: Cumplimiento de la normativa de protección de datos.
* Objetivo: Incrementar la adopción del servicio.

---

## T (Tarea)

**¿Qué es?**
Describe la acción específica que debe realizar el modelo. Debe representar una única acción clara y concreta (acción atómica), evitando combinar múltiples objetivos en una sola instrucción.

**Objetivo:**
Indicar **qué debe hacer** el modelo.

**Ejemplos:**

* Resume el documento en cinco puntos clave.
* Traduce el texto al inglés.
* Clasifica el sentimiento del comentario.
* Extrae las entidades mencionadas.
* Genera una lista de requisitos funcionales.
* Reescribe el texto con un tono profesional.

---

## F (Formato y Restricciones)

**¿Qué es?**
Define cómo debe presentarse la respuesta y cuáles son las reglas que el modelo debe respetar.

**Objetivo:**
Especificar **cómo debe entregarse** el resultado.

**Puede incluir:**

* Formato de salida (Markdown, JSON, tabla, HTML, lista, etc.).
* Tono (profesional, técnico, académico, amigable, formal, etc.).
* Extensión (número de palabras, párrafos, caracteres o secciones).
* Reglas de negocio (prioridades, validaciones, restricciones, políticas o condiciones).

**Ejemplo:**

* Formato: Markdown con títulos y listas.
* Tono: Profesional y objetivo.
* Extensión: Máximo 500 palabras.
* Restricciones:

  * No inventar información.
  * Utilizar únicamente el contexto proporcionado.
  * Si faltan datos, indicarlo explícitamente.
  * Priorizar la información más relevante.

---

# Resumen

El framework **RCTF** organiza un prompt en cuatro componentes fundamentales:

| Componente                      | Pregunta que responde       | Función                                                                                 |
| ------------------------------- | --------------------------- | --------------------------------------------------------------------------------------- |
| **R (Rol)**                     | ¿Quién eres?                | Define la identidad y experiencia del modelo.                                           |
| **C (Contexto)**                | ¿En qué escenario trabajas? | Proporciona la información necesaria para comprender la situación.                      |
| **T (Tarea)**                   | ¿Qué debes hacer?           | Especifica la acción concreta que debe ejecutar el modelo.                              |
| **F (Formato y Restricciones)** | ¿Cómo debes responder?      | Establece el formato, el tono, la extensión y las reglas que debe cumplir la respuesta. |
