# Procesamiento del Lenguaje Natural – Trabajos Prácticos

Este repositorio contiene los cuatro trabajos prácticos realizados en el marco de la materia **Procesamiento del Lenguaje Natural**, dictada por el Dr. Rodrigo Cárdenas Szigety y el Dr. Nicolás Vattuone en la carrera de Especializacion en Inteligencia Artificial de la Universidad de Buenos Aires.

Cada notebook aborda un problema distinto del procesamiento de texto, aplicando técnicas modernas de PLN, modelos clásicos y redes neuronales, combinando teoría y práctica sobre diversos datasets.

---

## 🔹 TP1 - Clasificación y Similaridad de Textos

**Notebook:** `ResolucionTP1.ipynb`  
**Dataset:** [20 Newsgroups](https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html)  
**Objetivo:** Analizar similitud semántica entre documentos y entrenar clasificadores supervisados.

### Contenidos:
- Vectorización con **TF-IDF**.
- Cálculo de **similaridad coseno** entre documentos.
- Entrenamiento y comparación de modelos de clasificación:
  - `Multinomial Naïve Bayes`
  - `Complement Naïve Bayes`
- Análisis de similaridad entre palabras transponiendo la matriz documento-término.

---

## 🔹 TP2 - Word Embeddings y Visualización

**Notebook:** `ResolucionTP2.ipynb`  
**Dataset:** `movie_reviews` de NLTK  
**Objetivo:** Entrenar embeddings de palabras y visualizar relaciones semánticas.

### Contenidos:
- Tokenización y limpieza de texto.
- Entrenamiento de **Word2Vec** (modelo Skip-Gram).
- Búsqueda de palabras más similares.
- Pruebas de analogías semánticas.
- Visualización de embeddings:
  - Reducción dimensional con **t-SNE**.
  - Heatmap de **similaridad coseno** entre palabras seleccionadas.

---

## 🔹 TP3 - Modelado de Lenguaje con RNN

**Notebook:** `ResolucionTP3.ipynb`  
**Dataset:** Guión de la serie *Friends* (extraído de un archivo `.txt`)  
**Objetivo:** Entrenar un modelo de lenguaje carácter a carácter utilizando redes recurrentes.

### Contenidos:
- Limpieza y normalización del corpus.
- Tokenización carácter a carácter.
- Preparación de datos para tareas many-to-many.
- Entrenamiento de un modelo secuencial:
  - `SimpleRNN` con Keras
- Evaluación del modelo con **perplejidad (PPL)** y early stopping.

---

## 🔹 TP4 - Chatbot Seq2Seq

**Notebook:** `ResolucionTP4.ipynb`  
**Dataset:** Conversaciones del challenge [ConvAI2](http://convai.io/data/)  
**Objetivo:** Construir un chatbot usando una arquitectura encoder-decoder con LSTM.

### Contenidos:
- Limpieza y preprocesamiento de diálogos.
- Tokenización de secuencias para entrada y salida.
- Definición del vocabulario y padding de secuencias.
- Preparación del dataset para un modelo Seq2Seq.
- Uso de **embeddings** preentrenados (FastText).
- Generación de respuestas automáticas con red neuronal recurrente `LSTM`.

---

## 📚 Herramientas utilizadas

- **Python**
- **NLTK**, **Gensim**, **Scikit-learn**, **Keras**, **TensorFlow**
- **Matplotlib**, **Seaborn**, **TSNE**, **Pandas**, **NumPy**

---

## 👨‍🏫 Profesores

- Dr. Rodrigo Cárdenas Szigety  
- Dr. Nicolás Vattuone


