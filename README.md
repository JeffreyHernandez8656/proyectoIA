# proyectoIA | predicción del género musical

Aquí encontrarás el proyecto de Inteligencia Artificial **FlixGenAI**, un sistema de recomendación de películas y series.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Banner
![Banner del Proyecto FlixGenAI](https://github.com/JeffreyHernandez8656/proyectoIA/blob/main/Banner.jpeg)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Autores

* Nestor Jeffrey Hernandez Ruiz - 2215108
* Juan carlos Arias Gonzalez - 2225007
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
##Objetivo
* Desarrollar un modelo de clasificación de géneros musicales utilizando características de audio con el fin de predecir el género con alta precisión.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
##Objetivos Específicos
* Evaluar la efectividad de diferentes algoritmos de machine learning en la clasificación de géneros musicales.
* Identificar las características de audio más relevantes.
* Optimizar el modelo para mejorar su rendimiento y precisión.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
##Información del Dataset
* Fuente: Dataset de Spotify (50,000 canciones).
* Géneros incluidos: Electrónica, Anime, Jazz, Alternativa, Country, Rap, Blues, Rock, Clásica y Hip-Hop.
* Características de audio: acousticness, danceability, energy, instrumentalness, loudness, valence, tempo, popularity, entre otros.
* Calidad garantizada: Proporcionado por la API de Spotify.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
##Procesamiento del Dataset
* Limpieza de datos: Eliminación de duplicados, manejo de nulos y outliers.
* Conversión de datos: Tipado correcto mediante pd.to_numeric() y df.loc[].
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
##Librerías utilizadas:
* Pandas para manejo de datos.
* NumPy para operaciones numéricas.
* Estadísticas y Visualización
* Análisis descriptivo: Medias, medianas, desviación estándar.
* Análisis de correlación: Matrices y gráficos.
* Visualizaciones: Histogramas, scatter plots, diagramas de caja, mapas de calor.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
##Modelos Utilizados Clasificación Supervisada
* Árbol de Decisión (Decision Tree)
* Random Forest
* Support Vector Machine (SVM)
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
##Resultados con Validación Cruzada (MAE):
* Decision Tree: ~14.02
* Random Forest: ~10.07 
* SVM: ~12.36
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
##Modelos No Supervisados y Reducción de Dimensionalidad
* PCA: Visualización 2D, pero limitada (varianza explicada < 50%).
* t-SNE: Mejora la agrupación, pero presenta cierta superposición.
* UMAP: Agrupa mejor géneros como Clásica y Hip-Hop.
* K-Means: Método del codo sugiere k=4 como óptimo.
* Distribución de Outliers: Clásica presenta más valores atípicos.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
##Conclusión
* El proyecto desarrolló un modelo para clasificar géneros musicales basado en características de audio. Random Forest mostró el mejor rendimiento (MAE = 10.07, precisión = 0.90). Las técnicas de reducción de dimensionalidad ayudaron a visualizar agrupaciones naturales entre géneros, revelando tanto similitudes como diferencias significativas, útiles para futuras aplicaciones como sistemas de recomendación.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
##Enlaces del Proyecto
* **Notebook:** [[Link al Notebook en Google Colab o Drive](https://github.com/JeffreyHernandez8656/proyectoIA/blob/main/proyectoia_Juan_Nestor.ipynb)]

* **Repositorio GitHub:** [[Repositorio GitHub](https://github.com/JeffreyHernandez8656/proyectoIA)]

* **Link de las Diapositivas:** [Ver Diapositivas](https://github.com/JeffreyHernandez8656/proyectoIA/blob/main/predicci%C3%B3n%20del%20g%C3%A9nero%20musical.pptx)]

* **Video del Proyecto:** [[Enlace si está disponible](https://youtu.be/UCSGr3GRNVY)]
