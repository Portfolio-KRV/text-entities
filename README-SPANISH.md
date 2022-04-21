# Text-entities
Desarrollado en el curso de Redes Neuronales por: Diego Quezada y Kevin Reyes.  
## Objetivos
- Reconocer entidades en texto utilizando redes neuronales recurrentes.
- Verificar si la **ley Zipf** se cumple en el conjunto de datos.
- Representar las palabras en un espacio vectorial que establezca relaciones coherentes entre el significado y contexto de las palabras (embedding).
- Predecir el carácter siguiente en una secuencia de texto.

## Descripción
Aplicación de redes neuronales recurrentes para las tareas de procesamiento del lenguaje natural de predicción entidades en textos representados con embeddings y predicción del carácter siguiente en una sentencia de texto..

## Conclusiones
- Se corrobora que efectivamente se cumple la ley Zipf sobre el conjunto de datos.
- Es importante escoger la dimensionalidad del embedding en base a la complejidad de las relaciones existentes en el diccionario de palabras, ya que utilizar una dimensionalidad muy alta podría introducir complejidad innecesaria al modelo, aumentar tiempos de entrenamiento y provocar overfitting.
- El uso de redes neuronales recurrentes bidireccionales no mejoró el desempeño de la red en el reconocimiento de entidades.

## Stack de tecnologías
- Keras.
- Tensorflow.
- Matplotlib.
- Numpy.
- Pandas.
- Scikit-learn.
