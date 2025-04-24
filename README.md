# Weather Prediction with LSTM

Este proyecto utiliza redes neuronales recurrentes (LSTM) para predecir las condiciones meteorológicas (temperatura, humedad, precipitación, y velocidad del viento) basándose en un conjunto de datos de condiciones meteorológicas históricas. El modelo está entrenado usando un conjunto de datos de Kaggle sobre el clima.

## Descripción del Proyecto

En este proyecto, desarrollamos un modelo de LSTM para predecir el clima. La tarea principal es utilizar datos históricos de temperatura, humedad, precipitación y velocidad del viento para predecir los mismos parámetros en un futuro cercano. Los datos provienen de la base de datos de Kaggle: Weather Data.

## Objetivos del Proyecto
Desarrollar un modelo de predicción de clima utilizando una red neuronal LSTM.
Evaluar la capacidad del modelo para predecir con precisión las variables meteorológicas.
Documentar y explicar cada paso del proceso de modelado y evaluación.

## Requisitos

Python 3.x
Bibliotecas: TensorFlow, Keras, Pandas, NumPy, Matplotlib, etc.
Para instalar las dependencias necesarias, puedes usar pip o conda. A continuación se muestra el comando de instalación con pip:

pip install -r requirements.txt

### ¿Cómo obtener los datos?
El conjunto de datos puede ser descargado desde este enlace de Kaggle.

## Conclusiones

El modelo LSTM ha sido capaz de hacer predicciones de las condiciones meteorológicas con una precisión razonable.
Aunque el modelo tiene espacio para mejorar, se puede ajustar mediante técnicas como el uso de más datos, optimización de hiperparámetros y ajustes en la arquitectura.

## Limitaciones

El modelo no tiene un rendimiento perfecto y las predicciones aún muestran ciertos errores.
La calidad de las predicciones puede mejorar al agregar más variables y usar más datos históricos.
El modelo no tiene en cuenta otros factores externos como fenómenos meteorológicos no medidos en el conjunto de datos.
