# ACTIVIDAD 2.2

### Razón para No Realizar Data Augmentation
Explicación:
El data augmentation es una técnica que se utiliza para aumentar la diversidad del dataset mediante la creación de variaciones de las imágenes existentes, como rotaciones, escalados, y traslaciones. Sin embargo, en este caso particular, se decidió no utilizar data augmentation por las siguientes razones:

Calidad del Dataset: Si los datos ya son de alta calidad, bien balanceados y suficientemente variados, el data augmentation puede no ser necesario. Un dataset de 15,000 imágenes puede ser suficientemente robusto para entrenar un modelo sin necesidad de generar imágenes adicionales artificialmente.

Generalización: A veces, aplicar técnicas de data augmentation puede introducir ruido o artefactos no deseados en los datos, lo que podría afectar negativamente la capacidad del modelo para generalizar.

### No Mejorar el Sample de Datos
Explicación:
Mejorar el sample de datos implica técnicas como la recolección de más datos, la limpieza exhaustiva de los datos existentes, o la realización de curación adicional para eliminar cualquier sesgo. En este contexto, no se realizaron mejoras adicionales al sample de datos por las siguientes razones:

Suficiencia y Representatividad: El dataset es ya suficientemente grande (15,000 imágenes) y representativo de las variaciones necesarias para que el modelo aprenda de manera efectiva. Si el dataset es equilibrado y bien distribuido entre las diferentes clases (hombres y mujeres), puede ser suficiente para el propósito del entrenamiento.

Costo y Tiempo: La mejora adicional del sample de datos puede ser un proceso costoso y que consume mucho tiempo. Si el dataset existente cumple con los requisitos de calidad y diversidad, no es necesario invertir recursos adicionales en este aspecto.

### Conclusión
En resumen, la decisión de dividir el dataset en un 70% para entrenamiento y un 30% para evaluación es una práctica estándar para garantizar que el modelo pueda generalizar adecuadamente. La omisión de técnicas de data augmentation y mejoras adicionales al sample de datos se debe a la alta calidad y suficiencia del dataset original, lo que hace que dichas técnicas sean innecesarias en este caso específico. Estas decisiones permiten un entrenamiento eficiente y una evaluación precisa del modelo, optimizando tanto recursos como tiempo.