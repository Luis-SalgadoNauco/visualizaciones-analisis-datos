# Visualización y Análisis de Datos

Este repositorio documenta el desarrollo progresivo de un proceso de **análisis de datos y visualización**, realizado en Python utilizando Jupyter Notebook, como parte de un programa de formación en **Análisis de Datos y Estadística**.

El enfoque principal es aprender a **comunicar insights de manera clara y efectiva**, aplicando principios de percepción visual, teoría del color y composición gráfica, con evidencia reproducible y versionada.

---

## Descripción general

La visualización de datos no es un ejercicio estético, sino una herramienta cognitiva que permite transformar datos complejos en información comprensible para la toma de decisiones.

Durante este proyecto se abordan:

- Fundamentos psicológicos de la percepción visual  
- Diseño de paletas de colores según tipo de dato  
- Principios de jerarquía, composición y accesibilidad  
- Buenas y malas prácticas en visualización  
- Documentación reproducible del análisis  

Cada día de trabajo incluye:

- Dataset utilizado  
- Análisis realizado  
- Evidencia visual  
- Código reproducible  

---

## Objetivos generales

- Comprender cómo el cerebro humano procesa información visual.
- Diseñar visualizaciones alineadas con principios perceptivos.
- Seleccionar paletas de color adecuadas según el contexto del dato.
- Evaluar el impacto del diseño visual en la claridad del insight.
- Generar evidencia técnica reproducible y versionada en GitHub.

---

## Día 1 — Psicología de la percepción visual y paletas de color

### Contenidos abordados

- Sistemas de procesamiento visual:
  - Procesamiento pre-atencional
  - Procesamiento consciente
- Principios Gestalt aplicados a visualización:
  - Proximidad
  - Semejanza
  - Continuidad
  - Cierre
  - Figura vs fondo
- Teoría del color:
  - Matiz
  - Saturación
  - Luminosidad
- Tipos de paletas:
  - Cualitativas
  - Secuenciales
  - Divergentes
- Introducción a accesibilidad visual

---

### Dataset utilizado

Archivo Excel con dataset y tablas derivadas:

**dataset_paletas_color_dia1.xlsx**

Incluye:

- Dataset completo
- Tablas de resumen estadístico
- Agregaciones por categoría y segmento

---

### Visualizaciones generadas

- Gráfico de barras con paleta cualitativa
- Gráfico de barras horizontales con paleta secuencial
- Ejemplo de paleta problemática (mala práctica)
- Gráfico de dispersión con jerarquía visual

---

### Evaluación visual

- **Jerarquía:** El tamaño y el color dirigen la atención hacia los valores relevantes.
- **Color:** Paletas adecuadas refuerzan el significado del dato; paletas incorrectas generan confusión.
- **Composición:** El orden y el espaciado facilitan la lectura y reducen la carga cognitiva.

---

### Evidencia generada

Archivos generados durante el Día 1:

- `paletas_color_dia1.ipynb`
- `dataset_paletas_color_dia1.xlsx`
- `principios_visuales_paletas_color.png`

---

## Día 2 — Análisis visual univariado y bivariado con Matplotlib

### Contenidos abordados

- Configuración profesional de Matplotlib:
  - Estilos globales
  - Parámetros `rcParams`
  - Tamaño, resolución y consistencia visual
- Uso de paletas de color corporativas
- Gestión de figuras y subplots
- Análisis univariado:
  - Histogramas
  - Diagramas de caja (boxplots)
  - Gráficos de barras
  - Gráficos de torta (uso con precaución)
- Análisis bivariado:
  - Diagramas de dispersión
  - Series temporales
- Introducción a dashboards exploratorios estáticos
- Creación y uso de plantillas visuales reutilizables (`.mplstyle`)

---

### Dataset utilizado

Dataset empresarial simulado con métricas de ventas, clientes y productos.

Archivo Excel generado para asegurar reproducibilidad total del análisis:

**dataset_y_tablas_dia2_analisis_visual.xlsx**

Incluye:

- Dataset completo de ventas (1.000 registros)
- Ventas agregadas por producto
- Ventas agregadas por región
- Ventas agregadas por tipo de cliente
- Ventas diarias agregadas (serie temporal)

