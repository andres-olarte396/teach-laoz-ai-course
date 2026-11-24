# Biblioteca de Prompts — Sector Farmacéutico

Este archivo consolida los prompts probados y ajustados durante las sesiones de entrenamiento. Cópialos y reemplaza lo que esté entre `[corchetes]` por tu caso real.

---

## Índice

1. [Prompts de Redacción y Copywriting](#1-prompts-de-redacción-y-copywriting)
2. [Prompts de Análisis de Documentos](#2-prompts-de-análisis-de-documentos)
3. [Prompts de Inteligencia Comercial](#3-prompts-de-inteligencia-comercial)

---

## 1. Prompts de Redacción y Copywriting

*(Sesión 1 — Framework RCTF: Rol, Contexto, Tarea, Formato)*

### 1.1 Copywriting Comercial B2B

```text
Rol: Actúa como un Director de Marketing Farmacéutico Senior especializado en ventas B2B.
Contexto: Estamos promocionando [Categoría/Producto] dirigido a [Audiencia: Médicos/Directores de Farmacia].
Tarea: Redacta una propuesta de correo comercial de 2 pasos para agendar una reunión breve de presentación.
Restricciones: Tono profesional, riguroso y consultivo. No uses adjetivos sensacionalistas ni afirmaciones médicas no verificadas.
Formato: Asunto + Cuerpo en 3 párrafos cortos + Llamado a la acción (CTA) claro.
```

### 1.2 Conversión Técnico-Comercial

```text
Rol: Eres un Copywriter especializado en comunicación médica y farmacéutica.
Contexto: Te comparto el siguiente fragmento técnico de nuestro producto: "[Pegar texto técnico]".
Tarea: Transforma esta información en 3 argumentos de venta clave orientados a beneficios para la fuerza de ventas.
Formato: Lista con viñetas: 1. Beneficio principal, 2. Diferenciador, 3. Manejo de principal objeción.
```

---

## 2. Prompts de Análisis de Documentos

*(Sesión 2 — usar con Custom Instructions activas, ver `Apunte_Sesion_02.md`)*

### 2.1 Resumen Ejecutivo de PDF Técnico

```text
Analiza este documento y extrae un resumen ejecutivo de 5 puntos clave para la fuerza de ventas.
```

### 2.2 Matriz de Argumentos y Objeciones

```text
Con base en el PDF adjunto, genera una tabla con 3 columnas:
[Argumento Médico] | [Traducción a Beneficio Comercial] | [Manejo de Objeción].
```

### 2.3 Extracción de FAQs de Producto

```text
Crea un listado de las 5 preguntas más frecuentes que un cliente o médico haría sobre este producto
y sus respuestas basadas exclusivamente en el texto.
```

---

## 3. Prompts de Inteligencia Comercial

*(Se irá poblando en próximas sesiones: análisis de datos de ventas, GPT personalizado)*
