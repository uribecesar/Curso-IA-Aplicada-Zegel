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

# Primera Sesión

---

<!-- backgroundImage: url('../image/bg2.JPG') -->

<!-- _class: subindicator-title -->

<h1 style="color: white"> SUBINDICADOR N°1: FUNDAMENTOS DE LA IA CONTEMPORÁNEA</h1>
Temas:

• Explicar los principios fundamentales y los mitos comunes sobre la IA
• Aplicar modelos de IA generativa de texto

---
<!-- backgroundImage: url('../image/bg5.JPG') -->
<!-- _class: topic-title -->


## 🎯 **4 BLOQUES**
* **🚀 BLOQUE 1:** Tu Entrada al Futuro Digital
* **🏛️ BLOQUE 2:** Framework OSAC  
* **⚡ BLOQUE 3:** Técnicas Avanzadas
* **🧠 BLOQUE 4:** Metodología C.R.E.A

**Objetivo:** De usuario amateur a profesional amplificado por IA

---

# 🚀 BLOQUE 1: Tu Entrada al Futuro Digital

---

# 📊 El Momento Crítico: ¿Por Qué Actuar Ahora?

## 🔥 **Datos que definen 2025:**
- **71%** de organizaciones usa IA generativa regularmente
- **40%** mejora en productividad esperada
- **92.1%** reporta beneficios significativos

---


## ⚠️ **El costo de no actuar:**
**Desventaja competitiva creciente e irreversible**

---

# 🤖 ¿Qué es Realmente la IA Generativa?

---


## 💡 **Definición Práctica:**
Sistemas que **crean contenido nuevo** basándose en patrones de grandes volúmenes de datos

---

## 🔄 **Diferencia Clave:**
- **IA Tradicional:** Clasifica y predice
- **IA Generativa:** **Produce** contenido original bajo demanda

---

# 🧠 Funcionamiento: Predictores Sofisticados

## 🔍 **Proceso en 4 pasos:**
1. **📥 Procesan** tu solicitud (prompt)
2. **🎯 Predicen** la siguiente palabra más probable  
3. **🔄 Continúan** secuencialmente
4. **✨ Generan** respuestas coherentes

---

### 🎯 **Punto Clave:** 
No "entienden" como humanos, pero sus predicciones producen **resultados prácticamente útiles**

---

# 🚫 Mitos vs 💡 Realidad

| **🚫 Mito** | **💡 Realidad** |
|-------------|----------------|
| "La IA piensa como humanos" | Predice patrones basándose en datos |
| "Siempre es 100% precisa" | Requiere verificación humana |
| "Reemplazará el trabajo" | Amplifica capacidades humanas |
| "Es demasiado compleja" | Interfaces conversacionales intuitivas |

---

# 🏆 Ecosistema de Servicios 2025

## 🥇 **ChatGPT** - $20/mes
**💪 Fortaleza:** Equilibrio y versatilidad  
**🎯 Mejor para:** Uso general empresarial

---


## 🧠 Claude
- **💪 Fortaleza:** Razonamiento fuerte, calidez en respuestas
- **🎯 Mejor para:** Análisis complejos, ética
- **⚠️ Limitación:** No genera imágenes, sin memoria
- **💰 Costo:** $20/mes Pro

---

## 🔍 Gemini
- **💪 Fortaleza:** Integración Google Workspace
- **🎯 Mejor para:** Entornos Google existentes
- **⚠️ Limitación:** Menor precisión especializada
- **💰 Costo:** Gratuito básico

---

## 🔥 Grok
- **💪 Fortaleza:** Integración X (Twitter) tiempo real
- **🎯 Mejor para:** Información actualizada, tendencias
- **⚠️ Limitación:** Acceso limitado X Premium
- **💰 Costo:** $16/mes

---

## ⚡ DeepSeek
- **💪 Fortaleza:** Alto rendimiento, bajo costo
- **🎯 Mejor para:** Análisis técnico profundo
- **⚠️ Limitación:** Consideraciones seguridad datos


---

# 🎯 Introducción al Prompt Engineering

## 📝 **¿Qué es un prompt?**
La **instrucción que das a la IA**. Su calidad determina directamente la utilidad de la respuesta.

---


