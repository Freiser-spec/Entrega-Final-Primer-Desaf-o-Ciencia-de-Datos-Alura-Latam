# Análisis de Datos de Tiendas Alura Latam

Este proyecto consistió en el análisis del rendimiento de cuatro tiendas online de Alura Latam, con el objetivo de proporcionar información clave y recomendaciones basadas en los datos de ventas. El análisis abarcó diversos aspectos, incluyendo ingresos totales, categorías de productos, satisfacción del cliente, productos más/menos vendidos y costos de envío.

## Contenido del Repositorio

* `AluraStoreLatam.ipynb`: Jupyter Notebook que contiene el código Python utilizado para el análisis de datos, la generación de visualizaciones y la elaboración del informe final.
* `base-de-datos-challenge1-latam/`: Carpeta que contiene los archivos CSV con los datos de cada una de las cuatro tiendas analizadas.
    * `tienda_1 .csv`: Datos de la Tienda 1.
    * `tienda_2.csv`: Datos de la Tienda 2.
    * `tienda_3.csv`: Datos de la Tienda 3.
    * `tienda_4.csv`: Datos de la Tienda 4.
* `mapa_ventas_Tienda 1.html`: Mapa interactivo generado con Folium mostrando la distribución geográfica de las ventas de la Tienda 1.
* `mapa_ventas_Tienda 2.html`: Mapa interactivo generado con Folium mostrando la distribución geográfica de las ventas de la Tienda 2.
* `mapa_ventas_Tienda 3.html`: Mapa interactivo generado con Folium mostrando la distribución geográfica de las ventas de la Tienda 3.
* `mapa_ventas_Tienda 4.html`: Mapa interactivo generado con Folium mostrando la distribución geográfica de las ventas de la Tienda 4.
* `README.md`: Este archivo, que proporciona una descripción general del proyecto.

## Objetivo del Proyecto

El objetivo principal fue analizar los datos de ventas de las diferentes tiendas para identificar patrones, tendencias y métricas clave de rendimiento. Esta información se utilizó para responder preguntas específicas y, finalmente, para proporcionar una recomendación sobre qué tienda sería la más adecuada para un potencial vendedor (Sr. Juan) en función del análisis realizado.

## Metodología

El proyecto se llevó a cabo utilizando las siguientes herramientas y técnicas:

* **Python:** Lenguaje de programación principal para el análisis de datos.
* **Pandas:** Librería para la manipulación y análisis de datos estructurados (DataFrames).
* **NumPy:** Librería para operaciones numéricas eficientes.
* **Matplotlib:** Librería para la creación de visualizaciones estáticas, interactivas y animadas en Python. Se utilizaron gráficos de barras y de pastel para representar los datos.
* **Folium:** Librería para la creación de mapas interactivos basados en Leaflet.js, utilizada para visualizar la distribución geográfica de las ventas.

El análisis incluyó los siguientes pasos:

1.  **Carga y exploración inicial de los datos:** Se cargaron los datos de cada tienda en DataFrames de Pandas y se examinó su estructura.
2.  **Cálculo de ingresos totales por tienda:** Se sumaron los precios de venta para determinar la facturación total de cada tienda.
3.  **Análisis de categorías de productos:** Se identificaron las categorías de productos más y menos vendidas en cada tienda.
4.  **Cálculo de calificaciones promedio de los clientes:** Se determinó la satisfacción promedio del cliente en cada tienda a través de las calificaciones.
5.  **Identificación de productos más y menos vendidos:** Se encontraron los productos con mayor y menor número de ventas en cada tienda.
6.  **Cálculo del costo de envío promedio:** Se analizó el gasto promedio en envío para cada tienda.
7.  **Exploración de coordenadas geográficas:** Se utilizaron las coordenadas de latitud y longitud para visualizar la distribución geográfica de las ventas mediante gráficos de dispersión (Matplotlib) y mapas interactivos (Folium).
8.  **Elaboración de un informe final:** Se sintetizaron los hallazgos del análisis en un informe que proporciona una recomendación basada en la evidencia de los datos.

## Hallazgos Clave y Recomendación

[**Nota:** Esta sección debe resumir brevemente los principales hallazgos del análisis (por ejemplo, qué tienda tuvo mayores ingresos, cuáles fueron las categorías más populares, etc.) y la recomendación final dada en el informe (por ejemplo, se recomendó la Tienda 1 debido a su mayor potencial de ingresos).]

Basado en el análisis exhaustivo de los datos, se recomendó al Sr. Juan considerar principalmente la **Tienda 1** para vender sus productos debido a su mayor potencial de ingresos y la fuerte demanda en categorías de productos relevantes.

## Cómo Utilizar este Repositorio

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/sindresorhus/del](https://github.com/sindresorhus/del)
    ```
2.  **Abrir el Jupyter Notebook:** Ejecuta el archivo `AluraStoreLatam.ipynb` en Jupyter Notebook o Google Colab para revisar el código del análisis y las visualizaciones generadas.
3.  **Explorar los mapas interactivos:** Abre los archivos `mapa_ventas_Tienda_X.html` en tu navegador web para visualizar la distribución geográfica de las ventas de cada tienda.
4.  **Revisar el informe final:** El informe completo se encuentra dentro del Jupyter Notebook y se imprime al final de su ejecución.

## Créditos

Este proyecto se basa en el "Primer Challenge de Data Science para One" de Alura Latam.
