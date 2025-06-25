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

# Séptima Sesión

---

<!-- backgroundImage: url('../image/bg2.JPG') -->

<!-- _class: subindicator-title -->

<h1 style="color: white"> Subindicador N° 7: DESARROLLO DE AGENTES Y AUTOMATIZACIÓN ASISTIDA</h1>

* Construir aplicaciones y scripts que orquesten agentes IA para automatizar procesos .


---
<!-- backgroundImage: url('../image/bg5.JPG') -->

# 🚀 AGENTES IA: LA REVOLUCIÓN DE LA AUTOMATIZACIÓN

## Del Asistente al Ejecutor Autónomo


---


**La ventana de oportunidad 2025:**
- 99% de empresas invierten en IA
- Solo 1% cree estar en madurez
- Esta brecha = tu oportunidad estratégica

---

## 🤔 Chatbot vs Agente IA

### Chatbot:
- Responde cuando le preguntas
- Necesita input constante
- Reactivo


---


### Agente IA:
- **Ejecuta tareas completas de inicio a fin**
- **Observa, planifica y actúa sin supervisión**
- **Proactivo y autónomo**

---

## 💰 El ROI de la Automatización

### Datos McKinsey 2025:
- **240% ROI** promedio
- **6-9 meses** recuperación de inversión
- **1 hora diaria** de ahorro por trabajador


---


### Por sectores (minutos ahorrados/día):
- Energía: 75 min
- Tecnología: 66 min
- Manufactura: 62 min
- Servicios Financieros: 57 min

---

## 🎯 Nuestra Estrategia: Híbrida e Inteligente

### GPT como Generador + Python como Ejecutor


---


**Ventajas:**
- ✅ Control total del proceso
- ✅ Costos mínimos
- ✅ Personalización completa
- ✅ Escalabilidad según necesidades

**Resultado:** Máxima flexibilidad sin dependencia de proveedores

---

## ⚠️ El Costo de No Actuar

### Datos del mercado:
- 99% de desarrolladores exploran agentes IA
- 82% de empresas planean integrar en 1-3 años
- 170 millones de nuevos empleos IA para 2030


---


### Los rezagados enfrentarán:
- Sobrecarga manual vs automatización
- Errores humanos vs precisión algorítmica
- Costos laborales vs eficiencia digital

---

## 📋 Caso de Uso: Despacho Legal

### Situación inicial:
- 200+ documentos mensuales
- 45 minutos por documento
- $7,500 USD/mes en costos laborales
- 8-12% documentos mal clasificados


---


### Con agente IA:
- 3 minutos por documento
- $500 USD/mes en costos
- <1% errores
- **ROI: 1,400% primer año**

---

## 🛠️ Tu Arsenal Mínimo

### Herramientas gratuitas:
- **Thonny IDE** - thonny.org
- **Python** (incluido)
- **Librerías básicas** (pandas, openpyxl)

---

### IA Generativa:
- **ChatGPT Plus** - $20 USD/mes
- **Alternativas gratuitas:** Claude, Gemini


---


### Tiempo de aprendizaje:
- Setup: 30 minutos
- Primer script: 2 horas
- Operativo: 1 semana

---

# 🛠️ ENTORNO TÉCNICO OPERATIVO

## Thonny: Tu IDE Estratégico

### ¿Por qué Thonny domina?
- Operativo en 30 minutos vs semanas de otros IDEs
- Sin configuración compleja
- Debugging visual integrado
- Ideal para automatización empresarial

---

## ⚡ Metodología de 5 Pasos (35 min total)

1. **Identificación** (5 min) - Reconocer tarea repetitiva
2. **Descripción** (10 min) - Articular objetivo a GPT
3. **Generación** (5 min) - Obtener código Python
4. **Ejecución** (10 min) - Implementar en Thonny
5. **Documentación** (5 min) - Registrar para reutilización

---

## 🔧 Configuración en 30 Minutos

### Paso 1: Instalación Thonny (10 min)
1. Visitar thonny.org
2. Descargar para tu sistema
3. Ejecutar instalación
4. Verificar con: `print("¡Listo para automatizar!")`

---

### Paso 2: Workspace (10 min)
```
📁 Automatizacion_Empresarial/
  📁 Scripts_Activos/
  📁 Plantillas_Prompts/
  📁 Datos_Prueba/
  📁 Respaldos/
```

---

## 📝 Template de Prompts (10 min)

```
"Necesito un script Python que [ACCIÓN ESPECÍFICA] 
usando archivos [TIPO] ubicados en [CARPETA]. 
El resultado debe [FORMATO DE SALIDA]. 
Requisitos: librerías básicas, manejo de errores, 
logging de actividades. Optimizar para [SECTOR]."
```

---

# 📁 AUTOMATIZACIÓN DE DOCUMENTOS

## Los 3 Pilares


---


### 1. Gestión Inteligente de Archivos
- Organización automática por tipo/fecha/proyecto
- Eliminación de duplicados
- Respaldos programados

---

### 2. Extracción y Procesamiento
- PDFs → Datos estructurados
- Excel → Reportes consolidados
- Imágenes → Texto (OCR)

---

### 3. Generación y Transformación
- Reportes automáticos
- Conversión de formatos
- Personalización masiva

---

## 📊 Impacto Cuantificado



---