---

### Visualizaciones generadas

**Análisis univariado:**

- Histograma del total de ventas
- Boxplot de ventas por producto
- Gráfico de barras horizontales por región
- Distribución de tipos de cliente

Evidencia:

- **analisis_univariado_empresarial.png**

---

**Análisis bivariado:**

- Diagrama de dispersión:
  - Precio unitario vs cantidad
  - Color representando el total de venta
- Serie temporal de ventas diarias:
  - Línea + área para enfatizar tendencia

Evidencia:

- **analisis_bivariado_empresarial.png**

---

### Verificación e insights del negocio

A partir de las visualizaciones generadas se identifican los siguientes insights iniciales:

- **Productos más rentables:**  
  Los boxplots muestran diferencias claras en la mediana y dispersión de ventas entre productos, permitiendo identificar aquellos con mayor aporte económico.

- **Variación regional:**  
  El gráfico de barras evidencia desigualdad en el desempeño regional, lo que sugiere oportunidades de optimización comercial o logística.

- **Comportamiento temporal:**  
  La serie temporal de ventas diarias permite detectar patrones de variabilidad y posibles indicios de estacionalidad o eventos atípicos.

---

### Evidencia generada

Archivos generados durante el Día 2:

- `analisis_visual_empresarial_dia2.ipynb`
- `analisis_univariado_empresarial.png`
- `analisis_bivariado_empresarial.png`
- `dataset_y_tablas_dia2_analisis_visual.xlsx`
- `estilo_profesional.mplstyle`

---

## Día 3 — Diseño de dashboards analíticos avanzados

### Contenidos abordados

- Diseño de figuras compuestas con subtramas
- Uso avanzado de `GridSpec` para layouts flexibles
- Arquitecturas de dashboards:
  - KPIs ejecutivos
  - Gráficos principales y secundarios
- Coordinación visual entre subtramas:
  - Escalas compartidas
  - Paletas consistentes
- Visualizaciones estadísticas avanzadas:
  - Heatmaps de correlación
  - Violin plots
- Construcción de dashboards ejecutivos estáticos
- Preparación de evidencia reproducible para análisis empresarial

---

### Dataset utilizado

Dataset de comercio electrónico simulado con información de:

- Órdenes
- Clientes
- Categorías de producto
- Regiones
- Métodos de pago
- Métricas monetarias

Archivo Excel generado para asegurar reproducibilidad total del análisis:

**dataset_y_tablas_dashboard_ecommerce_dia3.xlsx**

Incluye:

- Dataset completo de e-commerce (2.000 órdenes)
- Ventas agregadas por mes
- Ventas por categoría
- Distribución por método de pago
- Métricas por región
- Ticket promedio por día de la semana

---

### Visualizaciones generadas

- Panel de KPIs ejecutivos
- Evolución mensual de ventas
- Ventas por categoría
- Distribución de métodos de pago
- Heatmap de correlaciones
- Distribución de ventas por región (violin plot)
- Ticket promedio por día de la semana

Evidencia principal:

- `dashboard_ecommerce_completo.png`

---

### Verificación e insights del negocio

- **Visión ejecutiva:**  
  Los KPIs permiten una lectura inmediata del desempeño global.

- **Patrones temporales:**  
  Se identifican tendencias mensuales relevantes para planificación.

- **Preferencias de pago:**  
  Alta concentración en tarjeta sugiere dependencia de un método dominante.

- **Diferencias regionales:**  
  La dispersión por región evidencia comportamientos heterogéneos.

- **Comportamiento semanal:**  
  Variaciones en ticket promedio aportan insumos para campañas comerciales.

---

### Evidencia generada

Archivos generados durante el Día 3:

- `dashboard_ecommerce_dia3.ipynb`
- `dashboard_ecommerce_completo.png`
- `dataset_y_tablas_dashboard_ecommerce_dia3.xlsx`

---

## Día 4 — Storytelling con datos y presentaciones analíticas impactantes

### Contenidos abordados

