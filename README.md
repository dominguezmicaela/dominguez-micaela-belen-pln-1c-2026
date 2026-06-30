# Técnicas de Procesamiento del Lenguaje Natural — PLN 1C 2026

Repositorio de proyectos y ejercicios prácticos desarrollados a lo largo de la materia **Procesamiento del Lenguaje Natural**, cursada en 2026.

---
## Trabajo Final PLN:
[RAG Hidrocarburos Argentina](https://github.com/dominguezmicaela/rag_hidrocarburos) — Sistema RAG sobre normativa de hidrocarburos argentina, con embeddings locales, ChromaDB y sugeridor automático de preguntas. [Demo en vivo](https://huggingface.co/spaces/dominguezmic/RAG_Hidrocarburos)

## Proyecto Integrador Final:
[VoxCheck](https://github.com/dominguezmicaela/voxCheck) 
— Sistema de análisis periodístico con RAG, embeddings semánticos y detección de contradicciones.
---

## Descripción

Este repositorio reúne todos los trabajos, notebooks y resolución de ejercicios asociados a la materia. A lo largo de los módulos se trabajan técnicas de PLN aplicadas a casos reales, desde scraping y adquisición de datos hasta modelos de lenguaje, transformers y sistemas RAG.

---

## Tecnologías utilizadas

| Tecnología | Uso |
|------------|-----|
| ![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white) | Lenguaje principal |
| ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white) | Entorno de desarrollo |
| ![spaCy](https://img.shields.io/badge/spaCy-NLP-09A3D5?logo=python&logoColor=white) | Procesamiento lingüístico y pipelines de PLN |
| ![Gensim](https://img.shields.io/badge/Gensim-Word2Vec%20FastText-blue?logo=python&logoColor=white) | Embeddings de palabras |
| ![SentenceTransformers](https://img.shields.io/badge/Sentence--Transformers-Embeddings-9B59B6?logo=huggingface&logoColor=white) | Embeddings de oraciones |
| ![scikit-learn](https://img.shields.io/badge/scikit--learn-Pipeline-F7931E?logo=scikit-learn&logoColor=white) | Clasificación, métricas, TF-IDF |
| ![PyTorch](https://img.shields.io/badge/PyTorch-2.x-EE4C2C?logo=pytorch&logoColor=white) | Redes neuronales (MLP) |
| ![TensorFlow](https://img.shields.io/badge/TensorFlow-2.15-FF6F00?logo=tensorflow&logoColor=white) | Redes recurrentes (LSTM) |
| ![Keras](https://img.shields.io/badge/Keras-Sequential-D00000?logo=keras&logoColor=white) | API de alto nivel para LSTM |
| ![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-yellow?logo=huggingface&logoColor=white) | Modelos pre-entrenados (BETO, RoBERTuito, Whisper) |
| ![Gradio](https://img.shields.io/badge/Gradio-Interface-purple?logo=gradio&logoColor=white) | Interfaces interactivas |
| ![Playwright](https://img.shields.io/badge/Playwright-Scraping-45ba4b?logo=playwright&logoColor=white) | Scraping web dinámico |
| ![Scrapling](https://img.shields.io/badge/Scrapling-Web%20Scraping-red?logo=python&logoColor=white) | Extracción de datos web |
| ![Pandas](https://img.shields.io/badge/Pandas-DataFrame-150458?logo=pandas&logoColor=white) | Manipulación de datos |
| ![NumPy](https://img.shields.io/badge/NumPy-Arrays-013243?logo=numpy&logoColor=white) | Operaciones numéricas |
| ![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualización-11557c?logo=python&logoColor=white) | Visualización de datos |

---

## Estructura del repositorio

```
dominguez-micaela-belen-pln-1c-2026/
│
├── 001/                          # Módulo 01 — Python para PLN
│   ├── 001-TEO/
│   ├── 002-PRA/
│   │   ├── 001_Python_para_PLN.ipynb
│   │   ├── 002_Python_para_PLN.ipynb
│   │   └── 003_Guia_Ejercicio_Integrador.ipynb
│   └── 003-LAB/
│
├── 002/                          # Módulo 02 — Scraping y Adquisición de Datos
│   ├── 001-TEO/
│   ├── 002-PRA/
│   │   ├── 000_Intro_Gradio_BeautifulSoup.ipynb
│   │   ├── 001_Requests_NLP_Basico.ipynb
│   │   ├── 002_DOM_CSS_Headers.ipynb
│   │   ├── 003_Trafilatura_Pandas_CSV.ipynb
│   │   ├── 004_Playwright_Scraping_Dinamico.ipynb
│   │   ├── 005_GatesNotes_Scrapling.ipynb
│   │   ├── 006_Visualizacion_Datos.ipynb
│   │   ├── 007_Audio_Transcripcion_Whisper.ipynb
│   │   ├── 008_App_Transcripcion_Gradio.ipynb
│   │   ├── 009_Audio_Transription_App_Colab.ipynb
│   │   ├── 009_Proyecto_Final_Agenda_Medios.ipynb
│   │   └── fetch_gatesnotes_pw.py
│   └── 003-LAB/
│
├── 003/                          # Módulo 03 — spaCy y Fundamentos de PLN
│   ├── 001-TEO/
│   ├── 002-PRA/
│   │   ├── 000_intro_pln_y_spacy.ipynb
│   │   ├── 001_spacy_fundamentos.ipynb
│   │   ├── 002_spacy_pipeline_y_apoyo.ipynb
│   │   ├── 003_prelaboratorio_spacy_en_accion.ipynb
│   │   ├── 004_spacy_desafios_rioplatense.ipynb
│   │   ├── 005_laboratorio_integrador_noticias.ipynb
│   │   └── 006_preprocesamiento_y_representacion_texto.ipynb
│   └── 003-LAB/
│
├── 004/                          # Módulo 04 — TPI 1: Adquisición y Análisis Lingüístico
│   ├── 001-TEO/
│   ├── 002-PRA/
│   └── 003-LAB/
│       └── TPI_1_Adquisicion_y_Analisis_Linguistico.ipynb
│
├── 005/                          # Módulo 05 — Representación de Texto: BoW y TF-IDF
│   ├── 001-TEO/
│   ├── 002-PRA/
│   │   ├── 001_bag_of_words.ipynb
│   │   └── 002_tfidf_y_ngramas.ipynb
│   └── 003-LAB/
│
├── 006/                          # Módulo 06 — Laboratorio Integrador spaCy + TF-IDF
│   ├── 001-TEO/
│   ├── 002-PRA/
│   │   └── 002_laboratorio_integrador_spacy_tfidf.ipynb
│   └── 003-LAB/
│
├── 007/                          # Módulo 07 — TPI 2: Text Mining y Análisis Discursivo
│   ├── 001-TEO/
│   ├── 002-PRA/
│   └── 003-LAB/
│       ├── corpus_tpi2.csv
│       └── TPI_2_Text_Mining_y_Analisis_Discursivo_Comparado.ipynb
│
├── 008/                          # Módulo 08 — De Text Mining a Representaciones Semánticas
│   ├── 001-TEO/
│   ├── 002-PRA/
│   │   └── De_Text_Mining_a_Representaciones_Semantica.ipynb
│   └── 003-LAB/
│
├── 009/                          # Módulo 09 — TP3: Recuperatorio Grupal Final
│   ├── 001-TEO/
│   ├── 002-PRA/
│   └── 003-LAB/
│       ├── corpus_tp3.csv
│       └── TP3_Recuperatorio_Grupal_Final.ipynb
│
├── 010/                          # Módulo 10 — Representaciones Semánticas
│   ├── 001-TEO/
│   ├── 002-PRA/
│   │   ├── vectors/
│   │   ├── 01_word2vec_embeddings.ipynb
│   │   ├── 02_fasttext_glove.ipynb
│   │   ├── 03_sentence_embeddings_intro.ipynb
│   │   ├── 04_visualizacion_embeddings.ipynb
│   │   ├── 05_sintesis_representaciones.ipynb
│   │   ├── 06_ejercicios_similitud.ipynb
│   │   └── 07_anexo_clasificacion_texto.ipynb
│   └── 003-LAB/
│
├── 011/                          # Módulo 11 — Clasificación y Redes Neuronales
│   ├── 001-TEO/
│   ├── 002-PRA/
│   │   ├── 01_clasificacion_sklearn_tfidf.ipynb
│   │   ├── 02_naive_bayes_pipelines.ipynb
│   │   ├── 03_perceptron_desde_cero.ipynb
│   │   ├── 04_perceptron_multicapa_pytorch.ipynb
│   │   ├── 05_redes_recurrentes_lstm_keras.ipynb
│   │   └── 06_embeddings_semanticos_similitud.ipynb
│   └── 003-LAB/
│
├── 012/                          # Módulo 12 — Transformers y HuggingFace
│   ├── 001-TEO/
│   ├── 002-PRA/
│   │   ├── 01_transformers_preentrenados.ipynb
│   │   ├── 02_introduccion_gradio.ipynb
│   │   ├── 03_ejercicios_transformers.ipynb
│   │   └── 04_laboratorio_desarrollo_habla.ipynb
│   └── 003-LAB/
│
├── 013/                          # Módulo 13 — Modelos de Lenguaje
│   ├── 001-TEO/
│   ├── 002-PRA/
│   │   ├── 01_introduccion_modelos_lenguaje.ipynb
│   │   ├── 02_tokens_y_embeddings.ipynb
│   │   └── 04_aplicaciones_transformers.ipynb
│   └── 003-LAB/
│
├── 014/                          # Módulo 14 — LLMs y RAG
│   ├── 001-TEO/
│   ├── 002-PRA/
│   │   ├── 04_actualizacion_informacion_llms.ipynb
│   │   ├── 05_ollama_llms_locales.ipynb
│   │   ├── 06_modelos_locales_pydantic_humanidades.ipynb
│   │   ├── 07_carga_documentos_rag.ipynb
│   │   ├── 08_bases_datos_vectoriales_chromadb.ipynb
│   │   └── 09_sistema_rag_completo_gemini.ipynb
│   └── 003-LAB/
│
├── README.md
└── requirements.txt
```

---

## Contenido por módulo

### Módulo 01 — Python para PLN
Introducción a Python orientada al procesamiento del lenguaje natural. Estructuras de datos, manejo de texto y ejercicio integrador.

### Módulo 02 — Scraping y Adquisición de Datos
Técnicas de extracción de información web con Requests, BeautifulSoup, Playwright y Scrapling. Transcripción de audio con Whisper. Interfaces con Gradio. Proyecto final: agenda de medios.

### Módulo 03 — spaCy y Fundamentos de PLN
Pipelines de PLN con spaCy: tokenización, lematización, POS tagging, NER. Desafíos con español rioplatense. Laboratorio integrador con noticias.

### Módulo 04 — TPI 1: Adquisición y Análisis Lingüístico
Trabajo práctico integrador sobre adquisición de corpus y análisis lingüístico.

### Módulo 05 — Representación de Texto: BoW y TF-IDF
Bag of Words y TF-IDF con N-gramas. Vectorización de texto para tareas de clasificación.

### Módulo 06 — Laboratorio Integrador spaCy + TF-IDF
Integración de técnicas de spaCy con representaciones TF-IDF aplicadas a corpus reales.

### Módulo 07 — TPI 2: Text Mining y Análisis Discursivo
Trabajo práctico integrador sobre text mining y análisis discursivo comparado.

### Módulo 08 — De Text Mining a Representaciones Semánticas
Transición conceptual y práctica desde técnicas clásicas de text mining hacia representaciones semánticas densas.

### Módulo 09 — TP3: Recuperatorio Grupal Final
Trabajo práctico grupal integrador.

### Módulo 10 — Representaciones Semánticas
Word Embeddings con Word2Vec (SBWC), GloVe y FastText (OOV con n-gramas). Sentence Embeddings con Sentence-Transformers. Visualización con PCA y t-SNE. Síntesis comparativa de representaciones.

### Módulo 11 — Clasificación y Redes Neuronales
Clasificación de texto con TF-IDF y scikit-learn. Naive Bayes y Pipelines. Perceptrón desde cero. Red Neuronal Multicapa con PyTorch. Redes Recurrentes LSTM con Keras/TensorFlow. Búsqueda semántica con embeddings.

### Módulo 12 — Transformers y HuggingFace
Transfer Learning en NLP. Modelos pre-entrenados en español: BETO, RoBERTuito. Pipelines de HuggingFace (sentiment, NER, QA). Gradio para interfaces. Laboratorio de procesamiento del habla.

### Módulo 13 — Modelos de Lenguaje
Introducción a modelos de lenguaje, tokenización avanzada y aplicaciones con Transformers.

### Módulo 14 — LLMs y RAG
LLMs locales con Ollama. Modelos locales con Pydantic. Carga de documentos para RAG. Bases de datos vectoriales con ChromaDB. Sistema RAG completo con Gemini.

---

## Cómo ejecutar

1. Clonar el repositorio:
```bash
git clone https://github.com/dominguez-micaela-belen/dominguez-micaela-belen-pln-1c-2026.git
```

2. Crear y activar el entorno virtual:

**Windows**
```bash
python -m venv .venv
.venv\Scripts\Activate.ps1
```

**Linux / macOS**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

3. Instalar dependencias:
```bash
pip install -r requirements.txt
```

4. Abrir los notebooks con Jupyter o VS Code.

> **Nota:** Los modelos pre-entrenados (Word2Vec, FastText) deben descargarse por separado y colocarse en la carpeta `vectors/` del módulo correspondiente. No están versionados en este repositorio por su tamaño.

---

## Autora

**Micaela Belén Dominguez**

## Créditos

Materia y material a cargo del profesor **Matías Barreto** — Tecnicatura Superior en Ciencias de Datos e IA
