 Análisis de clientes de ConnectaTel
**Objetivo del proyecto**

El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones en Latinoamérica, utilizando información registrada hasta el año 2024.

A través del análisis exploratorio de datos, la limpieza y la segmentación de clientes, se busca identificar patrones de consumo, detectar valores atípicos y generar recomendaciones que contribuyan a mejorar los planes ofrecidos y las estrategias de retención de clientes.

**Datasets utilizados**

Para desarrollar el análisis se utilizaron tres conjuntos de datos:

- **`plans.csv`**: contiene información sobre los planes de servicio, incluyendo precios mensuales, minutos y mensajes incluidos, gigabytes disponibles y tarifas por consumo adicional.
- **`users_latam.csv`**: contiene información de los clientes, como edad, ciudad, fecha de registro, plan contratado y fecha de cancelación del servicio.
- **`usage.csv`**: contiene registros del uso de los servicios de telecomunicaciones, como llamadas, mensajes y duración de las llamadas.

***Etapas del análisis***

El proyecto se desarrolló mediante las siguientes etapas:

1. **Carga y exploración de datos:** importación de los datasets, revisión de las primeras filas, estructura, tipos de datos y estadísticas descriptivas.
2. **Limpieza y preparación:** identificación y tratamiento de valores faltantes, datos inconsistentes y fechas inválidas.
3. **Análisis exploratorio:** estudio de las distribuciones de las variables y revisión de posibles valores atípicos mediante estadísticas y visualizaciones.
4. **Integración de datos:** agregación de los registros de uso por cliente y combinación con la información de usuarios y planes cuando corresponde.
5. **Segmentación de clientes por uso:** clasificación de los clientes en grupos de bajo uso, uso medio y alto uso, según la cantidad de llamadas y mensajes.
6. **Segmentación de clientes por edad:** clasificación en jóvenes, adultos y adultos mayores.
7. **Visualización de resultados:** elaboración de histogramas, diagramas de caja y gráficos de distribución de los segmentos.
8. **Análisis ejecutivo y recomendaciones:** identificación de oportunidades para mejorar la calidad de los datos, adaptar los planes de servicio y orientar las estrategias de retención.

***Herramientas utilizadas***

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

***Cómo ejecutar el notebook***

El análisis se encuentra documentado en un notebook de Jupyter con extensión `.ipynb`.

Se puede ejecutar mediante Google Colab o Jupyter Notebook.

***Guía de reproducción***

Para reproducir el análisis:

1. Obtén los archivos `plans.csv`, `users_latam.csv` y `usage.csv`.
2. Abre el notebook del proyecto.
3. Comprueba que los nombres y las rutas de los archivos coincidan con los utilizados en el código.
4. Ejecuta las celdas en orden para cargar, limpiar, explorar e integrar los datos.
5. Reproduce las visualizaciones y los procedimientos de segmentación.
6. Revisa los resultados y las recomendaciones finales.

***Nota*** el notebook hace referencia originalmente a rutas como `/datasets/plans.csv`, `/datasets/users_latam.csv` y `/datasets/usage.csv`. Estas rutas pueden necesitar ajustes según el entorno de ejecución.

****Resultados esperados***

El análisis permite construir un perfil estadístico de los clientes, explorar sus patrones de consumo, identificar posibles valores atípicos y comparar segmentos según edad y nivel de uso.

Los resultados pueden servir como punto de partida para diseñar ofertas diferenciadas, revisar la adecuación de los planes y estudiar oportunidades de retención. Las decisiones comerciales deben complementarse con indicadores de ingresos, costos y cancelación de clientes.


