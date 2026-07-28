# Clasificacion de Sentimientos mediante Procesamiento del Lenguaje Natural

![Python](https://img.shields.io/badge/Python-3.13-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-f7931e)
![NLTK](https://img.shields.io/badge/NLTK-NLP-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

# Clasificación de Sentimientos en Reseñas de Películas mediante Naive Bayes y Redes Neuronales

<p align="center">
  <img src="images/flujo_metodologico.png" alt="Metodología del Proyecto" width="1000">
</p>

---

Este repositorio presenta el proyecto final desarrollado para el módulo de Procesamiento del Lenguaje Natural (PLN) del Postgrado en Inteligencia Artificial y Machine Learning de IEBS Digital School.

El objetivo del proyecto consiste en comparar el desempeño de un modelo clasico de aprendizaje automático (Naive Bayes) frente a una red neuronal sencilla para la clasificacion automatica de sentimientos en reseñas de peliculas.

## Descripción

Este proyecto desarrolla un sistema de clasificacion automatica de sentimientos utilizando tecnicas de Procesamiento del Lenguaje Natural (PLN).

Se comparan dos enfoques ampliamente utilizados para la clasificacion de texto:

- Multinomial Naive Bayes
- Red Neuronal implementada con TensorFlow/Keras

Ambos modelos fueron entrenados utilizando el corpus **movie_reviews** de NLTK y evaluados mediante diferentes metricas de desempeño para analizar sus fortalezas y limitaciones.

---

## Objetivos

- Implementar un clasificador basado en Naive Bayes.
- Diseñar una red neuronal sencilla utilizando Keras.
- Comparar objetivamente ambos modelos.
- Analizar los resultados mediante diferentes metricas.
- Comprender el impacto del preprocesamiento en tareas de PLN.

---

## Tecnologias utilizadas

- Python
- NLTK
- Scikit-learn
- TensorFlow / Keras
- Pandas
- NumPy
- Matplotlib

---

## Dataset

El proyecto utiliza el corpus **movie_reviews** incluido en la biblioteca NLTK.

Caracteristicas principales:

- 2,000 reseñas
- Clasificacion binaria
- 1,000 positivas
- 1,000 negativas
- Idioma inglés

---

## Metodologia

El flujo general del proyecto comprende las siguientes etapas:

1. Carga del corpus.
2. Preprocesamiento del texto.
3. Vectorizacion mediante CountVectorizer.
4. Entrenamiento de Naive Bayes.
5. Entrenamiento de una Red Neuronal.
6. Evaluacion comparativa mediante metricas y visualizaciones.

---

## Resultados

| Modelo | Accuracy | Precision | Recall | F1-score | ROC-AUC |
|---------|---------:|----------:|--------:|---------:|--------:|
| Naive Bayes | 0.8100 | 0.7925 | 0.8400 | 0.8155 | 0.8870 |
| Red Neuronal | **0.8275** | 0.7835 | **0.9050** | **0.8399** | **0.9175** |

La red neuronal obtuvo el mejor desempeño global, especialmente en Recall y ROC-AUC, mientras que Naive Bayes demostro ser una excelente línea base gracias a su simplicidad y eficiencia computacional.

---

## Estructura del repositorio

```text
.
├── docs/
│   ├── Proyecto_Final_PLN.pdf
│   └── Proyecto_Final_PLN.docx
│
├── images/
│   └── flujo_metodologico.png
│
├── notebook/
│   └── proyecto_final_pln.ipynb
│
├── README.md
├── LICENSE
└── requirements.txt
```

---

## Documentación

Este repositorio incluye distintos niveles de documentación para facilitar la comprension y reproduccion del proyecto.

| Recurso | Descripción |
|---------|-------------|
| 📓 Notebook | Implementacion completa del proyecto |
| 📄 Informe PDF | Documento tecnico completo |
| 📝 Informe Word | Versión editable del informe |

---

## Artículo en Medium

> Proximamente se publicara un artículo donde se describirá el desarrollo del proyecto, los principales aprendizajes y las conclusiones obtenidas durante la comparación entre Naive Bayes y una red neuronal sencilla.

---

## Cómo ejecutar

```bash
git clone https://github.com/alopez2003/nlp-sentiment-analysis-movie-reviews-by-alberto-lopez.git

cd nlp-sentiment-analysis-movie-reviews-by-alberto-lopez

pip install -r requirements.txt

jupyter notebook
```

---

## Autor

**Alberto Lopez Gutierrez**

Proyecto desarrollado como parte del **Postgrado en Inteligencia Artificial y Machine Learning** de **IEBS Digital School**.

## Profesora

**Layla Schelli**

