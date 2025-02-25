🌟 Análisis de Datos de Netflix

✨ Introducción

Este proyecto realiza un Análisis Exploratorio de Datos (EDA) sobre un dataset de Netflix para responder diversas preguntas relacionadas con la cantidad, el tipo y las tendencias del contenido disponible en la plataforma. Se han aplicado técnicas de manipulación de datos con Pandas, visualización con Matplotlib y Seaborn, y se han generado insights clave sobre la plataforma.

📊 Análisis General

1. ¿Cuántas películas y series hay en el dataset?

Se calcula el número total de registros y se diferencia entre películas y series.

2. ¿Cuál es el año con más estrenos en la plataforma?

Se analiza la columna release_year para determinar el año con mayor cantidad de lanzamientos.

3. ¿Cuántos títulos tiene cada categoría de contenido (películas vs. series)?

Se agrupan y cuentan los registros según la columna type ("Movie" vs. "TV Show").

4. ¿Cuál es la duración promedio de las películas en minutos?

Se extraen los minutos de la columna duration y se calcula la media.

🎬 Análisis de Contenido y Tendencias

5. ¿Cuáles son los géneros más populares en la plataforma?

Se analiza la columna listed_in, explotando y contando las categorías de género.

6. ¿Cuál es el país que más contenido ha producido?

Se agrupa la columna country y se obtiene el país con mayor cantidad de producciones.

7. ¿Cómo ha cambiado el número de lanzamientos por año?

Se visualiza la tendencia de estrenos a lo largo de los años.

8. ¿Qué directores han dirigido más contenido en la plataforma?

Se extraen y cuentan los directores con mayor presencia en el dataset.

9. ¿Cuáles son los actores más frecuentes en el catálogo?

Se analiza la columna cast, explotando los nombres y calculando su frecuencia.

📅 Análisis Temporal

10. ¿Cuántos títulos se han agregado por año/mes?

Se usa la columna date_added para analizar la frecuencia de nuevos contenidos por fecha.

11. ¿Cuál es la relación entre release_year y date_added?

Se examina si Netflix agrega más contenido reciente o títulos antiguos.

12. ¿En qué meses se agregan más títulos a la plataforma?

Se agrupan los registros por mes para detectar patrones de adición de contenido.

⭐ Análisis de Ratings

13. ¿Cuál es la distribución de ratings en la plataforma?

Se analiza la columna rating para ver la frecuencia de cada categoría.

14. ¿Qué tipo de contenido predomina en cada rating?

Se analiza cuántas películas vs. series hay en cada clasificación por edad.

15. ¿Hay alguna relación entre el rating y la duración del contenido?

Se evalúa si ciertos ratings están asociados a películas más largas o cortas.

🔎 Análisis Específico de Directores y Actores

16. ¿Cuáles son los directores con más títulos en la plataforma?

Se cuentan y listan los directores con mayor cantidad de obras.

17. ¿Cuáles son los actores que más aparecen en el catálogo?

Se extraen los actores más frecuentes en el dataset.

18. ¿Qué actores han trabajado juntos en varias producciones?

Se analiza la colaboración entre actores en múltiples títulos.

💡 Exploratory Data Analysis (EDA)

Se realiza un EDA detallado para comprender la estructura del dataset, detectar valores nulos, outliers y relaciones clave en los datos. Entre los pasos incluidos:

Carga y visualización de datos.

Limpieza y formateo de columnas.

Manejo de valores nulos y duplicados.

Análisis estadístico básico.

Visualización de datos clave.

🔧 Herramientas Utilizadas

Python (Pandas)

Jupyter Notebook 

Power BI / Tableau (Tengo pendiente realizar visualizaciones con Power BI)

📄 Dataset

El dataset utilizado proviene de kaggle (Netflix Movies and TV Shows) en formato CSV y contiene información sobre títulos, directores, elenco, año de lanzamiento, país, géneros, fecha de adición, duración y clasificación por edad.

📖 Conclusiones

Este análisis ofrece insights clave sobre el contenido disponible en Netflix, ayudando a identificar patrones en producciones, actores, directores y tendencias de consumo.

🛠️ Autor: [Jhon Arley Castañeda Vergara
💡 Contacto: [www.linkedin.com/in/arley-castañeda-3a981526]
