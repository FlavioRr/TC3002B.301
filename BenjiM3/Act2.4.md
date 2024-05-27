# ACTIVIDAD 2.4

## Paper de Investigación para Métricas:

"A Survey on Performance Metrics for Face Recognition" por Zhao et al. (2017): Este paper ofrece una revisión completa de las métricas de rendimiento para el reconocimiento facial, incluyendo la clasificación de género.
https://ieeexplore.ieee.org/document/8109069


### Selección de Métricas Adecuadas para Clasificación de Género Facial
1. Métricas de Precisión:
Precisión: Porcentaje de imágenes correctamente clasificadas (hombre o mujer). Es una métrica general que resume el rendimiento del modelo en ambas clases (hombre y mujer). Se calcula como: Precisión = (Verdaderos Positivos + Verdaderos Negativos) / (Total de Imágenes).

2. Métricas de Recuerdo (Recall) y Especificidad:
Recuerdo (Recall): Porcentaje de imágenes de hombres correctamente clasificadas como hombres. Se calcula como: Recall = (Verdaderos Positivos) / (Total de Hombres).
Especificidad: Porcentaje de imágenes de mujeres correctamente clasificadas como mujeres. Se calcula como: Especificidad = (Verdaderos Negativos) / (Total de Mujeres).

3. Curva ROC (Receiver Operating Characteristic):
La curva ROC grafica la tasa de falsos positivos (FPR) en función de la tasa de verdaderos positivos (TPR). Es útil para visualizar el rendimiento del modelo en diferentes umbrales de decisión.\

4. Métricas de Precisión-Recuerdo (Precision-Recall):
La curva de precisión-recuerdo grafica la precisión en función del recuerdo. Es útil para comparar el rendimiento del modelo en diferentes puntos de equilibrio entre precisión y recuerdo.

