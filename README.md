# Urban Mobility & Economic Productivity in Latin America

## Análisis de movilidad urbana y productividad económica con Python

Proyecto de análisis de datos desarrollado por **Sergio Yépez** para
explorar la relación entre indicadores de movilidad urbana y
productividad económica en ciudades de Latinoamérica, integrando
información de **TomTom Traffic Index** y **OECD Cities**.

## 🎯 Objetivo

Analizar indicadores de congestión vehicular y desempeño económico
durante **2024**, con el propósito de identificar patrones entre
ciudades y generar hallazgos que puedan servir como punto de partida
para análisis de movilidad, infraestructura y transporte.

## 📊 Datos utilizados

El proyecto integra dos fuentes principales:

-   **TomTom Traffic Index:** métricas relacionadas con tráfico y
    congestión urbana.
-   **OECD Cities:** indicadores económicos y demográficos a nivel
    ciudad.

Después de preparar y agregar los datos de tráfico, se obtuvieron **387
registros ciudad-país-año** para 2024. Posteriormente, mediante un
`INNER JOIN` por `city` y `year`, se construyó un dataset analítico
final con **15 ciudades** que contaban con información coincidente en
ambas fuentes.

## 🛠️ Tecnologías y herramientas

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Jupyter Notebook

## 🔎 Metodología

El análisis siguió las siguientes etapas:

1.  Carga y exploración inicial de los datasets.
2.  Revisión de estructura, tipos de datos e inconsistencias.
3.  Estandarización de nombres de columnas a formato `snake_case`.
4.  Conversión y limpieza de fechas y variables numéricas.
5.  Normalización de separadores decimales y porcentajes.
6.  Creación de variables derivadas.
7.  Filtrado de ambos datasets al año 2024.
8.  Agregación de métricas de tráfico por ciudad, país y año.
9.  Integración de las fuentes mediante `merge`.
10. Análisis exploratorio y visualización de las principales variables.
11. Exportación del dataset limpio para análisis posteriores.

## 📈 Hallazgos principales

-   **Mexico City** registró el mayor `jams_delay` promedio dentro del
    dataset de tráfico agregado de 2024, con aproximadamente
    **2,833.06**.
-   Los niveles de congestión presentan una variabilidad importante
    entre ciudades.
-   La distribución del PIB per cápita es asimétrica y un grupo reducido
    de ciudades alcanza los niveles más altos.
-   La comparación visual entre congestión y PIB per cápita **no muestra
    una relación lineal clara**.
-   Los resultados sugieren que la movilidad urbana debe analizarse
    considerando otros factores, como infraestructura, densidad
    poblacional, transporte público y planificación urbana.

> **Nota:** este análisis es exploratorio. Los patrones observados no
> deben interpretarse como evidencia de causalidad entre congestión y
> productividad económica.

## 💡 Recomendaciones

Como siguientes pasos, el análisis podría ampliarse mediante:

-   Medidas estadísticas de asociación entre variables.
-   Incorporación de densidad poblacional.
-   Cobertura y calidad del transporte público.
-   Inversión en infraestructura urbana.
-   Validación adicional de comparabilidad entre fuentes.
-   Análisis detallado de las ciudades con mayores niveles de
    congestión.

## 📁 Estructura del repositorio

``` text
urban-mobility-economic-analysis/
├── Sergio_Yepez_Urban_Mobility_Economic_Analysis_Portfolio.ipynb
└── README.md
```

## ▶️ Cómo revisar el proyecto

El análisis completo se encuentra en el notebook:

`Sergio_Yepez_Urban_Mobility_Economic_Analysis_Portfolio.ipynb`

GitHub permite visualizar directamente los notebooks de Jupyter, por lo
que no es necesario ejecutar el archivo para revisar el análisis, el
código, las visualizaciones y las conclusiones.

## 👤 Autor

**Sergio Yépez**\
Ingeniero en Telecomunicaciones y Electrónica \| Data Analyst en
formación

Este proyecto forma parte de mi portafolio profesional de análisis de
datos.
