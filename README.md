# Text-entities
Developed in the Neural Networks course by: Diego Quezada and Kevin Reyes.  
## Objectives
- Recognize entities in text using recurrent neural networks.
- Verify if the **Zipf law** is fulfilled in the data set.
- Represent the words in a vector space that establishes coherent relationships between the meaning and context of the words (embedding).
- Predict the next character in a text sequence.

## Description
Application of recurrent neural networks for the natural language processing tasks of predicting entities in texts represented with embeddings and predicting the next character in a text sentence.

## Conclusions
- It is corroborated that the Zipf law on the data set is indeed complied with.
- It is important to choose the dimensionality of the embedding based on the complexity of the existing relationships in the word dictionary, since using a very high dimensionality could introduce unnecessary complexity to the model, increase training times and cause overfitting.
- The use of bidirectional recurrent neural networks did not improve the performance of the network in entity recognition.

## Technology stack
- Keras.
- Tensorflow.
- Matplotlib.
- Numpy.
- Pandas.
- Scikit-learn.