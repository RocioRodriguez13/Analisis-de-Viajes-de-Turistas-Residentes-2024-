# Analisis de viajes de turistas residentes 2024

Este proyecto personal se centra en el análisis de los viajes realizados por turistas residentes de Argentina durante el año 2024, explorando tendencias en destinos, medios de transporte y estacionalidad.

## Datos:
El dataset utilizado, `turistas-residentes-serie.csv`, contiene información sobre:
- `indice_tiempo`: Fecha del registro (mensual).
- `medio_de_transporte`: Medio utilizado para el viaje (Aérea, Fluvial/Marítima, Terrestre).
- `pais_destino`: País o región de destino.
- `viajes_de_turistas_residentes`: Número de viajes registrados.

Los datos abarcan desde enero de 2016 hasta mayo de 2025. Para este análisis, nos enfocamos específicamente en el año 2024, considerándolo como el año completo más reciente disponible.

## Herramientas Utilizadas

- **Python**: Lenguaje de programación principal.
- **Pandas**: Para la manipulación y análisis de datos.
- **Matplotlib** y **Seaborn**: Para la visualización de datos y la creación de gráficos estadísticos.
- **Jupyter Notebook**: Para el desarrollo interactivo y la presentación del análisis.

## Análisis y Hallazgos Clave (2024)

El análisis realizado en el notebook `analisis_turismo_2024.ipynb` revela las siguientes tendencias y patrones para el año 2024:

1.  **Volumen de Viajes Mensuales**: Se observa la estacionalidad de los viajes a lo largo del año, identificando los meses de mayor y menor actividad turística.
    *   ![Viajes Mensuales 2024](img/viajes_mensuales_2024.png)

2.  **Destinos Más Populares**: Se identificaron los 5 países o regiones que atrajeron el mayor número de turistas residentes. Generalmente, los países limítrofes y regiones cercanas suelen liderar las estadísticas.
    *   ![Top Destinos 2024](img/top_destinos_2024.png)

3.  **Preferencias de Medio de Transporte**: Se analizó la distribución de los viajes según el medio de transporte utilizado (aéreo, fluvial/marítimo, terrestre), destacando cuál es el predominante.
    *   ![Distribución por Transporte 2024](img/distribucion_transporte_2024.png)

4.  **Estacionalidad por Medio de Transporte**: Un análisis más detallado muestra cómo la elección del medio de transporte varía a lo largo de los meses, influenciada por factores como la distancia, el costo y la naturaleza del viaje.
    *   ![Viajes Mensuales por Transporte 2024](img/viajes_mensuales_por_transporte_2024.png)

5.  **Ejemplo Específico: Viajes a Brasil (Destino Más Popular)**: Se profundiza en el destino más popular, mostrando cómo los turistas residentes viajaron a este país a lo largo de 2024, desglosado por medio de transporte.
    *   ![Viajes a Brasil por Transporte 2024](img/viajes_brasil_transporte_2024.png)

6.  **Contexto Histórico (2016-2024)**: Aunque el foco principal es 2024, una mirada rápida a la tendencia general desde 2016 muestra el impacto de eventos como la pandemia de COVID-19 y la subsiguiente recuperación del sector turístico.
    *   ![Tendencia Anual 2016-2024](img/viajes_anuales_tendencia.png)
