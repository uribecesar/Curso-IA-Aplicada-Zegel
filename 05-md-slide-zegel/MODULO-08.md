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

# Octava Sesión

---

<!-- backgroundImage: url('../image/bg2.JPG') -->

<!-- _class: subindicator-title -->

<h1 style="color: white">  SUBINDICADOR N°8: SOBERANÍA DE DATOS Y HOJA DE RUTA PROFESIONAL</h1>
Temas:

* Implementación de modelos locales 
* Soberanía de datos y compliance
* Planificación profesional estratégica


---

<!-- backgroundImage: url('../image/bg5.JPG') -->

# 💼 Modelos Locales: Control Total

## ⚖️ Local vs. Nube

---


| Aspecto | Modelos Locales | Servicios Nube |
|---------|----------------|----------------|
| **Costo Mensual** | $200-500 | $2,000-8,000 |
| **Control de Datos** | 100% | Limitado |
| **Latencia** | <100ms | 200-500ms |
| **Dependencia** | Ninguna | Total |

---

# 📊 Caso Real: Automatización de Reportes


---


### 🏢 **Empresa Consultora - 50 empleados**
- **Antes:** 4 horas por reporte, $45 costo
- **Después:** 20 minutos, $0.50 costo
- **Resultado:** $3,600 ahorro mensual, ROI 450%


---


### 🛠️ **Herramienta:** LM Studio + Llama 3.2
**Tiempo de configuración:** 30 minutos

---

# 🎛️ Interfaces de Control Personalizadas

## 💬 Chat vs. Interface Personalizada


---


| Aspecto | Chat Genérico | Interface Personalizada |
|---------|---------------|------------------------|
| **Personalización** | Limitada | Control total |
| **Integración** | Manual | Automática |
| **Costo Mensual** | $20-100/usuario | $0 post-desarrollo |
| **Escalabilidad** | Limitada | Ilimitada |

---

# 🏛️ Soberanía de Datos: Obligación Legal


---


### 📋 **Realidad Regulatoria 2025**
- **75+ países** con leyes de soberanía de datos
- **Multas GDPR:** hasta €20M o 4% del revenue
- **Cumplimiento automático** con arquitectura local


---


### 💰 **ROI de Compliance**
Firma de inversión: $180K → $25K anuales (**86% reducción**)

---

# 🚀 Tu Futuro Profesional en IA

## 💰 Premium Salarial Comprobado


---


### 🎯 **Datos del Mercado 2025**
- **56% premium salarial** para roles con IA
- **$300,600** compensación mediana AI engineers
- **26% crecimiento** en empleos IA vs. 4% general


---


### ⚠️ **Costo de No Actuar**
**-15% penalty** vs. colegas con habilidades IA

---

# 📈 Caso de Transformación: 12 Meses

### 👤 **De Marketing Manager a AI Consultant**
- **Salario inicial:** $75,000
- **Inversión:** $2,500 (cursos + tiempo)
- **Salario final:** $120,000
- **ROI:** 1,800% primer año


---


### 🎯 **Herramientas:** IBM SkillsBuild (gratuito)

---

# 🛠️ Hardware Mínimo para Empezar


---


### 💻 **Configuración Básica**
**Para modelos locales:**
- 16GB RAM
- GPU 8GB VRAM (opcional)
- LM Studio (gratuito)


---


**Para interfaces:**
- Cualquier laptop moderna
- Python + Streamlit (gratuito)

---

# 🎯 Ejercicios Prácticos Clave


---


### ⏰ **Ejercicio 1: Configuración (30 min)**
Instala LM Studio, configura Llama 3.2 3B, realiza 5 consultas de tu área de trabajo.


---


### 🔧 **Ejercicio 2: Interface (45 min)**

Calcula ROI de automatizar tu proceso más repetitivo con IA local.


---

# 🎯 Tu Plan de Acción Inmediato


---


### 💪 **Próximos 48 Horas**
1. **Descarga** LM Studio e instala Streamlit
2. **Identifica** tu caso de uso más valioso
3. **Configura** tu primer modelo local
4. **Desarrolla** tu primera interface básica
5. **Mide** el impacto desde día 1

---

# ⚡ La Ecuación del Éxito 2025

```
Modelos Locales + Interfaces Personalizadas + 
Soberanía de Datos + Skills IA = 
Ventaja Competitiva Exponencial
```


---


### 🚨 **Realidad Binaria**
En 2025 existirán solo **dos tipos de profesionales:**
- AI-Enhanced (premium salarial, crecimiento acelerado)
- Traditional (stagnación, opciones decrecientes)

---

# 🏁 Conclusión: El Momento es AHORA

### 🎯 **Tres Verdades de 2025**
1. **La ventana de oportunidad está abierta** pero cerrándose
2. **Los recursos están disponibles** (gratuitos y accesibles)
3. **El costo de esperar es exponencial**

---
# Fin del Octavo Modulo
## Preguntas & comentarios 🙌  
