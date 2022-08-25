# Información de usuario 21-22_caluva 
* Autor : Carlos Luzzatti Vázquez
* Descripción y tema:
  * Tema del tabajo: IA/Machine Learning aplicada a ciberseguridad
  * Descripción: Comparativa el rendimiento con varias Machine learning para la clasificación de spam no spam usando varios tipos de ML y luego comparar la exactitud que nos devuelve 
  * Objetivos: Con un mismo set de datos obtener el rendimiento de los principales ML basados en modelos predefinidos en forma gráfica y obtener el mas conveniente para los siguientes experimentos, despues comparar la exactitud del modelo seleccionado en contra de un modelo basado en redes neuronales
* Prerrequisitos 
  * Software necesario para el entorno
     * Para ejecutar en local descargar Anaconda en https://www.anaconda.com/products/individual
     * Dentro de la aplicación Anaconda utilizar jupyter notebook
     * Se puede ejecutar con la instrucción jupyter lab
  * Librerias necesarias para ejecutarlo
     * Instalar Keras y tensorflow, desde anaconda prompt ejecutar la instrucción conda install -c conda-forge tensorflow.
     * Instalar Keras instrucción pip install keras.
     * Instalar pandas instrucción pip install pandas.
     * Instalar numpy instrucción pip install numpy.
     * Instalar nltk instrucción pip install nltk.
     * Instalar matplotlib instrucción pip install matplotlib.
     * Instalar seaborn instrucción pip install seaborn.
     * Actualizar librerias scikit-learn conda update scikit-learn.
     * Al ejecutar el programa por primera vez ejecutar linea #nltk.download('punkt')
     * nltk.download('stopwords')
  * Lenguaje de programación
     * Descargar python https://www.python.org/downloads/windows/ 
     * Python 3.8.8
  * Versiones
     * Jupyter Notebook Version 6.4.3   
     * jupyterlab Version 3.1.7
     * anaconda-navigator Version 2.0.3
     * anaconda-project Version 0.10.0
     * anaconda-client  Version 1.8.0
     * Keras Version 2.4.3
     * matplotlib Version 3.3.4
     * nltk Version 3.6.2
     * numpy Version 1.20.2
     * scikit-learn Version 1.1.2
     * seaborn Version 0.11.1
     * tensorflow Version 2.3.0
     * tensorflow-estimator Version 2.5.0
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
* Modelos entrenados
  * RidgeClassifier Tiempo de entrenamiento 0.29766130447387695 Exactitud 0.8164251207729468
  * Perceptron Tiempo de entrenamiento 0.007395267486572266 Exactitud 0.9739130434782609
  * PassiveAggressiveClassifier Tiempo de entrenamiento 0.013032913208007812 Exactitud 0.9681159420289855
  * KNeighborsClassifier Tiempo de entrenamiento 0.0038254261016845703 Exactitud 0.7971014492753623
  * RandomForestClassifier Tiempo de entrenamiento 11.59603476524353 Exactitud 0.978743961352657 
  * LinearSVC(dual=False, tol=0.001) Tiempo de entrenamiento 0.05614876747131348 Exactitud 0.970048309178744
  * SGDClassifier(max_iter=50) Tiempo de entrenamiento 0.010421037673950195 Exactitud 0.9748792270531401
  * LinearSVC(dual=False, penalty='l1', tol=0.001) Tiempo de entrenamiento 0.11305356025695801 Exactitud 0.966183574879227
  * SGDClassifier(max_iter=50, penalty='l1') Tiempo de entrenamiento 0.11262297630310059 Exactitud 0.9487922705314009  
  * SGDClassifier(max_iter=50, penalty='elasticnet') Tiempo de entrenamiento 0.03076457977294922 Exactitud 0.9681159420289855
  * NearestCentroid Tiempo de entrenamiento 0.005759000778198242 Exactitud 0.5159420289855072
  * MultinomialNB Tiempo de entrenamiento 0.008762359619140625 Exactitud 0.9816425120772947
  * BernoulliNB Tiempo de entrenamiento 0.009632110595703125 Exactitud 0.9246376811594202
  * ComplementNB Tiempo de entrenamiento 0.009243011474609375 Exactitud 0.978743961352657
* Uso básico
  * Analizara documento de texto para usar aprendizaje automatico para clasificar el texto del correo en spam y no spam
  * Mostrara una grafica con varios modelos predefinidos indicando el tiempo y la exactitud del modelo y para obtener el rendimiento de varios modelos predefinidos
  * Modelo predefinido despues de valorar el rendimiento COMPLEMENTNB
  * Realizara la clasificicacion usando en un modelo predefinido y otro basado en redes neuronales  y realizara la comparativa de la exactitud de ambos modelos.     
* Fuentes referencia:
  * https://scikit-learn.org
  * https://docs.python.org/3/library/warnings.html
  * https://docs.python.org/3/library/optparse.html
  * https://pandas.pydata.org/docs/reference/api/pandas.read_csv.html
  * https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.drop.html
  * https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.head.html
  * https://seaborn.pydata.org/generated/seaborn.countplot.html
  * https://seaborn.pydata.org/generated/seaborn.set_theme.html
  * https://www.nltk.org/_modules/nltk/tokenize/regexp.html
  * https://pythonspot.com/nltk-stop-words/
  * https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html
  * https://scikit-learn.org/0.22/auto_examples/text/plot_document_classification_20newsgroups.html
  * https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.RandomizedSearchCV.html
  * https://scikit-learn.org/stable/modules/generated/sklearn.metrics.confusion_matrix.html
  * https://keras.io/guides/sequential_model/
  * https://keras.io/api/losses/
  * https://keras.io/guides/training_with_built_in_methods/


  
