# DL-Deteccion-Credict-Card-Fraud-Autoencoder

En este repositorio, encontrarás un archivo de Jupyter Notebook que detalla los métodos, procesos y argumentos utilizados para obtener respuestas y resultados, facilitando la toma de decisiones fundamentada en la metodología de un proyecto de ciencia de datos.

### Conceptos introductorios:
* Jupyter Notebook
* Metodología de Ciencia de Datos
* Dataset

Dataset: 

El conjunto de datos fue obtenido de un compartido en Kaggle, donde se encontró en el repositorio de Kaggle. Contiene transacciones realizadas por titulares de tarjetas europeos con tarjetas de crédito en septiembre de 2013. Este conjunto revela transacciones de dos días, con un total de 284,807 transacciones, entre las cuales se identificaron 492 fraudes. La proporción de fraudes respecto al total de transacciones es mínima, representando solo el 0.172%. Por motivos de confidencialidad, los datos han sido sometidos a una transformación por PCA. Las variables V1 a V28 representan los componentes principales obtenidos mediante PCA, siendo 'Tiempo' y 'Cantidad' las únicas características que no han sido alteradas. Para obtener más detalles, se puede consultar el repositorio en el siguiente enlace: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Autoencoder:

Un autoencoder es un tipo de red neuronal artificial utilizada para el aprendizaje no supervisado de representaciones de datos. Consiste en dos partes principales: un codificador y un decodificador.
Durante el entrenamiento, un autoencoder intenta minimizar la diferencia entre los datos de entrada y la salida reconstruida. Esto obliga a la red a aprender una representación útil de los datos, ya que necesita capturar la información esencial para poder reconstruirlos con precisión.

![image](https://github.com/JessicaChepe/DL-Deteccion-Credict-Card-Fraud-Autoencoder/assets/104339906/00b15f53-f539-4cc8-89cc-82d2827adb17)

Imagen(freepik)

✅ Subido en Kagle:
👉 https://www.kaggle.com/code/jessicachepe/credict-card-fraud-autoencoder