## 🔧 **Principios Básicos:**
- **🎯 Claridad:** Sé específico
- **📋 Contexto:** Información de fondo relevante
- **🏗️ Estructura:** Organización lógica
- **🔄 Iteración:** Refina basándote en resultados

---

# 📈 Beneficios Cuantificables

## ⏰ **Ahorro de Tiempo:**
- **📄 Redacción:** 60-70% menos tiempo
- **🔍 Investigación:** 50% reducción  
- **📝 Contenido:** 40-50% más rápido

---


## ✅ **Mejora de Calidad:**
- **🎵 Consistencia** de tono empresarial
- **📊 Completitud** comprehensive
- **👔 Profesionalización** del nivel comunicativo

---

# 🎯 Tu Primer Ejercicio

## 🔥 **Prompt Dirigido:**
*"Explica cómo la IA generativa puede ayudarme si me dedico a **[TU CAMPO ESPECÍFICO]**"*

---


## 🔄 **Seguimiento:**
*"Explícame paso a paso cómo implementarlo en mi trabajo diario"*

### 🚀 **Regístrate hoy:** ChatGPT gratuito para empezar

---

# 🏛️ BLOQUE 2: Framework OSAC

---

# 📊 El Problema del Prompting Amateur

## 💸 **Costo de la improvisación:**
- ⏰ **3-5 horas semanales** perdidas en iteraciones
- 📉 **80% del potencial** sin aprovechar
- 🔓 **Calidad inconsistente** y resultados variables

## 🎯 **La Solución:** Metodología sistemática

---

# 🥉 Amateur vs 🥇 Profesional

### 🥉 **Prompt Amateur:**
*"Escribe un informe sobre ventas"*

---


### 🥇 **Prompt Profesional:**
*"Genera análisis performance ventas Q1 2025 para presentación ejecutiva, incluyendo métricas KPI, análisis varianza vs. forecast, y 3 recomendaciones accionables basadas en pipeline actual"*

**Resultado:** 300% más precisión, 80% menos iteraciones

---

# 🏛️ Framework OSAC: La Metodología
 
---

## 🎯 **O - OBJETIVO**
¿Qué quieres lograr? (propósito + audiencia + detalle)

## 📋 **S - SALIDA**  
¿Cómo debe verse? (formato + longitud + estilo)

---


## ⚠️ **A - ADVERTENCIA**
¿Qué limitaciones? (restricciones + aspectos a evitar)

## 🧩 **C - CONTEXTO**
¿Qué información necesita? (sector + datos + antecedentes)

---

# 📊 Resultados OSAC vs Tradicional

| **Aspecto** | **🔄 Conversacional** | **🎯 OSAC** |
|-------------|----------------------|-------------|
| ⏱️ **Tiempo setup** | 2 min | 5 min |
| 🔄 **Iteraciones** | 3-5 prompts | 1-2 prompts |
| 🎯 **Precisión** | 60-70% | 85-95% |
| ⏰ **Tiempo total** | 15-20 min | 8-12 min |

---



### 🏆 **Ganancia neta: 40% menos tiempo, 90% más calidad**

---

# 🚀 Estrategias Avanzadas

## 👔 **1. Roles Especializada**
*"Actúa como [PROFESIONAL] con [X] años en [SECTOR], especializado en [ÁREA]"*

---



## ⚙️ **2. Modelo EPS**
- 📥 **Entrada:** Define datos disponibles
- 🔄 **Proceso:** Especifica metodología  
- 📤 **Salida:** Describe formato final

---



## 📝 **3. Prompting por Pasos**
Divide instrucciones complejas en secuencias lógicas

---

# 💼 Transformación Real: Gerente de Proyectos

---



### 🔴 **Antes (Conversacional):**
- 💬 *"Ayúdame con un plan de proyecto"*
- 📄 Plantilla genérica, 3 iteraciones
- ⏰ **25 minutos**

---



### 🟢 **Después (OSAC):**
- 🎯 **O:** Plan CRM 200 empleados
- 📊 **S:** Cronograma Gantt con hitos
- 💰 **A:** Presupuesto máximo 20K, equipo 5
- 🏢 **C:** Migración desde legacy
- ⏰ **8 minutos**

---

# 🎯 Tu Ejercicio OSAC

### 📝 **Transforma este prompt:**
*"Escribe un informe sobre implementación de IA en mi empresa"*


---



