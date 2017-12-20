
# Fashion-MNIST-Keras
Modify the keras MNIST examples to use the new Fashion-MNIST dataset from @[Zalando Research](https://github.com/zalandoresearch)
All the code files here are originally part of the [keras examples](https://github.com/fchollet/keras/tree/master/examples), and was modified to serve as a starting point to any one aiming to start using
the new Fashion-MNIST dataset.

# [Fashion-MNIST](https://github.com/zalandoresearch/fashion-mnist)
A dataset of Zalando's article images consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. Fashion-MNIST is intended to serve as a direct drop-in replacement of the original [MNIST dataset](http://yann.lecun.com/exdb/mnist/) for benchmarking machine learning algorithms.

# Included Examples
All the examples below using the same parameters and architecture as the keras examples. The only change was using Fashion-MNIST instead of the original MNIST.
This should serve as an encouragement to anyone who wants to move away from MNIST, your code will need around 5 minutes changes to begin using the new dataset.


[fashion_mnist_acgan.py](fashion_mnist_acgan.py)
Implementation of AC-GAN ( Auxiliary Classifier GAN ) on the FASHION-MNIST dataset

[fashion_mnist_cnn.py](fashion_mnist_cnn.py)
Trains a simple convnet on the FASHION-MNIST dataset.

[fashion_mnist_hierarchical_rnn.py](fashion_mnist_hierarchical_rnn.py)
Trains a Hierarchical RNN (HRNN) to classify FASHION-MNIST images.

[fashion_mnist_irnn.py](fashion_mnist_irnn.py)
Reproduction of the IRNN experiment with pixel-by-pixel sequential FASHION-MNIST in "A Simple Way to Initialize Recurrent Networks of Rectified Linear Units" by Le et al.

[fashion_mnist_mlp.py](fashion_mnist_mlp.py)
Trains a simple deep multi-layer perceptron on the FASHION-MNIST dataset.

[fashion_mnist_net2net.py](fashion_mnist_net2net.py)
Reproduction of the Net2Net experiment with FASHION-MNIST in "Net2Net: Accelerating Learning via Knowledge Transfer".

[fashion_mnist_siamese_graph.py](fashion_mnist_siamese_graph.py)
Trains a Siamese multi-layer perceptron on pairs of digits from the FASHION-MNIST dataset.

[fashion_mnist_sklearn_wrapper.py](fashion_mnist_sklearn_wrapper.py)
Demonstrates how to use the sklearn wrapper.

[fashion_mnist_swwae.py](fashion_mnist_swwae.py)
Trains a Stacked What-Where AutoEncoder built on residual blocks on the FASHION-MNIST dataset.

[fashion_mnist_transfer_cnn.py](fashion_mnist_transfer_cnn.py)
Transfer learning toy example.
