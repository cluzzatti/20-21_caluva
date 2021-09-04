# Información de usuario 20-21_caluva 
* Autor : Carlos Luzzatti Vázquez
* Descripción y tema:
  * Tema del tabajo: IA/Machine Learning aplicada a ciberseguridad
  * Descripción: Machine learning para la clasificación de spam no spam
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
* Estructura de los archivos del programa
  * Proyecto
      * Dataset
        * spam_ham_dataset
      * Clasificador_spam.ipynb
* Archivo necesarios para su ejecución
  * Necesitamos el archivo spam_ham_dataset incluido en la carpeta Dataset del proyecto
* Ejecución
  * Se puede ejecutar mientras por el terminal con la instrucción jupyter notebook, nos abrira el navegador y podremos seleccionar la ruta del proyecto, nos aparece un menu muy    simple en el que debemos seleccionar run para ejecutarlo
* Uso básico
  * Analizara documento de texto para usar aprendizaje automatico para clasificar el texto del correo en espam y no spam  en un      
    modelo predefinido y otro basado en redes neuronales , mostrara una grafica con varios modelos predefinidos indicando el tiempo y la exactitud del modelo y se comparara la exactitud de ambos modelos, modelo predefinido     usado COMPLEMENTNB .
  
