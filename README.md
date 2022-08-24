# Información de usuario 21-22_caluva 
* Autor : Carlos Luzzatti Vázquez
* Descripción y tema:
  * Tema del tabajo: IA/Machine Learning aplicada a ciberseguridad
  * Descripción: Comparativa con varias Machine learning para la clasificación de spam no spam usando varios tipos de ML y luego comparar la exactitud que nos devuelve 
  * Objetivos: Con un mismo set de datos obtener el rendimiento de los principales ML basados en modelos predefinidos en forma gráfica y obtener el mas conveniente para los siguientes experimentos, despues comparar la exactitud del modelo seleccionado en contra de un modelo basado en redes neuronales
* Prerrequisitos 
  * Software necesario para el entorno
     * Para ejecutar en local descargar Anaconda en https://www.anaconda.com/products/individual
     * Dentro de la aplicación Anaconda utilizar jupyter notebook
     * Se puede ejecutar con la instrucción jupyter lab
  * Librerias necesarias para ejecutarlo
     * Instalar Keras y tensorflow, desde anaconda prompt ejecutar la instrucción conda install -c conda-forge tensorflow
     * Instalar Keras instrucción pip install keras
     * Actualizar librerias scikit-learn conda update scikit-learn
     * Al ejecutar el programa por primera vez ejecutar linea #nltk.download('punkt')
     * nltk.download('stopwords')
  * Lenguaje de programación
     * Descargar python https://www.python.org/downloads/windows/
* Arquitectura 
  * Se ejecuta en localhost a traves del navegador 
  * Codigo en vivo , se puede ejecutar independientemente una celda 
  * Aprendizaje supervisado
  * Gráficas
* Estructura de los archivos del programa
  * Proyecto
      * Dataset
        * spam_ham_dataset
      * Clasificador_spam.ipynb
* Archivo necesarios para su ejecución
  * Necesitamos el archivo spam_ham_dataset incluido en la carpeta Dataset del proyecto
* Ejecución
  * Se puede ejecutar mientras por el terminal con la instrucción jupyter notebook, nos abrira el navegador y podremos seleccionar la ruta del proyecto, nos aparece un menu muy simple en el que debemos seleccionar run para ejecutarlo
* Uso básico
  * Analizara documento de texto para usar aprendizaje automatico para clasificar el texto del correo en spam y no spam
  * Mostrara una grafica con varios modelos predefinidos indicando el tiempo y la exactitud del modelo y para obtener el rendimiento de varios modelos predefinidos
  * Modelo predefinido despues de valorar el rendimiento COMPLEMENTNB
  * Realizara la clasificicacion usando en un modelo predefinido y otro basado en redes neuronales  y realizara la comparativa de la exactitud de ambos modelos.     
 
  
