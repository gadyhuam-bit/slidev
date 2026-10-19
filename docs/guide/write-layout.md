# Writing Layouts

> Please read <LinkInline link="guide/layout" /> first.

---
marp: true
theme: default
paginate: true
---

# Elementos de la Composición Tipográfica

**Legibilidad, kerning, tracking, interlineado, jerarquías y retículas**

Duración: 8 horas  
Resultado: Discriminar los elementos que se aplican en la composición tipográfica.

<!-- Nota: Imagen de fondo sugerida: revista o catálogo abierto con tipografía grande. -->

---

# Objetivos y saberes

**Saberes:**
- Legibilidad
- Kerning
- Tracking
- Ajuste óptico
- Interlineado
- Jerarquías tipográficas
- Tamaño y peso

**Resultado esperado:**  
Aplicar correctamente los elementos de la composición tipográfica en productos gráficos editoriales y multimedia.

---

# ¿Qué es la composición tipográfica?

- Es el proceso de organizar tipografías para que un mensaje sea **legible, coherente y visualmente atractivo**.
- Aplica en medios impresos: revistas, catálogos, periódicos.
- Aplica en medios digitales: banners, sitios web, redes sociales.
- Una buena composición **guía la lectura** y jerarquiza la información.

<!-- Nota: Mostrar ejemplos de revistas, catálogos y banners digitales. -->

---

# Elementos clave (parte 1)

| Elemento | Definición breve |
|----------|------------------|
| **Legibilidad** | Facilidad con que un texto puede ser leído y comprendido. |
| **Kerning** | Ajuste del espacio entre pares de letras específicas. |
| **Tracking** | Ajuste uniforme del espaciado entre todas las letras de una palabra o párrafo. |
| **Ajuste óptico** | Corrección manual del espaciado para lograr equilibrio visual. |

---

# Elementos clave (parte 2)

| Elemento | Definición breve |
|----------|------------------|
| **Interlineado** | Distancia entre líneas de texto. Afecta directamente la legibilidad. |
| **Jerarquías** | Organización visual del texto según su importancia: título, subtítulo, cuerpo, destacados. |
| **Tamaño** | Dimensión de la tipografía; establece niveles de lectura. |
| **Peso** | Grosor de los trazos: light, regular, bold, black. |

---

# Momento 1: Inicio (1 hora)

## Actividad inicial: Observación y análisis

**Actividades:**
- Presentación de referentes visuales: revistas, catálogos, periódicos y banners digitales.
- Identificación guiada de:
  - Jerarquías tipográficas
  - Interlineado
  - Alineación
  - Peso y tamaño
- Lluvia de ideas: **¿Qué hace que un texto sea legible y coherente?**

**Evidencia:** Participación oral y análisis inicial.

---

# Momento 2: Desarrollo — Bloque A (2 horas)

## Ajustes tipográficos

**Ejercicios prácticos:**
- **Kerning:** pares problemáticos como AV, To, Wa, Ya.
- **Tracking:** mejorar la lectura en párrafos y títulos.
- **Interlineado:** variaciones y análisis de impacto en legibilidad.
- **Jerarquías:** construcción de título, subtítulo, cuerpo y destacados.

<!-- Nota: Realizar ejercicios en papel o software: Illustrator, InDesign, Figma. -->

---

# Kerning vs. Tracking

## Diferencias visuales

- **Kerning:** ajuste entre pares específicos.
  - Ejemplo: A V → A V (sin kerning) vs. AV (con kerning).
- **Tracking:** ajuste global del espaciado.
  - Ejemplo: TEXTO (tracking normal) vs. T E X T O (tracking amplio).

<!-- Nota: Mostrar comparativas lado a lado con tipografía grande. -->

---

# Momento 2: Desarrollo — Bloque B (2 horas)

## Retículas y mini layouts

**Contenidos:**
- **Retículas:** columnas, márgenes, módulos y líneas de flujo.
- Construcción de retículas simples: 2, 3 o 4 columnas en papel o software.
- Aplicación en un **mini layout**: portada, catálogo, ficha o banner.

**Evidencia:** Ejercicios de composición y mini layouts diagramados.

---

# ¿Cómo se ve una retícula?

- **Columnas:** dividen el espacio verticalmente.
- **Márgenes:** espacio de respiro alrededor del contenido.
- **Módulos:** unidades que organizan la información.
- **Líneas de flujo:** guían la lectura del ojo humano.

<!-- Nota: Insertar diagrama de una retícula de 3 columnas con márgenes marcados. -->

---

# Momento 3: Cierre (3 horas)

## Propuesta de mejora creativa

**Actividades:**
1. Selección de un producto gráfico existente: banner, portada, catálogo o flyer.
2. Propuesta de mejora aplicando:
   - Jerarquías tipográficas
   - Ajustes de espaciado: kerning, tracking, interlineado
   - Retícula
3. Presentación breve justificando las decisiones tipográficas.

**Evidencia:** Propuesta de innovación aplicada y presentación final.

---

# Criterios de evaluación

- **Participación oral** en el análisis inicial.
- **Ejercicios de composición:** kerning, tracking, interlineado, jerarquías.
- **Mini layouts diagramados** con retícula aplicada.
- **Propuesta de mejora** creativa y coherente.
- **Presentación final** con justificación de decisiones.

<!-- Nota: Estos criterios son coherentes con el desarrollo del cotidiano 3. -->

---

# Ideas clave para recordar

- La **legibilidad** es el objetivo principal de toda composición tipográfica.
- **Kerning** y **tracking** controlan el espaciado con propósitos distintos.
- El **interlineado** adecuado facilita la lectura prolongada.
- Las **jerarquías** organizan la información y guían al lector.
- La **retícula** estructura el espacio y da coherencia al diseño.

---

# ¿Preguntas? ¿Comentarios?

**Recuerda:**
- La composición tipográfica es una habilidad que se perfecciona con la práctica.
- Analiza críticamente los productos gráficos que consumes a diario.

**¡Gracias por tu participación!**

Layouts are Vue components, so you can use all the features of Vue in them.

In the layout component, use `<slot/>` (the default slot) for the slide content:

```vue [default.vue]
<template>
  <div class="slidev-layout default">
    <slot />
  </div>
</template>
```

You can also have [named slots](https://vuejs.org/guide/components/slots.html) for more complex layouts:

```vue [split.vue]
<template>
  <div class="slidev-layout split">
    <div class="left">
      <slot name="left" />
    </div>
    <div class="right">
      <slot name="right" />
    </div>
  </div>
</template>
```

And then use it with <LinkInline link="features/slot-sugar" />.
