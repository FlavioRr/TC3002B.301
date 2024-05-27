# ACTIVIDAD 2.1

Folder con el dataset a utilizar:
Google drive Folder Face Data: https://drive.google.com/drive/folders/16i_jtLB22ho3U3ZilennOaO6ANkXHKzx

Cuando se trabaja con un conjunto de datos de imágenes para entrenar un modelo de inteligencia artificial, es fundamental seguir prácticas y técnicas adecuadas para asegurar que el modelo pueda generalizar bien y ofrecer resultados precisos en datos no vistos previamente. A continuación, explico en detalle las decisiones tomadas en el contexto de un dataset dividido en fotos de caras de hombres y mujeres, que cuenta con 15,000 elementos, y que fue dividido utilizando el archivo divisionDataset.py:

### 1. División del Dataset en Train y Test (70-30)
Justificación:
Dividir el dataset en dos partes, una para entrenamiento (train) y otra para evaluación (test), es una práctica estándar en el desarrollo de modelos de aprendizaje automático. La razón principal para esta división es evaluar el rendimiento del modelo en datos no vistos durante el entrenamiento, asegurando así que el modelo pueda generalizar a nuevos datos.

70% para entrenamiento: Utilizar el 70% del dataset para el entrenamiento permite al modelo aprender patrones y características relevantes de las imágenes de caras tanto de hombres como de mujeres. En este caso, 10,500 imágenes se destinan al entrenamiento.

30% para evaluación: Reservar el 30% restante para la evaluación proporciona una cantidad significativa de datos (4,500 imágenes) para medir el rendimiento del modelo de manera precisa y confiable.

### (Update) se tomo el 10 % de test para validation. 

### 70% 20% 10%