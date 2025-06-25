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

# Tercera Sesión

---

<!-- backgroundImage: url('../image/bg2.JPG') -->

<!-- _class: subindicator-title -->

<h1 style="color: white"> Subindicador N°3: INGENIERÍA DE PREDICCIÓN Y DECISIONES ESTRATÉGICAS</h1>
Temas:

* Implementa un pipeline de datos en Python/Colab 
* Generar predicciones y recomendaciones.


---
<!-- backgroundImage: url('../image/bg5.JPG') -->
<!-- _class: topic-title -->
# 🎯 

# PREDICCIÓN Y DECISIONES ESTRATÉGICAS

### De Datos a Ventaja Competitiva

---

# 🚀 **AUTOMATIZACIÓN DE REPORTES**
## La Revolución de 2025


---


### ⚡ **85-90% menos tiempo**
### 💰 **562 horas** ahorradas por año
### 🎯 **66% incremento** productividad

---

# 🔄 **ANTES vs DESPUÉS**

## 🐌 **Método Manual**
- ⏱️ **4-6 horas** creación
- ❌ **15-20%** errores
- 🔄 **3-5 revisiones**


---


## 🤖 **IA Generativa**
- ⚡ **15-30 minutos**
- ✅ **<2% errores**
- 🎯 **1-2 revisiones**

---

# 🛠️  3 TECNOLOGÍAS CLAVE


---


## 📝 **1. MARP**
### Markdown → Presentaciones


---


## 🌐 **2. HTML + Reveal.js**
### Dashboards interactivos

---



## 🤖 **3. ChatGPT + Python**
### PowerPoint automático

---

# ⚙️ **PIPELINE AUTOMATIZADO**

```
📊 Excel/CSV → 🐍 Python → 🎨 Formato → 📤 Distribución
```


---


### **Framework OSAC:**
- **🎯 O**bjetivo específico
- **📤 S**alida deseada
- **⚠️ A**dvertencias importantes
- **📋 C**ontexto completo

---

# 💼 **CASO PRÁCTICO: REPORTE VENTAS**


---


## 🎯 **Escenario**
500 productos → Presentación ejecutiva

## ⚡ **Resultado**
- **Antes:** 3 horas manual
- **Después:** 5 minutos automatizado
- **ROI:** 3,500% tiempo ahorrado

### 8 slides generadas automáticamente

---

# 🎓 **EJERCICIO 1: MARP BÁSICO**



## 🎯 **Tarea:** Crear 15 slides con MARP
**⏱️ Tiempo: 25 minutos**

---

# 🐍 ANÁLISIS CON PYTHON


---


## Código Simple, Resultados Profesionales

### 🎯 **Precisión Quirúrgica en Reportes**

---

# 💪 **PYTHON vs EXCEL**

| Aspecto | Excel | Python | Ventaja |
|---------|-------|--------|---------|
| **Límite datos** | 1M filas | ∞ | **∞x** |
| **100K filas** | 30 min | 30 seg | **60x** |
| **Precisión** | Errores | 15 decimales | **100%** |
| **Automatización** | Manual | Total | **∞x** |

---

# 🔬 **VENTAJAS QUIRÚRGICAS**


---


## 💎 **Precisión Sin Límites**
### Excel colapsa, Python procesa millones

## ⚡ **Velocidad Exponencial**
### Horas → Segundos


---


## 🔍 **Transparencia Total**
### Cada decisión documentada línea por línea

---

# 🎯 **5 PROMPTS MAESTROS**


---


## **1. Análisis Básico**
```
"Tengo [archivo]. Quiero entender patrones. 
Dame código que cargue, grafique y resuma 
en palabras simples."
```


---


## **2. Detectar Problemas**
```
"Encuentra errores en [archivo]. 
Muestra gráficos y dime qué arreglar."
```

---

# 🎯 **PROMPTS MAESTROS (CONT.)**

## **3. Comparaciones**
```
"Compara [A] vs [B]. 
Gráficos claros, cuál es mejor y por qué."
```


---


## **4. Dashboard Interactivo**
```
"Botones y filtros para que jefe explore 
sin programación. Clicks simples."
```


---


## **5. Reporte Ejecutivo**
```
"Conclusiones en bullets, recomendaciones 
específicas, PDF profesional."
```

---

# 📊 **DATASET MODELO**

## 📁 **`ventas_productos_q1_2025.xlsx`**


---


| Columna | Contenido | Ejemplos |
|---------|-----------|----------|
| **producto** | Nombre | "Laptop Dell" |
| **precio** | Precio venta | 1200 |
| **cantidad** | Unidades | 150 |
| **categoria** | Tipo | "Tecnología" |
| **region** | Ubicación | "Norte" |
| **fecha** | Cuándo | 2025-01-15 |

**1,000 productos + 10% errores intencionalmente**

---

# 🎓 **EJERCICIO 2: PYTHON BÁSICO**

---



## 🎯 **Usa Prompt 1 con dataset modelo**

### **Pasos:**
1. Abre Google Colab
2. Sube `ventas_productos_q1_2025.xlsx`
3. Copia Prompt 1 + nombre archivo
4. Pégalo en ChatGPT
5. Ejecuta código en Colab

**⏱️ Tiempo: 25 minutos**
**🎯 Objetivo: Generar primeros insights automáticamente**

---

# 📊 VISUALIZACIÓN INTELIGENTE
## Gráficos que Comunican y Predicen

### 🚀 **La Era de la Inteligencia Visual**

---

# 🤖 **MÁS ALLÁ DE LO CONVENCIONAL**

 ❌ **Antes:** Gráficos estáticos manuales
✅ **Ahora:** IA sugiere visualizaciones automáticas


---


