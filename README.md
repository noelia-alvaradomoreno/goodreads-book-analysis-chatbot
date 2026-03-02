# Goodreads Book Analysis + Chatbot + RandomForest

Proyecto en Google Colab basado en el dataset **Goodreads Books (Kaggle)**.  
Incluye análisis exploratorio de datos (EDA), visualizaciones y un chatbot simple por reglas integrado con un modelo de Machine Learning.

## Qué incluye
- Carga y limpieza del dataset (`books.csv`)
- Análisis exploratorio: libros mejor puntuados y más votados, idioma más frecuente, rating promedio, etc.
- Visualizaciones (gráficos de barras) con interpretación
- **Modelo RandomForest** para clasificar si un libro tiene “buen rating” (≥ 4.0)
  - Preprocesamiento con **One-Hot Encoding** usando `pd.get_dummies`
  - Evaluación con *accuracy* y número de aciertos
- Chatbot interactivo en consola
  - Responde con resultados reales del análisis
  - Permite `predecir <texto>` y muestra **predicción vs rating real** del dataset

## Tecnologías
- Python (Pandas, Matplotlib)
- Scikit-learn (RandomForest, train_test_split, métricas)

## Cómo ejecutarlo
1. Abrir el archivo `.ipynb` en Google Colab.
2. Cargar el dataset `books.csv` (descargado desde Kaggle).
3. Ejecutar las celdas en orden hasta llegar al chatbot.
4. Probar comandos como:
   - `idioma mas frecuente`
   - `promedio rating`
   - `libro mas votado`
   - `explica grafico votados`
   - `explica grafico puntuados`
   - `predecir harry potter`

## Dataset
- Goodreads Books (Kaggle)