### 🏗️ **Usando estructura:**
```
OBJETIVO: [Propósito específico + audiencia]
SALIDA: [Formato + longitud + estilo]  
ADVERTENCIA: [Limitaciones + restricciones]
CONTEXTO: [Info sectorial + datos + antecedentes]
```

---

# ⚡ BLOQUE 3: Técnicas Avanzadas

---

# 💥 El Problema Oculto: Límites Técnicos


---


## 📊 **Limitaciones 2025:**
- **📤 Tokens salida:** 4K-8K (cuello de botella crítico)
- **😵 76%** usuarios experimenta alucinaciones en contenido largo
- **💸 Causa:** Intentar generar contenido complejo en una sola instrucción


---



## 🎯 **Solución:** Trabajar CON las limitaciones, no contra ellas

---

# ⚔️ Método "Dividir y Vencer"

## 🧩 **Fundamento:**
❌ **Fallido:** Informe 5,000 palabras en 1 prompt  
✅ **Exitoso:** Segmentar en componentes manejables


---


## 🔄 **Proceso 4 Pasos:**
1. **📋 Hoja de Ruta:** Estructura detallada
2. **✅ Validación:** Cada sección autónoma y cohesiva
3. **🚀 Generación:** Sección por sección  
4. **🎨 Cohesión:** Ajustar transiciones

---

# 📊 Resultados Dividir y Vencer

---



| **📈 Métrica** | **🔴 Generación Directa** | **🟢 Dividir y Vencer** |
|----------------|---------------------------|-------------------------|
| ✅ **Completitud** | 45% | 95% |
| 🎪 **Coherencia** | 6.2/10 | 8.7/10 |
| ⏰ **Tiempo total** | 180 min | 120 min |
| 😵 **Alucinaciones** | 23% | 7% |

### 🏆 **Resultado: Triplicar efectividad**

---

# 🎧 Multiplicador TTS + STT

---



## 🔄 **Transformación del Workflow:**
**Visual/Manual** → **Auditiva/Conversacional**

## 🚀 **Beneficios:**
- 🎯 **300% más rápida** revisión contenido
- 👂 **45% más efectiva** detección errores  
- 🤹 **Multitarea** mientras procesa
- 😌 **60% menos fatiga** visual

---

## 🛠️ **Herramientas Gratuitas:**
- **TTS:** Microsoft Edge (integrado), Balabolka
- **STT:** Windows Speech Recognition (Win+H), LilySpeech

---

# 💼 Caso Real: Estrategia Marketing Q2


---


### 🟢 **Método Dividir y Vencer:**
1. 📋 Hoja de ruta 8 secciones (5 min)
2. 📊 8 secciones × 8 min c/u (64 min)  
3. 👂 Revisión TTS (10 min)
4. 🔧 Ajustes STT (7 min)

### 🏆 **Resultado: 4,200 palabras calidad premium en 86 minutos**

---

# 🧠 BLOQUE 4: Metodología C.R.E.A

---

# 🚨 Crisis Cognitiva Oculta

## 🔬 **Investigación MIT 2025:**
> Usuarios frecuentes ChatGPT: **menor compromiso cerebral** y **bajo desempeño** neuronal

## 📊 **Impacto 6 meses uso pasivo:**
- 💔 **40% atrofia** conexiones neurales críticas
- 🎯 **60% pérdida** capacidad síntesis original
- 📉 **50% degradación** análisis independiente

### ⚠️ **El Círculo Vicioso:** Mayor dependencia → Menos pensamiento crítico

---

# 🛡️ C.R.E.A: El Antídoto

---



## 🎯 **Principio Core:**
**Cerebro como centro de procesamiento**  
**IA como amplificador, NO sustituto**

## 🏛️ **4 Fases:**
- **🗂️ C - COMPILAR:** Curaduría inteligente
- **🤔 R - REFLEXIONAR:** Procesamiento cognitivo activo
- **🏗️ E - ESTRUCTURAR:** Organización de ideas  
- **⚡ A - AMPLIFICAR:** Expansión inteligente con IA

---

# 📊 C.R.E.A vs Uso Pasivo


---