| Proceso | Tiempo Manual | Automatizado | Mejora |
|---------|---------------|--------------|--------|
| Clasificación docs | 8 horas | 15 minutos | 97% ↓ |
| Extracción datos | 6 horas | 10 minutos | 95% ↓ |
| Generación reportes | 4 horas | 5 minutos | 98% ↓ |
| Organización archivos | 2 horas | 3 minutos | 97% ↓ |

---

## 💻 Scripts Fundamentales

### 1. Organizador Universal
```python
# Detecta tipos automáticamente
# Crea estructura inteligente
# Maneja duplicados
# Genera log de cambios
```

---

### 2. Extractor de Datos
```python
# Procesa múltiples formatos
# Valida y limpia información
# Exporta a formatos estándar
```
---

### 3. Generador de Reportes
```python
# Plantillas personalizables
# Gráficos automáticos
# Distribución vía email
```

---

# 🖥️ APLICACIÓN DE FORMULARIOS

## Del Excel Manual a la Aplicación Profesional


---


### Tkinter: Framework GUI Incluido en Python

**Ventajas:**
- Costo cero
- Implementación en 60-90 minutos
- Compatibilidad total (Windows, macOS, Linux)
- Personalización completa

---

## 🆚 Excel vs Aplicación Tkinter

| Proceso | Excel Manual | Tkinter App | Mejora |
|---------|-------------|-------------|--------|
| Entrada datos | 45 min | 3 min | 93% ↓ |
| Validación | 15% errores | <0.5% errores | 97% ↑ |
| Reportes | 3 horas | 2 minutos | 99% ↓ |
| Distribución | Manual | Automática | 100% ↓ |

---

## 🏗️ Arquitectura de la Aplicación

### Componentes principales:
1. **Interfaz intuitiva** - Formularios dinámicos
2. **Motor de datos** - Validación empresarial
3. **Sistema de reportes** - Analytics integrado


---


### Características avanzadas:
- Validación tiempo real
- Autocompletado inteligente
- Navegación por teclado
- Confirmaciones de seguridad

---

## 💼 Caso de Uso: Gestión de Leads


---


### Problema inicial:
- 15 min por lead manual
- 20% información incorrecta
- 30% leads sin follow-up
- $25,000 USD/mes en leads perdidos



---

### Solución Tkinter:
- 2 min por lead
- 0.5% errores
- 98% follow-up rate
- **ROI: $1,170,000 USD anual**

---

# 🎯 EJERCICIOS PRÁCTICOS VALIOSOS

## 1. Análisis de Procesos Automatizables

```
"Analiza mi descripción de proceso [describir proceso] 
e identifica qué tareas pueden automatizarse con Python. 
Prioriza por impacto vs complejidad de implementación."
```


---


## 2. Evaluación de ROI Personalizada

```
"Calcula el ROI potencial de automatizar [proceso] 
considerando: tiempo actual [X horas], costo por hora [Y], 
frecuencia [Z veces por mes]. Incluye escenarios 
optimista y conservador."
```

---

## 3. Generador de Script de Organización

```
"Crea un script Python que organice archivos en mi 
carpeta de descargas por tipo (PDF, Word, Excel, imágenes) 
y los mueva a carpetas específicas. Incluye manejo de 
errores y log de actividades."
```

## 4. Extractor de Datos de Documentos

```
"Desarrolla un script Python que extraiga [datos específicos] 
de múltiples archivos [tipo] en una carpeta y genere un CSV 
con los resultados. Optimiza para mi sector [especificar]."
```

---

## 5. Automatización Personalizada Completa

```
"Basándote en mi proceso manual más repetitivo [describir], 
diseña una solución completa que incluya: 
1) Script Python funcional
2) Interfaz de usuario simple  
3) Plan de implementación paso a paso
4) Métricas de éxito medibles"
```

---

## 6. Configuración de Workspace Empresarial

```
"Diseña la configuración óptima de Thonny para mi sector 
[especificar] incluyendo: estructura de carpetas, librerías 
esenciales, templates de prompts, y métricas de éxito 
específicas para mi industria."
```

---

## 7. Aplicación Tkinter Empresarial

```
"Desarrolla una aplicación Tkinter para [proceso específico] 
que incluya: formulario con validación, guardado automático 
en Excel, confirmación al usuario. Tiempo objetivo: 
aplicación operativa en 60 minutos."
```

## 8. Sistema de Reportes Integrados

```
"Extiende la aplicación anterior agregando: generación 
automática de reportes con métricas clave, gráficos básicos, 
filtrado por fechas, y exportación múltiple. Incluir 
alertas para datos críticos."
```

---

# 📅 ROADMAP DE IMPLEMENTACIÓN

## Primeros 30 días


---


### Semana 1-2: Fundación
- ✅ Configuración Thonny + librerías
- 🚀 Primeros 3 scripts funcionando
- 📋 Documentación de procesos



---

### Semana 3-4: Escalamiento
- 🔥 5-8 automatizaciones operativas
- 👥 Capacitación del equipo
- 📊 Métricas de éxito establecidas

---

## ⏰ La Ventana de Oportunidad 2025

### Predicciones clave:
- 75% empresas usarán automatización IA para 2026
- Los próximos 6 meses determinarán líderes vs seguidores


---


### Tu posición estratégica:
Mientras otros buscan soluciones costosas, **tú ejecutas automatización inmediata**

---


### La diferencia entre un profesional promedio y uno excepcional en 2025:
- ❌ No será solo el conocimiento
- ✅ Será la capacidad de multiplicar ese conocimiento a través de agentes IA



---
# Fin del Séptimo Modulo
## Preguntas & comentarios 🙌  
