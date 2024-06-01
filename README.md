# ST0263 - Tópicos Especiales en Telemática, 2024-1

* Estudiante: Tomás Bernal Zuluaga - tbernalz@eafit.edu.co
* Profesor: Edwin Montoya - emontoya@eafit.edu.co

# Proyecto 3 - Spark con Notebooks y PySpark

En este proyecto se explorarán y analizarán los datos de casos positivos de COVID-19 en Colombia utilizando PySpark y Jupyter Notebooks. El objetivo es realizar un análisis exploratorio de los datos, responder preguntas de negocio específicas y almacenar los datos procesados tanto en AWS S3 como en Google Drive. El proyecto se desarrollará en dos plataformas: AWS-EMR-JupyterHub y Google Colab.


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