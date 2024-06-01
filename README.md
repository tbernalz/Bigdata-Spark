# ST0263 - Tópicos Especiales en Telemática, 2024-1

* Estudiante: Tomás Bernal Zuluaga - tbernalz@eafit.edu.co
* Profesor: Edwin Montoya - emontoya@eafit.edu.co

# Proyecto 3 - Spark con Notebooks y PySpark

En este proyecto se explorarán y analizarán los datos de casos positivos de COVID-19 en Colombia utilizando PySpark y Jupyter Notebooks. El objetivo es realizar un análisis exploratorio de los datos, responder preguntas de negocio específicas y almacenar los datos procesados tanto en AWS S3 como en Google Drive. El proyecto se desarrollará en dos plataformas: AWS-EMR-JupyterHub y Google Colab.


### Archivo .ipynb
El archivo Jupyter Notebook con el desarrollo completo de estos pasos está disponible en este repositorio.


## 1. Almacenar datos en AWS S3 y en google drive

### Configurar Credenciales de AWS
* Montar Google Drive

* Instalar Java y Spark en Google Colab

* Configuración del entorno de Java y Spark

### Crear una Sesión de Spark con Configuraciones Adicionales
* Configurar credenciales de AWS

* Inicialización de findspark con las configuraciones establecidas anteriormente

* Crear una sesión de Spark con configuraciones adicionales para AWS S3

### Verificar la conexión con Spark con:

* SparkSession.builder

* sparkContext

### Cargar dataset desde Google Drive hacia Spark

* Se debe tener el dataset almacenado en drive

### Cargar dataset desde AWS S3 hacia Spark

* Se debe tener el dataset almacenado en drive


## 2. Análisis Exploratorio de Datos

* 2.1 Mostrar las columnas

* 2.2 Mostrar los tipos de datos

* 2.3 seleccionar algunas columnas

* 2.4 Renombrar Columnas (esto se recomienda hacerlo para facilitar el procesamiento posterior)

* 2.5 Agregar columnas

* 2.6 Borrar columnas

* 2.7 Filtrar datos

* 2.8 Ejecutar una función UDF sobre alguna columna (Edad) creando una nueva (Edad_grupo)


## 3. Preguntas de Negocio

* 3.1 Departamentos con Más Casos de Covid en Colombia ordenados de mayor a menor

* 3.2 Las 10 ciudades con más casos de covid en Colombia ordenados de mayor a menor

* 3.3 Los 10 días con más casos de covid en Colombia ordenados de mayor a menor

* 3.4 Distribución de casos por edades de covid en Colombia

* 3.5 Pregunda de negocio: ¿Cuál es el promedio de edad de los casos recuperados?


## 4. Almacenamiento de Resultados en un Bucke público de AWS S3

* departamentos_mas_casos: 

* ciudades_mas_casos: 

* dias_mas_casos: 

* distribucion_edad: 

* promedio_edad_activos: 


## Conclusión

En este proyecto se realizó un análisis detallado de los datos de COVID-19 en Colombia utilizando PySpark. Se almacenaron los datos en AWS S3 y Google Drive, se llevó a cabo un análisis exploratorio de datos y se respondieron preguntas de negocio utilizando tanto la API de DataFrame de Spark como SparkSQL. Finalmente, los resultados se almacenaron en AWS S3 para su posterior análisis y consulta.