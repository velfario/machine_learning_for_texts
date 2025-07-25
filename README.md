Hola, en este repo vemos un ejemplo de machine learning aplicado a textos, clasificando en positivas y negativas reseñas de películas. En este jupyter notebook podemos encontrar un breve análisis de los datos, así como:

- modelo NLTK, TF-IDF, LR: Es un modelo que utiliza el vectorizado TF-IDF (Term frequency – Inverse document frequency) que les da importancia a las palabras dependiendo la frecuencia con la que se presenta en la reseña y en el conjunto de textos en entrenamiento (corpus).
- modelo spaCy, TF-IDF, LR: Es un modelo que primero "Lematiza" las palabras antes de utilizar el vectorizado TF-IDF.
- modelo BERT: Utilizamos el modelo BERT (Bidirectional Encoder Representations from Transformers) de Google, un modelo de procesamiento en lenguaje natural que hace una vectorización de palabras dependiendo su contexto (embeddings). Este tipo de vectorización es de las más actuales aplicado a textos utilizada por Gemini, ChatGPT entre otras.

En la actualidad el procesamiento de textos con IA es de las herramientas más utilizadas en la industria por ser una novedad y presentar una variedad de aplicaciones cuando se une a la IA generativa.
