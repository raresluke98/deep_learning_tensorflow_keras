# Deep learning tensorflow keras

## Summary:
I have made a deep learning network that classifies images from the MNIST dataset.

## Libraries:
* tensorflow - library used for creating Deep Learning models by Google
* keras - open-source library that provides an interface for artificial neural networks (acts as an interface for the TensorFlow library)
 
## Functions:

## Result:
I have managed to predict the classes of the MNIST dataset with an accuracy of .97 using a deep learning network with two hidden layers

## Notes:
* We load the mnist dataset (28 x 28 images)
* We normalize the X data
* We initialize a flate layer as input
* We add two hidden layers made of 128 units(neurons) each.
* We add 10 units in the output layer (equal to the number of classes)


## TODO:
* what is tf.keras.layers.Dense ??
* what is softmax activation func?
* what is adam optimizer?
* what is the crossentropy loss function?
