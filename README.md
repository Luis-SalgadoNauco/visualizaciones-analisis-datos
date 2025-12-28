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

---

## Días siguientes

- **Día 3:** Pendiente
- **Día 4:** Pendiente
- **Día 5:** Pendiente

---

## Tecnologías utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Git / GitHub

---

## Estructura del proyecto

El repositorio se organiza por días de trabajo, permitiendo un seguimiento progresivo del aprendizaje y facilitando la reproducibilidad del análisis.

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
│   └── dataset_y_tablas_dia2_analisis_visual.xlsx
├── dia_3/
├── dia_4/
└── dia_5/

```