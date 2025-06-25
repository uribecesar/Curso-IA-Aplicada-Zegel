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

# Cuarta Sesión

---

<!-- backgroundImage: url('../image/bg2.JPG') -->

<!-- _class: subindicator-title -->

<h1 style="color: white"> SUBINDICADOR N° 4: ÉTICA, PROMPT ENGINEERING AVANZADO Y AUTOMATIZACIÓN
</h1>
Temas:

* Automatización inteligente con Google Apps Script
* Agentes IA especializados con Gemini Gems
* Estrategias multiplataforma GPTs vs Gems


---

<!-- backgroundImage: url('../image/bg5.JPG') -->

# 🚀 AUTOMATIZACIÓN INTELIGENTE
## Google Apps Script + IA Generativa


---


### El Escenario Actual
- **60%** empresas ya automatizan procesos rutinarios
- **Brecha competitiva**: 30% aún procesa datos manualmente


---


### Por Qué Apps Script
✅ JavaScript en servidores Google  
✅ Sin instalación ni configuración  
✅ Integración nativa con Workspace  

---

# 📊 CASO REAL: ALEJANDRA (CFO)

### El Problema
**6 horas semanales** consolidando reportes financieros
- Formularios papel dispersos
- 2-3 horas adicionales corrigiendo errores
- Reportes con retraso constante

---


### La Solución (2 horas con IA)
Formulario → Apps Script → Dashboard automático

### El Resultado
**6h → 30min/semana** • **85% menos errores** • **$3,600 ahorrados**

---

# 💼 EJERCICIO 1: SISTEMA FINANCIERO

**Tu misión:** Automatizar registro de ingresos/egresos

```
"Genera código Google Apps Script para: 
1) Formulario con campos fecha, tipo, categoría, monto
2) Validaciones automáticas en hoja de cálculo
3) Email cuando gasto > $500
4) Resumen semanal automático
Incluye instrucciones paso a paso."
```


---


**Tiempo:** 30 minutos implementación  
**Entregable:** Sistema funcionando con datos reales

---

# 🤖 AGENTES IA ESPECIALIZADOS
## Gemini Gems para Marketing


---


### El Salto Evolutivo
De herramientas → **Sistemas autónomos que razonan**


---


### Productividad Documentada
- **79%** especialistas optimizan procesos
- **42%** mayor eficiencia con datos estructurados
- **5+ horas semanales** ahorradas por especialista

---

# 📱 METODOLOGÍA ENTRADA-PROCESO-SALIDA


---


### Framework para Agentes Efectivos

**🔴 ENTRADA** - Datos específicos
- Parámetros claros
- Contexto (audiencia, objetivo)
- Referencias (brand guidelines)

---


**🟡 PROCESO** - Lógica estructurada  
- Pasos de análisis secuencial
- Criterios de evaluación
- Conocimiento especializado


---


**🟢 SALIDA** - Entregables actionables
- Formato consistente
- Métricas incluidas
- Opciones de mejora

---

# 💼 EJERCICIO 2: LINKEDIN CONTENT PRO

**Crea tu Gema especializada usando EPS:**

```
"Diseña Gema 'LinkedIn Content Pro':

ENTRADA: Tema, audiencia (C-level/managers), objetivo
PROCESO: Research tendencias + tone empresa + hook + argumentos + CTA
SALIDA: Post 150-200 palabras + hashtags + predicción engagement + 3 variaciones A/B

Incluye instrucciones exactas configuración."
```


---


**Entregable:** Gema funcionando + 5 posts generados

---

# ⚔️ ESTRATEGIA MULTIPLATAFORMA
## GPTs vs Gems: Dominio Dual


---


### Realidad del Mercado
- **ChatGPT**: 59.5% participación + 600M usuarios
- **Gemini**: 400M usuarios activos mensuales
- **Riesgo**: Dependencia de una sola plataforma


---


### Especialización Natural
- **GPTs**: Creatividad + conversación + DALL-E
- **Gems**: Análisis + Google ecosystem + datos tiempo real

---

# 🔄 CASO ROBERTO: ESTRATEGIA DUAL

### El Desafío
Director Operaciones limitado a ChatGPT únicamente
- Sin integración Google Workspace
- Research competitivo desactualizado
- Falta de redundancia operativa

---


### La Implementación
**Semana 1:** Replicar 3 GPTs como Gems equivalentes
**Semana 2:** Especializar según fortalezas naturales
**Semana 3:** Sistema backup automático

### Resultado
**45%** velocidad propuestas • **100%** uptime • **$23,400** ahorrados

---

# 💼 EJERCICIO 3: REPLICACIÓN ESTRATÉGICA

**Domina ambos ecosistemas:**


---


```
"Toma tu GPT más valioso y crea equivalente Gem:
1) Analiza funciones específicas (entrada-proceso-salida)
2) Identifica mejoras con fortalezas Gemini
3) Implementa usando metodología EPD
4) Documenta diferencias rendimiento
5) Estrategia uso complementario según contexto"
```

**Entregable:** Mismo resultado por ambas plataformas + análisis comparativo

---

# 🎭 PERSONALIZACIÓN AVANZADA
## De Genéricos a Especialistas


---


### La Brecha de Adopción
- **71%** organizaciones usan IA generativa
- **Solo 12%** integración organizacional real
- **Diferencia clave**: Usuarios casuales vs. especialización avanzada

---


### Impacto Measurable
- **Precisión contextual**: 85-95% vs. 60-70% genéricos
- **ROI mensual**: $1,500-3,000 vs. $200-500
- **Valor profesional**: Soluciones específicas vs. tareas básicas

---

# 🎯 PLANTILLA ESPECIALIZACIÓN


---


### Estructura Completa
```
IDENTIDAD PROFESIONAL:
- Rol: [Título + contexto industria]
- Experiencia: [Años + logros + perspectiva única]
- Valores: [Principios guiando decisiones]

EXPERTISE TÉCNICA:
- Conocimientos: [Dominio específico]
- Metodologías: [Frameworks utilizados]
- Métricas: [KPIs y medidas éxito]

ESTILO COMUNICACIÓN:
- Tono: [Formal/casual, directo/consultivo]
- Estructura: [Organización respuestas]
- Restricciones: [Límites éticos/operacionales]
```

---

# 💼 EJERCICIO 4: AGENTE ESPECIALIZADO

**Crea tu versión IA profesional:**


---


```
"Diseña agente completamente especializado para tu función:
1) PERSONALIDAD: Características específicas
2) EXPERTISE: Conocimientos técnicos + terminología
3) CONTEXTO: Entorno trabajo + stakeholders
4) ESTILO: Comunicación según audiencia
5) RESTRICCIONES: Límites éticos/operacionales

Implementa y documenta diferencias vs. genérico en 3 tareas."
```

**Entregable:** Agente especializado + comparativa performance

---

# 🎯 CONCLUSIÓN ESTRATÉGICA

### Los Datos Hablan
- **336% ROI** automatización (Forrester)
- **4.2x ROI** IA especializada vs. genérica
- **Early adopters** establecen ventajas sostenibles

---


### Tu Ventaja Competitiva
**No es si puedes automatizar, sino qué tan rápido lo implementas**


---
# Fin del Cuarto Modulo
## Preguntas & comentarios 🙌  
