| Información | Detalle |
|------------|---------|
| Autor | Alberto López Gutiérrez |
| Institución | IEBS Digital School |
| Programa | Postgrado en IA y Machine Learning |
| Módulo | Procesamiento del Lenguaje Natural |
| Lenguaje | Python |
| Estado | Finalizado |

# Clasificación de Sentimientos en Reseñas de Películas mediante Naive Bayes y Redes Neuronales

![Python](https://img.shields.io/badge/Python-3.13-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.21-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-f7931e)
![NLTK](https://img.shields.io/badge/NLTK-NLP-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## Flujo general del proyecto

<p align="center">
  <img src="images/flujo_metodologico.png" alt="Metodología del Proyecto" width="1000">
</p>

---

Este repositorio presenta el proyecto final desarrollado para el módulo de Procesamiento del Lenguaje Natural (PLN) del Postgrado en Inteligencia Artificial y Machine Learning de IEBS Digital School.

El objetivo del proyecto consiste en comparar el desempeño de un modelo clásico de aprendizaje automático (Naive Bayes) frente a una red neuronal sencilla para la clasificación automatica de sentimientos en reseñas de películas.

## Tabla de Contenido

- Descripción
- Objetivos
- Tecnologías
- Dataset
- Metodología
- Resultados
- Estructura
- Documentación
- Cómo ejecutar
- Autor

## Descripción

Este proyecto desarrolla un sistema de clasificación automatica de sentimientos utilizando técnicas de Procesamiento del Lenguaje Natural (PLN).

Se comparan dos enfoques ampliamente utilizados para la clasificación de texto:

- Multinomial Naive Bayes
- Red Neuronal implementada con TensorFlow/Keras

Ambos modelos fueron entrenados utilizando el corpus **movie_reviews** de NLTK y evaluados mediante diferentes métricas de desempeño para analizar sus fortalezas y limitaciones.

---

## Objetivos

- Implementar un clasificador basado en Naive Bayes.
- Diseñar una red neuronal sencilla utilizando Keras.
- Comparar objetivamente ambos modelos.
- Analizar los resultados mediante diferentes métricas.
- Comprender el impacto del preprocesamiento en tareas de PLN.

---

## Tecnologías utilizadas

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

Características principales:

- 2,000 reseñas
- clasificación binaria
- 1,000 positivas
- 1,000 negativas
- Idioma inglés

---

## Metodología

El flujo general del proyecto comprende las siguientes etapas:

1. Carga del corpus.
2. Preprocesamiento del texto.
3. Vectorización mediante CountVectorizer.
4. Entrenamiento de Naive Bayes.
5. Entrenamiento de una Red Neuronal.
6. Evaluación comparativa mediante métricas y visualizaciones.

---

## Resultados

| Modelo | Accuracy | Precision | Recall | F1-score | ROC-AUC |
|---------|---------:|----------:|--------:|---------:|--------:|
| Naive Bayes | 0.8100 | 0.7925 | 0.8400 | 0.8155 | 0.8870 |
| Red Neuronal | **0.8275** | 0.7835 | **0.9050** | **0.8399** | **0.9175** |

> Este proyecto compara un modelo probabilístico clásico (Naive Bayes) con una red neuronal sencilla para la clasificación automática de sentimientos utilizando el corpus *movie_reviews* de NLTK.

La red neuronal obtuvo el mejor desempeño global, especialmente en Recall y ROC-AUC, mientras que Naive Bayes demostró ser una excelente línea base gracias a su simplicidad y eficiencia computacional.

---

## Resultados destacados

- La red neuronal obtuvo el mayor Accuracy.
- Alcanzó el mejor Recall para identificar reseñas positivas.
- Naive Bayes presentó un desempeño competitivo con un costo computacional considerablemente menor.
- Ambos modelos demostraron la importancia del preprocesamiento en tareas de PLN.

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

Este repositorio incluye distintos niveles de documentación para facilitar la comprensión y reproducción del proyecto.

| Recurso | Descripción |
|---------|-------------|
| 📓 Notebook | Implementación completa del proyecto |
| 📄 Informe PDF | Documento técnico completo |
| 📝 Informe Word | Versión editable del informe |

---

## Publicaciones relacionadas

El desarrollo de este proyecto será complementado con un artículo técnico en Medium donde se describirá el proceso de construcción, los principales retos encontrados y las lecciones aprendidas durante la comparación entre un modelo probabilístico clásico y una red neuronal para clasificación de sentimientos.

> **Disponible próximamente.**

---

## Instalación y ejecución

```bash
git clone https://github.com/aLópez2003/nlp-sentiment-analysis-movie-reviews-by-alberto-lopez.git

cd nlp-sentiment-analysis-movie-reviews-by-alberto-lopez

pip install -r requirements.txt

jupyter notebook
```

---

## Referencias

- NLTK Documentation
- TensorFlow Documentation
- Scikit-learn Documentation
- NLTK Movie Reviews Corpus

## Autor

**Alberto López Gutiérrez**

Proyecto desarrollado como parte del **Postgrado en Inteligencia Artificial y Machine Learning** de **IEBS Digital School**.

## Agradecimientos

Este proyecto fue desarrollado como parte del Postgrado en Inteligencia Artificial y Machine Learning de IEBS Digital School.

Agradezco especialmente a la profesora **Layla Schelli** por los conocimientos compartidos, la orientación brindada y el acompañamiento durante el desarrollo de este proyecto.

## Licencia

Este proyecto se distribuye bajo la licencia MIT.

Consulta el archivo LICENSE para más información.
