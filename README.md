# Workshop Convolutional Neural Networks

Source of cifar10 dataset: [https://www.cs.toronto.edu/~kriz/cifar.html](https://www.cs.toronto.edu/~kriz/cifar.html)

## Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AvisiLabs/workshop-cnn/blob/master/workshop-cnn.ipynb)


## Adjusting the model

Now that we've run through making and training a model we can adjust some of the parameters to try and get a better performance.
For this we'd like to give you a couple of suggestions to get you started:

- Adjusting the number of nodes in the layers (we recommend not touching the very last layer with 10 nodes).
- Adjusting the [activation function](https://www.tensorflow.org/api_docs/python/tf/keras/activations) of layers.
- Changing type of layers (e.g. change a MaxPooling2D layer to a AveragePooling2D layer.
- Adding or removing layers.
- Change the [optimizer](https://www.tensorflow.org/api_docs/python/tf/keras/optimizers#classes) used for the model.
- Change the [loss function](https://www.tensorflow.org/api_docs/python/tf/keras/losses#classes) used for the model.
- Adjust the number of epochs the mdoel trains for.

One last thing to note it that the model does a prediction over 10 categories, this means guessing rate is 1/10 or 10%. Keep this in mind when evaluating your models performance.
