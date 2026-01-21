# RAG (Retrieval-Augmented Generation)

Este repositorio contiene un ejercicio práctico para la creación de un modelo RAG (Retrieval-Augmented Generation). Este enfoque combina técnicas de recuperación de información y generación de texto para proporcionar respuestas más precisas y contextualmente relevantes.

## Descripción del Proyecto

El modelo RAG implementado en este proyecto utiliza una base de datos Chroma para almacenar y recuperar información relevante. Posteriormente, un generador de texto procesa esta información para generar respuestas enriquecidas. Este enfoque es ideal para aplicaciones como chatbots, asistentes virtuales y sistemas de preguntas y respuestas.

## Estructura del Repositorio

- `clase rag.ipynb`: Notebook principal que contiene el código y las explicaciones del modelo.
- `chroma_db/`: Carpeta que almacena la base de datos Chroma utilizada para la recuperación de información.
  - `chroma.sqlite3`: Archivo principal de la base de datos.
  - Subcarpeta con archivos binarios que contienen datos adicionales para la base de datos.

## Requisitos Previos

- Python 3.8 o superior
- Dependencias especificadas en el notebook (asegúrate de instalar las bibliotecas necesarias antes de ejecutar el código).

## Uso

1. Abre el archivo `clase rag.ipynb` en un entorno compatible con Jupyter Notebook.
2. Sigue las instrucciones en el notebook para cargar la base de datos y ejecutar el modelo.
3. Personaliza el modelo según tus necesidades específicas.