- Estructura de una historia de datos efectiva:
  - Contexto del problema de negocio
  - Evidencia analítica
  - Comunicación de insights
  - Llamado a la acción
- Principios de storytelling con datos:
  - Progreso lógico de la narrativa
  - Emoción + racionalidad
  - Relevancia contextual según audiencia
- Jerarquía visual y diseño de atención:
  - Tamaño y posición de elementos
  - Sistemas de color jerárquicos
  - Layouts ejecutivos con `GridSpec`
- Técnicas de énfasis visual:
  - Aislamiento de insights clave
  - Contraste extremo
  - Uso de anotaciones, flechas y zonas de atención
- Comunicación persuasiva basada en datos:
  - Traducción de análisis a decisiones
  - Recomendaciones priorizadas
  - Definición de próximos pasos medibles

---

### Dataset utilizado

Dataset simulado de rendimiento de ventas con foco ejecutivo.

Archivo Excel generado para asegurar reproducibilidad total del análisis:

**dataset_y_tablas_rendimiento_ventas_dia4.xlsx**

Incluye:

- Dataset base de ventas mensuales
- Resumen ejecutivo de métricas clave
- Cumplimiento mensual vs objetivo
- Identificación de mejor y peor mes
- Brecha de ventas bajo umbral crítico

---

### Visualizaciones generadas

- Diapositiva de título y contexto ejecutivo
- Diapositiva de insights principales con jerarquía visual
- Diapositiva de recomendaciones estratégicas con llamado a la acción

Evidencia visual:

- `diapositiva_01_titulo.png`
- `diapositiva_02_insights_principales.png`
- `diapositiva_03_recomendaciones.png`

---

### Verificación e insights del negocio

- **Lectura ejecutiva clara:**  
  La jerarquía visual permite identificar rápidamente desempeño, riesgos y oportunidades.

- **Narrativa coherente:**  
  La presentación fluye desde el contexto hasta la acción, sin saltos cognitivos.

- **Énfasis efectivo:**  
  El uso de contraste y aislamiento asegura que los insights críticos no pasen desapercibidos.

- **Accionabilidad:**  
  Las recomendaciones están priorizadas y conectadas directamente con los datos analizados.

---

### Evidencia generada

Archivos generados durante el Día 4:

- `presentacion_analitica_rendimiento_ventas_dia4.ipynb`
- `dataset_y_tablas_rendimiento_ventas_dia4.xlsx`
- `diapositiva_01_titulo.png`
- `diapositiva_02_insights_principales.png`
- `diapositiva_03_recomendaciones.png`

---

## Día 5 — Comparación de herramientas de visualización y criterios de selección

### Contenidos abordados

- Comparación práctica de herramientas de visualización en Python:
  - Seaborn
  - Plotly
  - Pandas plotting (backend Matplotlib)
- Análisis de ventajas y limitaciones según contexto de uso
- Visualización estadística vs interactividad
- Exploración rápida vs dashboards reproducibles
- Generación de evidencia visual y datasets reproducibles
- Buenas prácticas para selección de herramientas en proyectos reales

---

### Dataset utilizado

Dataset simulado de análisis de ventas con métricas comerciales y segmentación de clientes.

Archivo Excel generado para asegurar reproducibilidad total del análisis:

**dataset_y_tablas_analisis_ventas_dia5.xlsx**

Incluye:

- Dataset completo de ventas (1.000 registros)
- Ventas y beneficios por región
- Ventas por categoría
- Tendencia temporal mensual
- Métricas derivadas:
  - Beneficio
  - Margen
  - Agregaciones por tipo de cliente

---

### Visualizaciones generadas

**Seaborn — Visualización estadística:**

- Boxplot de ventas por región
- Scatter plot ventas vs beneficio con segmentación por tipo de cliente
- Heatmap de ventas promedio por categoría y región
- Tendencia mensual de ventas

Evidencia:

- `analisis_seaborn_comparacion_ventas_dia5.png`

---

**Plotly — Dashboard interactivo:**

- Ventas totales por región (barra interactiva)
- Distribución de ventas por categoría (pie interactivo)
- Tendencia mensual de ventas (línea interactiva)
- Relación beneficio vs ventas con escala de color por margen