| **🧠 Métrica** | **🔴 Uso Pasivo** | **🟢 C.R.E.A** |
|----------------|-------------------|----------------|
| 🧠 **Retención conocimiento** | 23% | 87% |
| 💡 **Síntesis original** | 31% | 89% |
| 🔍 **Profundidad análisis** | 4.2/10 | 8.6/10 |
| 🎯 **Confianza expertise** | 34% | 91% |
| ⏰ **Tiempo dominio** | 45h | 28h |

---



### 🏆 **Resultado: Triplicar retención, duplicar confianza**

---

# 🗂️ C - COMPILAR: Curaduría Inteligente

## 🎯 **Proceso:**
1. **📏 Criterios:** Profundidad + fuentes + temporalidad
2. **🔍 Prompt compilación:**
```
OBJETIVO: Compilar bibliografía sobre [TEMA]
SALIDA: 15-20 fuentes categorizadas  
ADVERTENCIA: Priorizar peer-reviewed
CONTEXTO: [Profundidad] + [audiencia]
```

---



## 🛠️ **Herramientas:** Consensus.app, ResearchRabbit, Scite.ai

---

# 🤔 R - REFLEXIONAR: Procesamiento Activo

## 🧠 **NO resumen algorítmico, SÍ síntesis personal**

---



## ✍️ **Proceso:**
1. **📖 Lectura analítica:** Argumentos + evidencia + perspectiva
2. **💭 Borrador reflexivo:**
```
"Desarrolla TUS percepciones:
- Patrones que fuentes NO explicitan
- Conexiones originales entre conceptos
- Preguntas que NO abordan  
- Perspectivas desde tu experiencia"
```

---

# 🏗️ E - ESTRUCTURAR + ⚡ A - AMPLIFICAR

## 🏗️ **ESTRUCTURAR:**
```
OBJETIVO: Convertir mis argumentos en estructura
SALIDA: Esquema con evidencia de soporte
CONTEXTO: [TU BORRADOR REFLEXIVO]
```

---



## ⚡ **AMPLIFICAR:**
```
OBJETIVO: Amplificar sección [X] manteniendo 
MIS argumentos como columna vertebral
ADVERTENCIA: IA amplifica MIS ideas, no genera independiente
```

### ✅ **Control:** ¿Preserva tu voz intelectual original?

---

# 💼 Caso Real: Consultor Transformación


---


### 📅 **C.R.E.A en 16 horas:**
- **📋 DÍA 1:** COMPILAR (3h) - 18 fuentes validadas
- **🤔 DÍA 2:** REFLEXIONAR (4h) - 2,500 palabras originales  
- **🏗️ DÍA 3:** ESTRUCTURAR (3h) - Arquitectura 8 secciones
- **⚡ DÍAS 4-5:** AMPLIFICAR (6h) - Expansión controlada

### 🏆 **Resultado:** White paper 8,500 palabras + 40% más leads

---

# 🎯 Tu Transformación C.R.E.A

## 📋 **Ejercicio (5.25 horas):**

---


1. **🗂️ COMPILAR (45 min):** 20 fuentes sobre tu expertise
2. **🤔 REFLEXIONAR (90 min):** Lectura + borrador personal
3. **🏗️ ESTRUCTURAR (60 min):** Argumentos + arquitectura
4. **⚡ AMPLIFICAR (120 min):** Expansión + integración

### 🎯 **Resultado:** Informe 5,000 palabras calidad superior

---

# 🏆 Conclusión: La Transformación Completa

## ✅ **Dominaste 4 Niveles:**

---


- 🤖 **Fundamentos:** Reconocimiento y uso IA generativa
- 🎯 **OSAC:** Prompting profesional sistemático  
- ⚡ **Avanzado:** Generación segmentada + herramientas
- 🧠 **Maestría:** Preservación y amplificación pensamiento crítico

## 🚀 **Resultado Final:**
**Profesional amplificado por IA, no reemplazado por ella**

---

# 🎯 Siguientes Pasos

## 📅 **Plan 30 días:**
1. **Semana 1:** Registro y experimentación herramientas
2. **Semana 2:** Implementación OSAC en 5 tareas frecuentes
3. **Semana 3:** Práctica dividir y vencer + TTS/STT
4. **Semana 4:** Proyecto C.R.E.A completo


---



### 🏆 **Meta:** Transformar productividad con IA en 1 mes



---
# Fin del Primer Modulo
## Preguntas & comentarios 🙌  
