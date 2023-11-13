# Análisis de Redes Sociales y Comportamiento del Consumidor

Este proyecto utiliza el método de los k vecinos más cercanos (KNN) para analizar la relación entre el comportamiento en redes sociales y las decisiones de compra en línea. Se generó un conjunto de datos ficticio y se implementó un modelo KNN para clasificar a los usuarios en categorías de compra o no compra.

## Contenido

1. [Estructura del Proyecto](#estructura-del-proyecto)
2. [Requisitos](#requisitos)
3. [Instrucciones de Uso](#instrucciones-de-uso)
4. [Resultados y Visualizaciones](#resultados-y-visualizaciones)
5. [Posibles Mejoras](#posibles-mejoras)
6. [Limitaciones](#limitaciones)

## Estructura del Proyecto

- `analisis_redes_sociales.ipynb`: Jupyter Notebook con el código del proyecto.
- `README.md`: Documentación del proyecto.

## Requisitos

- Python 3.x
- Bibliotecas de Python: numpy, pandas, scikit-learn, matplotlib, seaborn.

## Instrucciones de Uso

1. Clona o descarga este repositorio en tu máquina local.
2. Abre el archivo `analisis_redes_sociales.ipynb` en un entorno Jupyter Notebook.
3. Ejecuta cada celda en orden para reproducir los resultados.

## Resultados y Visualizaciones

El proyecto genera un conjunto de datos ficticio, entrena un modelo KNN y evalúa su precisión en la clasificación de usuarios. Se presentan estadísticas descriptivas, métricas de evaluación adicionales, una curva ROC y un Heatmap para visualizar la correlación entre las variables.

## Posibles Mejoras

- Optimización de hiperparámetros para mejorar la precisión del modelo.
- Manejo de desequilibrios en las clases "Compra" y "No compra".
- Análisis más profundo de características para identificar patrones clave.

## Limitaciones

- El tiempo de ejecución de KNN puede aumentar con conjuntos de datos más grandes.
- Fenómeno de la maldición de la dimensionalidad en conjuntos de datos con muchas dimensiones.
