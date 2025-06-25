---
marp: true
theme: uncover
class: invert # Fondo oscuro, texto claro por defecto con uncover
paginate: true
style: |
  :root {
    --font-main: 'Duplet', sans-serif;
    --font-heading: 'RecifeDisplay SemiBold', 'RecifeDisplay', serif; /* 'RecifeDisplay SemiBold' primero */
    
    --color-foreground-default: #4F0B3D; /* Color de texto general sobre fondos oscuros */
    --color-background-default: #222222; /* Color de fondo si no hay imagen */
    
    --color-title-main: #4F0B3D;         /* Blanco para títulos principales */
    --color-title-topic: #FE004E;        /* Rosa para títulos de tema */
    --color-custom-purple:rgb(255, 255, 255);      /* Tu color morado original, por si lo necesitas */
    --color-custom-white:rgb(255, 255, 255);      /* Tu color morado original, por si lo necesitas */
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
  section.topic-main h1 {
    color: var(--color-custom-white);
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

<!-- _class: topic-main -->

# Inteligencia Artificial Aplicada

---

<!-- backgroundImage: url('../image/bg2.JPG') -->

<!-- _class: topic-main -->

# Sexta Sesión

---

<!-- backgroundImage: url('../image/bg2.JPG') -->

<!-- _class: subindicator-title -->

<h1 style="color: white"> SUBINDICADOR N°6: SISTEMAS DE GESTIÓN DEL CONOCIMIENTO</h1>
Temas:

* Implementa un sistema básico de gestión de conocimiento con capacidades de búsqueda semántica.


---
<!-- backgroundImage: url('../image/bg5.JPG') -->

# 🚀 Marco DESCUBRE
## Redefiniendo tu Gestión de Conocimiento

### ¿Por qué 97% de los Profesionales Resuelven el Problema Equivocado? 🤔

---

# 💡 El Problema Real

**❌ Síntoma:** "Necesito escribir más rápido"  
**✅ Causa Raíz:** "¿Por qué estoy digitalizando manualmente documentos que deberían llegar ya digitales?"


---


### 📊 Crisis Silenciosa (McKinsey 2025):
- ⏰ **1.8 horas diarias** buscando información
- 📈 **37% de tu jornada** perdida en búsquedas

---

# ⚖️ Enfoque Tradicional vs. Marco DESCUBRE


---


| **Optimización Incremental** 🐌 | **Transformación Radical** ⚡ |
|--------------------------------|------------------------------|
| "Escribir más rápido" | "¿Por qué escribo manualmente?" |
| Optimiza pasos existentes | Elimina pasos innecesarios |
| **15% mejora** | **300% transformación** |

---

# 📖 CASO ALEX: Director de Operaciones

**Situación:** 3 horas diarias transcribiendo PDFs físicos
**Costo:** s./6,000 anuales en tiempo perdido


---


### Aplicando DESCUBRE:
**D** - Mapear proceso real completo
**E** - Explorar qué hace la competencia  
**S** - Separar objetivo (archivo editable) del método (transcripción)

**Resultado:** OCR + negociación entrega digital = $72,000 ahorro anual

---

# 🛠️ HERRAMIENTA CONCRETA

## Google NotebookLM como Motor de Descubrimiento


---


### ¿Por qué NotebookLM?
- 🆓 **Gratuito** para uso profesional básico
- 📁 **50 documentos** por notebook
- 🤖 **IA Gemini 2.0** para análisis avanzado
- 👥 **Millones de usuarios** verificados globalmente

---

# ⚡ EJERCICIO 1: Redefinición 5 Por Qués

**Instrucciones:** Toma un proceso frustrante de tu trabajo actual


---


- ❓ ¿Por qué existe este problema?
- ❓ ¿Por qué no se ha resuelto?
- ❓ ¿Por qué asumimos que debe hacerse así?
- ❓ ¿Por qué no exploramos alternativas?
- ❓ ¿Por qué no eliminamos el proceso completo?

---

# 📋 TAREA BLOQUE 1

## Implementación Marco DESCUBRE:


---


1. 📓 **Crear notebook** "Diagnóstico Gestión Conocimiento"
2. 📤 **Subir 3 documentos:** proceso actual, benchmarks, restricciones
3. 🤖 **Consultar NotebookLM:** "Analiza y sugiere 5 alternativas radicales"
4. 🎧 **Generar Audio Overview** para insights móviles

---

# 🏗️ Bloque 2: Construcción del Corpus Profesional
## Del Conocimiento Disperso al Sistema Inteligente


---


### El Problema: 54% de Organizaciones Usan +5 Plataformas Desconectadas

---

# 💡 Fragmentación vs. Estructura

**❌ Problema:** Herramientas dispersas sin arquitectura
**✅ Solución:** Sistema centralizado con conectores inteligentes


---


### 📊 Impacto Medible:
- **75% reducción** tiempo búsqueda
- **$750,000 ahorro** anual (empresa 150 personas)
- **ROI 300-500%** primeros 6 meses

---

# 📖 CASO PATRICIA: Directora Consultoría

**Situación:** 847 documentos dispersos, 5 horas semanales buscando información


---


### Proceso de 3 Fases:
1. **Mapeo:** 23% alta relevancia, 36% obsoleta
2. **Arquitectura:** Taxonomía 5 categorías, 23 subcategorías  
3. **Implementación:** Workflows captura y actualización

**Resultado:** 5 horas → 30 minutos semanales, ROI 311%

---

# 🛠️ Opciones de Implementación

## **Opción A:** Documento Unificado (Recomendado)
- 🔗 Google Docs + NotebookLM
- 📋 Plantillas predefinidas
- 🎯 Ideal para individuales y equipos pequeños


---


## **Opción B:** Sistema Fragmentado Inteligente  
- 🕸️ Obsidian + NotebookLM
- 📝 Markdown estructurado
- 🎯 Ideal para organizaciones grandes

---

# ⚡ EJERCICIO 2: Construcción Taxonomía Personal


---


**Instrucciones:** Diseña la arquitectura de tu conocimiento

- 🗂️ Define **5 categorías principales** de tu conocimiento
- 📋 Establece **3-5 subcategorías** por categoría
- ✅ Crea **criterios clasificación** claros
- 🔄 Diseña **proceso captura** para cada tipo

---

# 📋 TAREA BLOQUE 2

## Construcción Corpus (90 minutos total):


---


**Preparación (30 min):**
1. 📓 Crear notebook "Corpus Profesional [Tu Nombre]"
2. 🗂️ Establecer estructura según taxonomía diseñada

**Construcción (45 min):**
3. 📤 Subir 10 documentos más relevantes
4. 📄 Crear documento maestro con índice


---


**Validación (15 min):**
5. 🔍 Realizar 5 consultas test
6. 📝 Documentar insights y mejoras

---

# 🤖 Bloque 3: Implementación con NotebookLM
## De Corpus a Sistema Inteligente


---


### El Problema: 79% Considera KM Crítico, Solo 1% Tiene Implementación Madura

---

# 💡 Brecha Estrategia-Ejecución

**❌ Problema:** Saben QUÉ necesitan, no CÓMO implementarlo
**✅ Solución:** Metodología sistemática paso a paso


---


### ⚖️ Comparativa Implementación:

| **Desarrollo Tradicional** | **NotebookLM** |
|---------------------------|----------------|
| 6-18 meses | 1-3 días |
| $50,000-200,000 | $0-240 anuales |
| Equipo técnico | Interface intuitiva |

---

# 📖 CASO CARLOS: Director Innovación

**Situación:** 200 empleados, conocimiento disperso, propuestas subóptimas


---


### Implementación Sistemática 3 Semanas:
1. **Semana 1:** Auditoría + arquitectura (1,247 documentos)
2. **Semana 2:** Implementación técnica (847 documentos organizados)
3. **Semana 3:** Validación + capacitación (89% casos cubiertos)

**Resultado:** 78% reducción tiempo investigación, $780,000 nuevos ingresos

---

# 🏗️ METODOLOGÍA PASO A PASO

## Fase 1: Marco EVALÚA (1 día)


---


**E** - **Evaluar** contexto organizacional y stakeholders
**V** - **Valorar** idoneidad NotebookLM vs alternativas  
**A** - **Analizar** impacto proyectado y métricas éxito


---


## Fase 2: Arquitectura Técnica (2 días)
- Notebooks especializados por área
- Taxonomía organizacional escalable
- Workflows automatizados

---

# ⚡ EJERCICIO 3: Diseño Arquitectura NotebookLM

**Instrucciones:** Crea el blueprint para tu organización


---


- 🏗️ **Estructura notebooks** por área funcional
- 🔄 **Flujos información** entre departamentos  
- 👥 **Roles y permisos** por tipo usuario
- 📅 **Cronograma implementación** realista

---


# 🚀 Bloque 4: Optimización y Escalabilidad
## Evolución Profesional con IA


---


### El Problema: 69% Considera IA Esencial, Solo 25% Obtiene Ventaja Competitiva Real

---

# 💡 Adopción vs. Dominio

**❌ Problema:** Tener tecnología ≠ ventaja competitiva
**✅ Solución:** Optimización estratégica inteligente


---


### 💰 Multiplicación de Valor:
- **8.57-11.19% incremento salarial** con habilidades IA
- **$300,600 compensación promedio** ingenieros IA
- **40% más ingresos** empresas con personalización

---

# 📖 CASO DIANA: Directora Estrategia Digital

**Situación:** NotebookLM básico, plateau de valor, falta insights predictivos


---


### Optimización Avanzada 6 Semanas:
1. **Sem 1-2:** Knowledge graphs + taxonomías dinámicas
2. **Sem 3-4:** Personalización inteligente + predictive analytics  
3. **Sem 5-6:** Integración ecosistémica + real-time insights


---


**Resultado:** 89% reducción mantenimiento, $2.3M valor primer año

---

# 🎯 ROADMAP EVOLUCIÓN PROFESIONAL IA



---

## **Nivel 1: IA Literacy** (Mes 1-2)
- Fundamentos matemáticos básicos
- Python esencial para análisis
- Conceptos ML fundamentales



---

## **Nivel 2: IA Application** (Mes 3-6)  
- Implementación algoritmos reales
- Integración APIs IA existentes
- Prototipos casos uso específicos


---


## **Nivel 3: IA Strategy** (Mes 7-12)
- Sistemas escalables y éticos
- Liderazgo transformación digital

---

# ⚡ EJERCICIO 4: Diseño Roadmap Personal IA



---

**Instrucciones:** Crea tu plan evolución específico

- 🎯 **Especialización IA** alineada con tu carrera
- 📅 **4 milestones trimestrales** medibles
- 🛠️ **Proyectos demostración** por trimestre
- 👥 **Mentores y recursos** por fase

---

# 📋 TAREA BLOQUE 4

## Coach Evolución Personal (12 horas en 2 semanas):

**Semana 1 (6 horas):** Configuración
1. Crear notebook "Evolución Profesional IA 2025"
2. Subir CV, roles objetivo, análisis industria
3. Configurar taxonomía evolución profesional


---


**Semana 2 (4 horas):** Desarrollo roadmap
4. Generar análisis gaps competenciales
5. Diseñar plan aprendizaje trimestral específico



---

**Ongoing (2 horas semanales):** Implementación
6. Documentar progreso y ajustar roadmap

---

# 📊 MÉTRICAS DE ÉXITO INTEGRADAS

## **Inmediatas (1 mes):**
- 50% reducción tiempo búsqueda
- 80% automatización tareas rutinarias


---


## **Mediano Plazo (3 meses):**
- 60% incremento identificación oportunidades
- ROI sistema >300%


---


## **Estratégicas (6-12 meses):**  
- Incremento salarial 8-15% competencias IA
- Top 10% profesionales sector por ventaja IA

---

# 🎯 CONCLUSIÓN: Tu Ventaja Competitiva Irreversible


---


### 📈 Has completado tu transformación:
1. 🔍 **Marco DESCUBRE:** Redefine problemas
2. 🏗️ **Corpus Profesional:** Estructura conocimiento  
3. 🤖 **Implementación NotebookLM:** Sistema inteligente
4. 🚀 **Optimización:** Evolución profesional continua


---


### ❓ Pregunta Final:
**¿Tu evolución será dirigida por insights inteligentes o limitada por métodos obsoletos?**


---
# Fin del Sexto Modulo
## Preguntas & comentarios 🙌  
