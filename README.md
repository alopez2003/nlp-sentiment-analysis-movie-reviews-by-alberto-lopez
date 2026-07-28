# nlp-sentiment-analysis-movie-reviews-by-alberto-lopez
# Procesamiento del Lenguaje Natural (PLN)

## Clasificación de Sentimientos en Reseñas de Películas con Modelos Clásicos y Redes Neuronales Sencillas

### Comparación entre Multinomial Naive Bayes y Redes Neuronales con Keras

> Proyecto Final del módulo de **Procesamiento del Lenguaje Natural y LLMs**  
> Postgrado en Inteligencia Artificial y Machine Learning  
> **IEBS Digital School**

---

## Descripción del proyecto

Este proyecto presenta el desarrollo completo de un sistema de clasificación de sentimientos utilizando técnicas de Procesamiento del Lenguaje Natural (PLN). El objetivo principal consiste en comparar el desempeño de un modelo clásico de aprendizaje automático (**Multinomial Naive Bayes**) frente a una **Red Neuronal** implementada con TensorFlow/Keras, utilizando el corpus **movie_reviews** de NLTK.

Para garantizar una comparación objetiva, ambos modelos fueron entrenados utilizando exactamente el mismo conjunto de datos, el mismo proceso de preprocesamiento y la misma representación vectorial mediante **CountVectorizer**. Posteriormente, su desempeño fue evaluado utilizando diversas métricas de clasificación y visualizaciones que permiten interpretar sus fortalezas y limitaciones.

---

## Objetivos

- Preparar un conjunto de datos de texto para tareas de clasificación.
- Implementar un modelo basado en Multinomial Naive Bayes.
- Diseñar y entrenar una Red Neuronal utilizando Keras.
- Comparar ambos enfoques mediante métricas de evaluación.
- Analizar e interpretar los resultados obtenidos.

---

## Tecnologías utilizadas

| Tecnología | Uso |
|------------|-----|
| Python | Lenguaje de programación |
| NLTK | Procesamiento del lenguaje natural |
| Scikit-learn | Modelos de Machine Learning |
| TensorFlow / Keras | Red neuronal |
| Pandas | Manipulación de datos |
| NumPy | Procesamiento numérico |
| Matplotlib | Visualización |
| Jupyter Notebook | Desarrollo del proyecto |

---

## Conjunto de datos

El proyecto utiliza el corpus **movie_reviews**, disponible en la biblioteca **NLTK**.

Características principales:

- 2,000 reseñas de películas
- Distribución balanceada
- 1,000 reseñas positivas
- 1,000 reseñas negativas
- Clasificación binaria de sentimientos

---

## Metodología

El proyecto se desarrolló siguiendo las siguientes etapas:

1. Preparación del entorno.
2. Descarga del corpus.
3. Exploración de los datos.
4. Preprocesamiento del texto.
5. Vectorización mediante CountVectorizer.
6. Entrenamiento del modelo Naive Bayes.
7. Construcción y entrenamiento de la Red Neuronal.
8. Evaluación comparativa.
9. Interpretación de resultados.

---

## Resultados principales

Los modelos fueron evaluados utilizando las siguientes métricas:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

La Red Neuronal obtuvo el mejor desempeño general, mientras que Naive Bayes demostró ser una alternativa muy competitiva debido a su simplicidad y eficiencia computacional.

---

## Contenido del repositorio

```text
.
├── notebook/
├── docs/
├── images/
├── README.md
├── LICENSE
└── requirements.txt
```

---

## Trabajo futuro

Algunas posibles líneas de evolución del proyecto son:

- Incorporar TF-IDF como técnica de representación.
- Evaluar modelos basados en Transformers.
- Comparar embeddings modernos.
- Aplicar el flujo de trabajo a otros dominios de texto.

---

## Autor

**Alberto López Gutiérrez**

Proyecto Final

Procesamiento del Lenguaje Natural

Postgrado en Inteligencia Artificial y Machine Learning

## Profesora

** Layla Schelli**

IEBS Digital School
