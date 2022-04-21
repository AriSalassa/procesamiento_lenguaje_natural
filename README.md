# Procesamiento del Lenguaje natural :speech_balloon:
<img width="100%" src="https://user-images.githubusercontent.com/34188162/164556965-d5b9f540-c417-4f84-a71e-d9729af6317f.png"/>
Este repositorio contiene ejercicios y material teórico práctico correspondiente al curso de NLP de la carrera de especialización en inteligencia artificial de la Universidad de Buenos Aires.

## Challenges :computer:
### Challenge N°1: word2vec

Los primeros pasos en NLP. Usando los conceptos básicos de NLP, codificamos a de cero la conversión de oraciones a vectores usando, en primer lugar, un simple **OneHotEncoding**; luego **vectores de frecuencia**; y, finalmente, vectores **TFIDF**. Una vez que se obtuvo una representación vectorizada de las otraciones, los documentos del corpus se compararon usando **similitud de coseno** para analizar qué oraciones están "más cerca" de otras.

[Link to the notebook](https://github.com/AriSalassa/procesamiento_lenguaje_natural/blob/main/clase_1/ejercicios/1a%20-%20word2vec.ipynb)

### Challenge N°2: bot basado en reglas usando DNN + spaCy

En este desafío, se puso en práctica el **preprocesamiento** en NLP usando **tokenización**, **steeming** y **lematización** para construir un bot de chat de gestión de stock basado en reglas. Durante el curso, se usaron las bibliotecas **NLTK** y **SpaCY** para NLP pero se eligió SpaCy para este proyecto.

[Link to the notebook](https://github.com/AriSalassa/procesamiento_lenguaje_natural/blob/main/clase_2/ejercicios/ejercicio_clase_2.ipynb)

### Challenge N°3: custom embeddings usando Gensim

El ejercicio consiste en el **entrenamiento de custom embeddings** utilizando la biblioteca **Gensim** para analizar las letras de canciones escritas por diferentes artistas y su estilo de composición. Se analizó un artista en particular: Michael Jackson.

[Link to the notebook](https://github.com/AriSalassa/procesamiento_lenguaje_natural/blob/main/clase_3/ejercicios/ejercicio_clase_3_colab.ipynb)

### Challenge N°4: predicción de palabra usando RNN

Utilizando una **arquitectura many_to_one** para hacer **predicción de palabras** se puso en práctica el concepto de **Red Neuronal Recurrente (RNN)**. Para este ejercicios se usó un conjunto de datos kaggle de diálogos de varias películas de Marvel.

[Link to the notebook](https://github.com/AriSalassa/procesamiento_lenguaje_natural/blob/main/clase_4/ejercicios/ejercicio_clase_4.ipynb)

### Challenge N°5: clasificación de reseñas con LSTM

Utilizando la capa especializada de **Memoria a largo y corto plazo (LSTM)** y la biblioteca **FastText** que proporciona **embeddings pre entrenados**, se desarrolló un modelo para clasificar las reseñas de un comercio electrónico de ropa.

[Link to the notebook](https://github.com/AriSalassa/procesamiento_lenguaje_natural/blob/main/clase_5/ejercicios/5%20-%20clothing_ecommerce_reviews.ipynb)

### Challenge N°6: Q&A bot usando Seq2seq
En este desafío, se implementa un **bot conversacional** utilizando una arquitectura **codificador-decodificador seq2seq**. El usuario puede hablar de forma interactiva con el bot que responde de manera limitada por el entrenamiento ralizado. 

[Link to the notebook](https://github.com/AriSalassa/procesamiento_lenguaje_natural/blob/main/clase_6/ejercicios/6%20-%20bot_qa.ipynb)

## Contenido :books:

### [Clase 1](clase_1/README.md) 
* Introducción a NLP (natural language programing)
* Vectorización de documentos

### [Clase 2](clase_2/README.md)
* Preprocesamiento de texto
* Librerías de NLP
* Rule-based bots

### [Clase 3](clase_3/README.md)
* Word embeddings, CBOW y SkipGRAM
* Representación de oraciones

### [Clase 4](clase_4/README.md)
* Redes recurrentes (RNN)
* Problemas de secuencia
* Estimación de próxima palabra

### [Clase 5](clase_5/README.md)
* Redes LSTM
* Análisis de sentimientos (sentiment analysis)
    
### [Clase 6](clase_6/README.md)
* Modelos Seq2Seq
* Bots conversacionales y traductores

### [Clase 7](clase_7/README.md)
* Celdas con Attention
* Transformers
* BERT y ELMo
* Fine tuning

### [Clase 8](clase_8/README.md)
* Cierre del curso
* Deployment de servicio NLP
* Flask, APIs!
* Docker y Tensorflow Serving (TFX)

# Profesores
:octocat: Msc. Rodrigo Cardenas Szigety\
:octocat: Esp. Ing. Hernán Contigiani
