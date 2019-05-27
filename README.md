# Implementing Autoencoder Deep Learning

I have used the popular MNIST dataset for this assignment. This dataset consists of 70000 28x28 greyscale images representing digits. The training and testing sets are fixed: there are 60000 training images and 10000 test images with corresponding labels.

The objective of this assignment is to remove noise from noisy images by passing them through an autoencoder.

- 784 x 32 x 784 autoencoder network. 784 neurons in the input layer (MNIST image size is 28x28 = 784), 32 neurons in the hidden layer (code size) and 784 neurons in the output layer (same size as the input layer as is standard for autoencoders)
- Rectified linear unit (RELU) activation function for the hidden layer.
- Sigmoid activation function for the output layer.
- Size of the output images is same as the input image size.
- training the autoencoder with using the noisy images as input and clean images as output. Batch size of 128 with approximately 10 or so epochs