Evidencia:

- `dashboard_plotly_comparacion_ventas_dia5.html`

---

**Pandas plotting — Análisis exploratorio rápido:**

- Histograma de ventas
- Boxplot de ventas por región
- Scatter beneficio vs ventas
- Tendencia mensual
- Ventas por categoría
- Área acumulada por tipo de cliente

Evidencia:

- `analisis_pandas_plotting_comparacion_ventas_dia5.png`

---

### Verificación y criterios de selección de herramientas

A partir del ejercicio comparativo se establecen los siguientes criterios de uso:

- **Pandas plotting:**  
  Ideal para análisis exploratorios rápidos y estadísticas descriptivas sobre datasets estáticos, con mínimo esfuerzo y máxima integración con Pandas.

- **Seaborn:**  
  Recomendado para visualizaciones estadísticas con mejor estética y valores por defecto profesionales, especialmente en análisis exploratorio y presentación técnica.

- **Plotly:**  
  Herramienta preferida cuando se requiere interactividad, exploración dinámica, dashboards web o visualizaciones sobre datos que se actualizan constantemente.

**Factores clave de decisión:**

- Complejidad del análisis
- Nivel de interactividad requerido
- Audiencia objetivo
- Rendimiento
- Facilidad de uso
- Reproducibilidad del resultado

---

### Evidencia generada

Archivos generados durante el Día 5:

- `comparacion_herramientas_analisis_ventas_dia5.ipynb`
- `analisis_seaborn_comparacion_ventas_dia5.png`
- `analisis_pandas_plotting_comparacion_ventas_dia5.png`
- `dashboard_plotly_comparacion_ventas_dia5.html`
- `dataset_y_tablas_analisis_ventas_dia5.xlsx`

---

## Cierre de la semana

Durante esta semana de trabajo se recorrió un proceso completo de **visualización y comunicación de datos**, avanzando desde los fundamentos perceptivos hasta la comparación profesional de herramientas de visualización.

Se desarrollaron competencias en:

- Comprensión cognitiva de la percepción visual
- Diseño consciente de gráficos efectivos
- Análisis exploratorio y estadístico
- Construcción de dashboards analíticos
- Storytelling con datos orientado a decisión
- Selección adecuada de herramientas según contexto

El resultado final es un repositorio **documentado, reproducible y versionado**, que evidencia no solo el dominio técnico de las librerías, sino también la capacidad de **pensar visualmente los datos para comunicar insights de negocio**.

---

## Tecnologías utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook
- Git / GitHub

---

## Estructura del proyecto

```text
visualizaciones-analisis-datos/
├── README.md
├── dia_1/
│   ├── paletas_color_dia1.ipynb
│   ├── dataset_paletas_color_dia1.xlsx
│   └── principios_visuales_paletas_color.png
├── dia_2/
│   ├── analisis_visual_empresarial_dia2.ipynb
│   ├── analisis_univariado_empresarial.png
│   ├── analisis_bivariado_empresarial.png
│   ├── dataset_y_tablas_dia2_analisis_visual.xlsx
│   └── estilo_profesional.mplstyle
├── dia_3/
│   ├── dashboard_ecommerce_dia3.ipynb
│   ├── dashboard_ecommerce_completo.png
│   └── dataset_y_tablas_dashboard_ecommerce_dia3.xlsx
├── dia_4/
│   ├── presentacion_analitica_rendimiento_ventas_dia4.ipynb
│   ├── dataset_y_tablas_rendimiento_ventas_dia4.xlsx
│   ├── diapositiva_01_titulo.png
│   ├── diapositiva_02_insights_principales.png
│   └── diapositiva_03_recomendaciones.png
├── dia_5/
│   ├── comparacion_herramientas_analisis_ventas_dia5.ipynb
│   ├── analisis_seaborn_comparacion_ventas_dia5.png
│   ├── analisis_pandas_plotting_comparacion_ventas_dia5.png
│   ├── dashboard_plotly_comparacion_ventas_dia5.html
│   └── dataset_y_tablas_analisis_ventas_dia5.xlsx

```