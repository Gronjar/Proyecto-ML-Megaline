# 🤖 Proyecto de Machine Learning - Megaline

Este proyecto forma parte del curso de análisis de datos y machine learning.  
El objetivo es desarrollar un **modelo de clasificación** que recomiende el plan de telefonía óptimo (Smart o Ultra) en función del comportamiento de los usuarios.  

## 📊 Contenido del proyecto
- Importación y exploración del dataset `users_behavior.csv`
- Segmentación en **train / validation / test**
- Entrenamiento y comparación de modelos de Machine Learning
- Ajuste de hiperparámetros
- Evaluación de exactitud (umbral mínimo: 0.75)
- Prueba final en conjunto de test
- Prueba de cordura del modelo


## 📌 Dataset
Cada fila corresponde al uso mensual de un cliente:
- `calls` → número de llamadas  
- `minutes` → duración total de llamadas  
- `messages` → número de mensajes enviados  
- `mb_used` → tráfico de internet en MB  
- `is_ultra` → plan actual (Ultra = 1, Smart = 0)

## 🚀 Herramientas utilizadas
- Python 3
- pandas
- scikit-learn
- matplotlib / seaborn
