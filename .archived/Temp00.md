---
marp: true
theme: uncover
class: invert # Fondo oscuro, texto claro por defecto con uncover
style: |
  :root {
    --font-main: 'Duplet', sans-serif;
    --font-heading: 'RecifeDisplay SemiBold', 'RecifeDisplay', serif; /* 'RecifeDisplay SemiBold' primero */
    
    --color-foreground-default: #4F0B3D; /* Color de texto general sobre fondos oscuros */
    --color-background-default: #222222; /* Color de fondo si no hay imagen */
    
    --color-title-main: #ffffff;         /* Blanco para títulos principales */
    --color-title-topic: #FE004E;        /* Rosa para títulos de tema */
    --color-custom-purple:rgb(255, 255, 255);      /* Tu color morado original, por si lo necesitas */
  }

  section {
    font-family: var(--font-main);
    color: var(--color-foreground-default); /* Texto general claro */
  }

  h1, h2, h3, h4, h5, h6 {
    font-family: var(--font-heading);
    color: var(--color-title-main); /* Color por defecto para H1, se puede sobrescribir */
  }
  
  /* Estilo para títulos principales y de sesión (blancos) */
  h1 {
    /* Estilos generales para H1 si son necesarios, ya cubiertos arriba */
  }

  /* Clase para diapositivas con título de tema/subpunto (rosa) */
  section.topic-title h1 {
    color: var(--color-title-topic);
  }

  /* Ajuste específico para el título de Subindicador */
  section.subindicator-title h1 {
    font-size: 56px;
    color: var(--color-title-main); /* Blanco */
  }
  
  /* Estilo para los temas en la lista de "Subindicador" */
  section.subindicator-title ul li {
    /* Si necesitas un estilo específico para estos items */
  }

  /* Estilo para las fuentes consultadas */
  section.sources-slide h1 {
    color: var(--color-title-main); /* Blanco para "Fuentes Consultadas" */
  }
  section.sources-slide ul li {
    font-family: var(--font-heading); /* Usar la fuente de encabezado para las referencias */
    color: var(--color-title-main);   /* Texto blanco para las referencias */
  }

  /* Si necesitas que el texto normal sea morado en diapositivas no invertidas
     o en elementos específicos que no sean invertidos por `class: invert`
  section.normal-text {
    color: var(--color-custom-purple);
  }
  */


---

<!-- backgroundImage: url('../image/bg1.JPG') -->

<!-- _class: main-title -->

# Inteligencia Artificial Aplicada

---

<!-- backgroundImage: url('../image/bg2.JPG') -->

<!-- _class: main-title -->

# N Sesión

---

<!-- backgroundImage: url('../image/bg2.JPG') -->

<!-- _class: subindicator-title -->

# Subindicador N°: Prompt para animaciones con IA

**Temas:**

* Imagen de entrada
* Cuatro parámetros clave
* Ejemplos aplicados

---

<!-- backgroundImage: url('../image/bg3.JPG') -->

<!-- _class: topic-title -->

# Introducción al Prompt Visual

---

<!-- backgroundImage: url('../image/bg4.JPG') -->

<!-- _class: topic-title -->

# ¿Qué es un prompt animado?

Un mensaje estructurado que guía a la IA en la creación de contenido visual en movimiento.

---

<!-- backgroundImage: url('../image/bg5.JPG') -->

<!-- _class: topic-title -->

# Elemento indispensable: Imagen base

---

<!-- backgroundImage: url('../image/bg5.JPG') -->

<!-- _class: topic-title -->

# Opciones de entrada visual

* Imagen cargada externamente
* Imagen generada en la herramienta

---

<!-- backgroundImage: url('../image/bg3.JPG') -->

<!-- _class: topic-title -->

# Parámetros esenciales del prompt

---

<!-- backgroundImage: url('../image/bg4.JPG') -->

<!-- _class: topic-title -->

# 1. Movimiento del sujeto

Ej: camina, gira, corre, flota

---

<!-- backgroundImage: url('../image/bg5.JPG') -->

<!-- _class: topic-title -->

# 2. Movimiento de cámara

Ej: paneo lateral, zoom frontal, travelling

---

<!-- backgroundImage: url('../image/bg5.JPG') -->

<!-- _class: topic-title -->

# 3. Descripción de la escena

Contexto, fondo, ambientación, iluminación

---

<!-- backgroundImage: url('../image/bg5.JPG') -->

<!-- _class: topic-title -->

# 4. Estilo visual de salida

Ej: realismo, anime, acuarela, cyberpunk

---

<!-- backgroundImage: url('../image/bg3.JPG') -->

<!-- _class: topic-title -->

# Ejemplo básico (débil)

"Un gato caminando en la nieve"

---

<!-- backgroundImage: url('../image/bg4.JPG') -->

<!-- _class: topic-title -->

# Ejemplo estructurado (fuerte)

"Un gato blanco caminando lentamente por un callejón nevado, cámara lenta desde atrás, estilo realismo mágico"

---

<!-- backgroundImage: url('../image/bg5.JPG') -->

<!-- _class: topic-title -->

# Variación temática

"Una nave despega en medio de una tormenta eléctrica, cámara contrapicada, estilo cyberpunk"

---

<!-- backgroundImage: url('../image/bg5.JPG') -->

<!-- _class: topic-title -->

# Prompt plantilla sugerida

```
[Elemento central] + [acción] + [mov. cámara] + [ambiente] + [estilo]
```

---

<!-- backgroundImage: url('../image/bg5.JPG') -->

<!-- _class: topic-title -->

# Diagrama de flujo básico

```
[Imagen Base]
     ↓
[Prompt completo]
     ↓
[Motor de IA]
     ↓
[Animación final]
```

---

<!-- backgroundImage: url('../image/bg6.JPG') -->

<!-- _class: sources-slide -->

# Fuentes Consultadas

* RunwayML
* Pika Labs
* Kaiber
* Deforum
* AnimateDiff