### **3 Capacidades Revolucionarias:**
- 🤖 **Análisis autónomo** completo
- 🔮 **Visualización predictiva** integrada
- 🎮 **Interactividad avanzada** contextual

---

# 🔮 **PREDICTIVO vs PRESCRIPTIVO**

## 🔍 **Predictivo: "¿Qué Va a Pasar?"**
- 📈 Predicción demanda 3 meses
- ⚠️ Anticipación fallas equipos
- 💰 Proyección flujos caja


---



## 🎯 **Prescriptivo: "¿Qué Hacer?"**
- **Recomendaciones específicas** acción
- **Simulación escenarios** "qué pasaría si"
- **ROI $13.01** por dólar invertido

---

# 📊 **6 GRÁFICOS VALIOSOS**

## 🎯 **Prompt Visualizaciones Estratégicas**
```
"Genera exactamente 6 gráficos:
1. 🔥 HEATMAP correlaciones
2. 📈 TENDENCIAS temporales + proyección
3. 📊 ANÁLISIS ABC (Pareto)
4. 📦 BOXPLOT comparativo outliers
5. 🎯 SCATTER interactivo precio-volumen
6. 🎮 DASHBOARD resumen con KPIs"
```

---

# ☁️ **GOOGLE COLAB EMPRESARIAL**


---



## 👥 **Colaboración Tiempo Real**
- **Múltiples usuarios** editan juntos
- **Chat integrado** sin cambiar plataformas
- **Permisos granulares** por usuario


---


## 🔗 **Integración Sistémica**
- **BigQuery** y Google Sheets
- **Import/Export** Google Drive directo
- **Colab Enterprise** seguridad total

---

# 🎓 **EJERCICIO 3: DASHBOARD INTERACTIVO**

## 🎯 **Crea dashboard con widgets**


---


### **Usando mismo dataset:**
1. Menú desplegable categorías
2. Botones filtro región
3. Gráficos que cambien automáticamente
4. Botón descargar resultados

**⏱️ Tiempo: 30 minutos**
**🎯 Objetivo: Dashboard tan fácil como Netflix**

---

# 🎯 **DECISIONES ESTRATÉGICAS**
## De Análisis a Recomendaciones Accionables

### 🚀 **De Intuición a Inteligencia Aumentada**

---

# 🏆 **ORGANIZACIONES DATA-DRIVEN**

---


### **23x más propensas** adquirir clientes
### **6x más propensas** retenerlos  
### **19x más propensas** ser rentables

## ⚠️ **Solo 25%** decisiones completamente data-driven

---

# 💡 **PROMPT TRADUCCIÓN EJECUTIVA**

```
"Traduce análisis técnico a lenguaje ejecutivo:

RESUMEN (30 segundos):
- 1 insight principal
- 1 recomendación específica  
- 1 número de impacto

RECOMENDACIONES:
- Qué hacer específicamente
- Cuánto costará/ahorrará
- Cuándo implementar

Usa analogías negocio, evita jerga técnica."
```

---

# 💼 **CASO INTEGRADOR: CRISIS VENTAS**

## 🚨 **Situación:** Ventas bajaron 15% en 3 semanas

---


### **Prompt Emergencia:**
```
"URGENTE: Analiza caída ventas.
- Identifica cuándo/dónde/por qué empezó
- Proyecta impacto si continúa
- 3 acciones inmediatas (<7 días)
- Dashboard seguimiento diario
TIEMPO: 2 horas máximo"
```

---

# 🎓 **EJERCICIO 4: FRAMEWORK COMPLETO**

## 📊 **Dataset:** "decisiones_estrategicas_modelo.xlsx"
### 2,000 filas, 15 variables

---


## 🎯 **Implementar pasos:**
1. Contextualización industria
2. Predicciones próximos 6 meses
3. Recomendaciones específicas con ROI
4. Documento ejecutivo automático

**⏱️ Tiempo: 45 minutos**

---

# 📋 **TAREA FINAL: PROYECTO REAL**

## 🚀 **Proyecto Integrador Completo**

---


### **Objetivo:** Sistema automatizado Google Colab
1. ✅ Leer Excel 6 columnas
2. 🎨 Generar 3 formatos (MARP, HTML, PPTX)
3. 📊 Dashboard interactivo con widgets
4. 🧠 Análisis
5. 📄 Reporte ejecutivo automático Word
6. 📥 Botones descarga cada formato
7. ⏱️ Medir tiempo vs método manual

---

# 💰 **RECURSOS NECESARIOS**

## 🆓 **Stack Completo Gratuito**
- ☁️ **Google Colab:** $0
- 📚 **Bibliotecas Python:** $0  
- 🤖 **ChatGPT:** $20/mes (Pro recomendado)
- 📂 **Google Drive:** $0

---


## ⏱️ **Tiempo Dominio**
**2-3 semanas** vs **meses** capacitación tradicional

---

## 💡 **ROI Inmediato**
**$20/mes** vs **s,/ cientos** en consultores

---

# 🏆 **TRANSFORMACIÓN GARANTIZADA**

## 📊 **Antes vs Después**
- ❌ **Antes:** Reportes manuales semanas
- ✅ **Después:** Sistemas automatizados horas

---


## 💡 **Nueva Realidad**
- **5-8x ROI** vs competencia tradicional
- **85-95% precisión** vs 60-70% manual
- **Decisiones tiempo real** vs intuición

---

## 🎯 **Pregunta Definitiva**
¿Tus datos solo **informan** o **transforman** decisiones?

---

# 🚀 **¡COMIENZA HOY!**

## ⚡ **Próximo Paso Crítico**
**Implementar primer pipeline esta semana**

## ⚠️ **Costo de Esperar**
Perder ventaja competitiva **mensurable**


---
# Fin del Tercer Modulo
## Preguntas & comentarios 🙌  
