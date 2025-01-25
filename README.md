# Analisis y Procesamiento de Datos para Recuperacion de Informacion con Python

## 📂 Contenidos
1. [Introduccion](#introduccion)
2. [Apartado 4: Iniciacion y Procesamiento de Datos](#apartado-4-iniciacion-y-procesamiento-de-datos)
   - [Descripcion](#descripcion)
   - [Herramientas Utilizadas](#herramientas-utilizadas)
   - [Carga y Exploracion de Datos](#carga-y-exploracion-de-datos)
3. [Apartado 5: TF-IDF](#apartado-5-tf-idf)
   - [Conceptos Clave](#conceptos-clave)
   - [Implementacion](#implementacion)
4. [Apartado 6: Uso de Embeddings en un Sistema de Recuperacion de Informacion](#apartado-6-uso-de-embeddings-en-un-sistema-de-recuperacion-de-informacion)
   - [Introduccion a Gemini](#introduccion-a-gemini)
   - [Generacion de Embeddings](#generacion-de-embeddings)
   - [Pruebas y Consultas](#pruebas-y-consultas)

---

## 📖 Introduccion
Este repositorio contiene ejercicios de analisis de datos con Python, utilizando diversas bibliotecas para manipulacion y visualizacion de datos, como `pandas`, `matplotlib` y `seaborn`.

---

## 🏆 Apartado 4: Iniciacion y Procesamiento de Datos

### Descripcion
En este ejercicio se trabaja con un conjunto de datos en formato CSV que contiene tweets. El objetivo es limpiar, analizar y procesar los datos para su posterior analisis.

### Herramientas Utilizadas
- **`pandas`** para manipulacion de datos.
- **`numpy`** para operaciones matematicas.
- **`NLTK`** para procesamiento de lenguaje natural.
- **`matplotlib` y `seaborn`** para visualizacion de datos.

### Carga y Exploracion de Datos
- Lectura del archivo CSV proporcionado.
- Exploracion de las principales caracteristicas de los datos.
- Procesamiento del texto mediante tecnicas de tokenizacion y limpieza.

---

## 🏡 Apartado 5: TF-IDF

### Conceptos Clave
TF-IDF (Term Frequency - Inverse Document Frequency) es una tecnica utilizada para evaluar la importancia de una palabra en un conjunto de documentos. En este ejercicio, se analiza una fuente de datos ya procesada.

### Implementacion
- Carga de los datos desde `tfidf.csv`.
- Aplicacion de la tecnica de TF-IDF para evaluar la relevancia de los terminos.
- Visualizacion de los terminos mas importantes utilizando graficos.

---

## 🗃️ Apartado 6: Uso de Embeddings en un Sistema de Recuperacion de Informacion

### Introduccion a Gemini
Se introduce el modelo de IA **Gemini de Google**, el cual permite la generacion de embeddings (representaciones numericas de texto). Estos embeddings permiten la busqueda y recuperacion de informacion de manera mas eficiente.

### Generacion de Embeddings
- Uso de la API de Gemini para obtener embeddings de textos.
- Transformacion del texto en arrays numericos para su analisis.

### Pruebas y Consultas
- Ejecucion de consultas sobre los datos utilizando embeddings generados.
- Propuesta de nuevos ejemplos de consulta para probar la efectividad del modelo.

---

### 🔧 Tecnologias utilizadas
- Python
- Pandas
- Matplotlib
- Seaborn


