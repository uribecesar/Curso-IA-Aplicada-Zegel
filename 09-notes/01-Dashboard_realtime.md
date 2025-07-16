# 🧠 Construir dashboards con datos en tiempo real usando IA (Guía Práctica)

## Índice

1. [Objetivo general](#objetivo-general)
2. [Punto de partida: archivo Excel](#punto-de-partida-archivo-excel)
3. [Etapa 1: Preparar los datos](#etapa-1-preparar-los-datos)
4. [Etapa 2: Subir a Google Sheets](#etapa-2-subir-a-google-sheets)
5. [Etapa 3: Publicar como CSV público](#etapa-3-publicar-como-csv-público)
6. [Etapa 4: Construcción del dashboard simple](#etapa-4-construcción-del-dashboard-simple)
7. [Etapa 5: Dashboard avanzado tipo slideshow](#etapa-5-dashboard-avanzado-tipo-slideshow)
8. [Conclusiones](#conclusiones)

---

## 🎯 Objetivo general

Explicar cómo cualquier profesional puede crear un dashboard visual y dinámico en HTML usando inteligencia artificial, sin necesidad de saber programar, a partir de un archivo de ventas en Excel o Google Sheets.

---

## 📁 Punto de partida: archivo Excel

Contamos con un archivo que contiene datos de ventas. Las columnas son:

* Fecha
* Producto
* Categoría
* Vendedor
* Región
* Canal de Venta
* Método de Pago
* Cliente
* Cantidad
* Precio Unitario (USD)
* Descuento (%)
* Total (USD)

**Ejemplo de filas:**


| Fecha       | Producto         | Categoría  | Vendedor       | Región | Canal        | Método de Pago         | Cliente       | Cantidad | Precio Unitario (USD) | Descuento (%) | Total (USD) |
|-------------|------------------|------------|----------------|--------|--------------|------------------------|----------------|----------|------------------------|----------------|--------------|
| 2024-03-27  | Ratón ergonómico | Wearables  | Luis Martínez  | Este   | Marketplace  | Transferencia bancaria | Cliente_0219  | 5        | 706.65                 | 15.96          | 2969.34      |
| 2024-03-25  | Laptop Pro 15    | Accesorios | Luis Martínez  | Sur    | Online       | Tarjeta de débito      | Cliente_0093  | 8        | 1213.25                | 11.07          | 8631.55      |

---

## ✅ Etapa 1: Preparar los datos

* Elimina espacios extra en encabezados
* Asegúrate que los valores numéricos estén bien formateados (punto decimal)
* No dejes columnas vacías

**Recomendado:** Si los datos son muchos, automatiza limpieza con Python o IA.

---

## 📤 Etapa 2: Subir a Google Sheets

1. Sube tu archivo `.xlsx` a Google Drive
2. Haz clic derecho → Abrir con → Hojas de cálculo de Google

---

## 🔗 Etapa 3: Publicar como CSV público

1. En Google Sheets: `Archivo > Compartir > Publicar en la web`
2. Publica como **CSV** (elige la hoja correcta)

**Ejemplo de enlace generado:**

```
https://docs.google.com/spreadsheets/d/e/2PACX-1vQvcL9xZ.../pub?gid=0&single=true&output=csv
```

Este archivo se actualiza automáticamente cada vez que edites la hoja.

---

## 💡 Etapa 4: Construcción del dashboard simple

**Prompt base para IA:**

```markdown
// 🧠 ROL
Eres un profesional experto en análisis de datos y business intelligence.

// 🎯 OBJETIVO
Genera un **dashboard descriptivo** interactivo en formato **HTML embebible**, usando **Chart.js** para mostrar datos de ventas.

Debe contener **4 gráficos diferentes** organizados como un slideshow navegable, con diseño profesional, paleta de colores sobria y visualización clara.

// 📊 ENTRADA DE DATOS
Usa este archivo CSV público de Google Sheets:

 [URL CSV]

Accede a los datos vía proxy CORS:

  https://corsproxy.io/?url={encodeURIComponent(URL_CSV)}

// ⚠️ CONTEXTO DE EJECUCIÓN
- Este código podrá  **embebido dentro de una página web** (servido vía `https://`).
- Contempla en caso de que se abrirá como archivo local (`file://`), puede usarse sin problemas.
- No se usará ningún backend, framework ni servidor externo. Todo debe correr **directamente en el navegador del usuario**.

// 🧱 REQUISITOS TÉCNICOS

- Usa `fetch()` con `https://corsproxy.io/?url=...` y `encodeURIComponent` correctamente.
- Si el `fetch` falla, usa `fallbackData` predefinido como respaldo.
- Implementa validación mínima del CSV (estructura básica y valores numéricos).
- Usa solo tecnologías nativas: HTML + JavaScript (sin frameworks).
- Usa **Chart.js** desde CDN (`chart.umd.js` o similar).
- Diseño responsivo con navegación por botones (`Siguiente / Anterior`).
- Todos los gráficos deben ser distintos entre sí: línea, barras, pie, radar, polar, scatter, etc.
- Estilo sobrio y profesional, ideal para mostrar en presentaciones o sitios educativos.

// 📌 SALIDA ESPERADA
Un único archivo `.html` funcional, con los siguientes componentes:

1. Sección inicial con título y mensaje de carga.
2. Contenedor slideshow con 4 gráficos, uno por slide.
3. Botones de navegación (`Anterior`, `Siguiente`).
4. Gráficos usando datos reales del CSV (o fallback si falla).
5. Carga de datos automática desde proxy CORS.
6. Advertencia clara si los datos no se pueden cargar.

TODO debe estar contenido en **un solo archivo HTML**, 100% funcional sin backend ni librerías externas.

// 🧪 MUESTRA DE DATOS

[Ejemplo de muestra de datos ]
```

---

## 📊 Etapa 5: Dashboard avanzado tipo slideshow

**Prompt mejorado:**

```markdown
// 🧠 ROL
Eres un profesional experto en análisis de datos y business intelligence.

// 🎯 OBJETIVO
Genera un **dashboard descriptivo** interactivo en formato **HTML embebible**, usando **Chart.js** para mostrar datos de ventas.

Debe contener **6 gráficos diferentes** con diseño profesional, paleta de colores sobria y visualización clara.

[recomendado: Lista graficos relevantes]

// 📊 ENTRADA DE DATOS
Usa este archivo CSV público de Google Sheets:

 [URL CSV]

Accede a los datos vía proxy CORS:

  https://corsproxy.io/?url={encodeURIComponent(URL_CSV)}

// ⚠️ CONTEXTO DE EJECUCIÓN
- Este código podrá  **embebido dentro de una página web** (servido vía `https://`).
- Contempla en caso de que se abrirá como archivo local (`file://`), puede usarse sin problemas.
- No se usará ningún backend, framework ni servidor externo. Todo debe correr **directamente en el navegador del usuario**.

// 🧱 REQUISITOS TÉCNICOS

- Usa `fetch()` con `https://corsproxy.io/?url=...` y `encodeURIComponent` correctamente.
- Si el `fetch` falla, usa `fallbackData` predefinido como respaldo.
- Implementa validación mínima del CSV (estructura básica y valores numéricos).
- Usa solo tecnologías nativas: HTML + JavaScript (sin frameworks).
- Usa **Chart.js** desde CDN (`chart.umd.js` o similar).
- Diseño responsivo con navegación por botones (`Siguiente / Anterior`).
- Estilo sobrio y profesional, ideal para mostrar en presentaciones o sitios educativos.

// 📌 SALIDA ESPERADA
Un único archivo `.html` funcional, con los siguientes componentes:

1. Gráficos usando datos reales del CSV (o fallback si falla).
2. Carga de datos automática desde proxy CORS.
3. Advertencia clara si los datos no se pueden cargar.

TODO debe estar contenido en **un solo archivo HTML**, 100% funcional sin backend ni librerías externas.

// 🧪 MUESTRA DE DATOS

[Ejemplo de muestra de datos ]
```

---

## 📚 Conclusiones

* Puedes usar Google Sheets como fuente dinámica de datos
* Los proxies como `corsproxy.io` permiten evitar errores CORS
* La IA puede ayudarte a generar el código base
* Lo importante es tener un archivo limpio, bien estructurado y un prompt claro

---

## 🔗 Recursos útiles

* [Chart.js documentación](https://www.chartjs.org/docs/latest/)
* [CORS Proxy simple](https://corsproxy.io/)
* [Guía oficial Google Sheets - Publicar CSV](https://support.google.com/docs/answer/183965)