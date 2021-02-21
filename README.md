# Deep learning tensorflow keras

## Summary:
I have made a deep learning network that classifies images from the MNIST dataset.

## Libraries:
* tensorflow - library used for creating Deep Learning models by Google
* keras - open-source library that provides an interface for artificial neural networks (acts as an interface for the TensorFlow library)

## Result:
I have managed to predict the classes of the MNIST dataset with an accuracy of .97 using a deep learning network with two hidden layers

## Notes:
* We load the mnist dataset (28 x 28 images)
* We normalize the X data
* We initialize a flate layer as input
* We add two hidden layers made of 128 units(neurons) each.
* We use the tf.keras.layers.dense function for the previous point because we want every unit to be connected to every unit in the next layer
* We add 10 units in the output layer (equal to the number of classes)
* We use the softmax activation function for the output
* The softmax function "squishes" the inputs, so sum(input) = 1; it's a way of normalizing.
* We compile the model using the adam optimizer, sparse crossentropy loss function and the accuracy metric
* The adam optimizer is a stochastic gradient descent method (it reduces the computational burden in high-dimensional optimization problems)
* The cross-entropy error function leads to faster training as well as improved generalization

## TODO:
* ~~what is tf.keras.layers.Dense ??~~
* ~~what is softmax activation func?~~
* ~~what is adam optimizer?~~
* ~~what is the crossentropy loss function?~~
