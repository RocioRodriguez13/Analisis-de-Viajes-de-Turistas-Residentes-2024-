# Análisis de Viajes de Turistas Residentes en Argentina (2024) 🇦🇷🛫🛥️🗺️

Este proyecto personal se centra en el análisis exploratorio de los viajes realizados por turistas residentes de Argentina, con un enfoque principal en las tendencias observadas durante el año 2024. El objetivo es identificar patrones clave en destinos, medios de transporte y estacionalidad del turismo emisivo.

## Datos 📊

El dataset utilizado, `turistas-residentes-serie.csv`, contiene información detallada sobre los viajes, incluyendo las siguientes columnas:

-   `indice_tiempo`: Fecha del registro (mensual), abarcando desde enero de 2016 hasta mayo de 2025.
-   `medio_de_transporte`: Medio utilizado para el viaje (Aérea, Fluvial/Marítima, Terrestre).
-   `pais_destino`: País o región de destino.
-   `viajes_de_turistas_residentes`: Número de viajes registrados en la entrada correspondiente.

Para este análisis, nos enfocamos en el período de datos hasta finales de 2024 (si hay datos completos para 2024, o la porción más completa si los datos de 2025 son incompletos), considerando este como el año más reciente con información sustancial para un análisis anual.

## Preguntas Clave / Objetivos del Análisis

A través de este análisis exploratorio de datos (EDA), se buscaron responder preguntas como:

-   ¿Cuál es la tendencia mensual de viajes de turistas residentes en 2024?
-   ¿Cuáles fueron los destinos más populares en 2024?
-   ¿Cómo se distribuyen los viajes según el medio de transporte en 2024?
-   ¿Cómo se compara el volumen de viajes en 2024 con años anteriores (especialmente pre-pandemia y de recuperación)?
-   ¿Qué impacto tuvo la pandemia de COVID-19 en las tendencias de viajes a lo largo del tiempo?
-   ¿Cómo se comporta la categoría "Resto del mundo" en comparación con los destinos específicos de mayor volumen?

## Análisis y Visualizaciones Realizadas

El notebook `Análisis_Exploratorio_Turismo_2024_.ipynb` incluye los siguientes pasos de análisis y visualizaciones clave:

1.  **Carga y Preprocesamiento de Datos:** Conversión de tipos de datos, extracción de componentes de tiempo (año, mes) y limpieza/estandarización de columnas.
2.  **Estadísticas Descriptivas:** Resúmenes numéricos y estructurales del dataset.
3.  **Análisis de Estacionalidad Mensual (2024):** Visualización de la distribución de viajes a lo largo de los meses.
4.  **Top Destinos (2024):** Identificación y visualización de los países/regiones de destino más visitados.
5.  **Distribución por Medio de Transporte (2024):** Gráficos que muestran la proporción de viajes por vía aérea, terrestre y fluvial/marítima.
6.  **Viajes Mensuales por Medio de Transporte (2024):** Un análisis apilado para ver la evolución del uso de cada medio a lo largo del año.
7.  **Tendencia de Viajes Anuales:** Comparación del volumen total de viajes desde 2016 hasta 2024 (y datos parciales de 2025) para observar el impacto de la pandemia y la recuperación.
8.  **Crecimiento Porcentual Anual (YoY):** Análisis del crecimiento interanual para cuantificar la recuperación y las fluctuaciones.
9.  **Análisis de "Resto del Mundo":** Agrupación de destinos menos frecuentes para entender su peso en el panorama general del turismo.
10. **Comparativa Mensual Año a Año:** Gráficos que superponen los patrones mensuales de 2024 con años clave (pre-pandemia como 2019, y de recuperación como 2023) para identificar tendencias y cambios estacionales.

## Conclusiones Clave

-   El año 2024 mostró una **recuperación sostenida** en el volumen de viajes de turistas residentes, aunque no todos los indicadores han alcanzado completamente los niveles pre-pandemia de 2019.
-   El mes de **Enero** se consolidó como el de mayor actividad turística en 2024, lo que sugiere una fuerte estacionalidad asociada a las vacaciones de verano.
-   **Brasil, Chile, Uruguay y Paraguay** continúan siendo los principales destinos elegidos por los turistas residentes, destacando la importancia del turismo regional.
-   El **transporte terrestre** fue el medio más utilizado, confirmando su rol predominante en los viajes regionales.
-   La **pandemia de COVID-19** causó una caída drástica en 2020 y 2021, seguida de una recuperación muy marcada en 2022 y un crecimiento más moderado en los años subsiguientes.

## Cómo Utilizar el Proyecto

Para replicar este análisis o explorar los datos, sigue estos pasos:

1.  **Clonar el Repositorio:**
    ```bash
    git clone https://github.com/RocioRodriguez13/Analisis-de-Viajes-de-Turistas-Residentes-2024-.git
    ```

2.  **Navegar al Directorio del Proyecto:**
    ```bash
    cd Analisis-de-Viajes-de-Turistas-Residentes-2024-/Analisis/
    ```

3.  **Abrir el Notebook:**
    Puedes abrir el archivo `Análisis_Exploratorio_Turismo_2024_.ipynb` en Google Colab (subiéndolo a tu Drive o abriendo desde GitHub directamente) o en tu entorno local de Jupyter Notebook/JupyterLab.

4.  **Ejecutar las Celdas:**
    Ejecuta todas las celdas del notebook en orden. Asegúrate de que el archivo `turistas-residentes-serie.csv` y la carpeta `img/` estén presentes en el mismo directorio que el notebook.

## Tecnologías Utilizadas

-   **Python**: Lenguaje de programación principal.
-   **Pandas**: Para la manipulación y análisis de datos.
-   **Matplotlib** y **Seaborn**: Para la visualización de datos y la creación de gráficos estadísticos.
-   **Jupyter Notebook / Google Colab**: Para el desarrollo interactivo, la ejecución del código y la presentación del análisis.

## Mejoras Futuras / Posible Trabajo Adicional

-   **Análisis Predictivo:** Implementar modelos de series de tiempo (ARIMA, Prophet, etc.) para pronosticar futuras tendencias de viajes.
-   **Segmentación de Destinos:** Agrupar destinos por características (ej. playa, montaña, ciudad) y analizar patrones específicos para cada segmento.
-   **Impacto de Factores Externos:** Integrar datos de eventos económicos (inflación, tipo de cambio), festivos nacionales o eventos turísticos específicos para analizar su correlación con los volúmenes de viaje.
-   **Análisis de Sentimiento:** Si se dispusiera de datos de redes sociales o reseñas, se podría analizar el sentimiento de los turistas.
-   **Creación de un Dashboard Interactivo:** Desarrollar un dashboard (ej. con Dash, Streamlit o Tableau) para permitir la exploración dinámica de los datos.


Este `README.md` mejorado no solo describe tu proyecto, sino que también **vende tus habilidades** de una manera muy efectiva para un rol de analista de datos. ¡Te felicito por el esfuerzo y por buscar la mejora continua!
