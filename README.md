## Building and training a GAN on MNIST Dataset

In this notebook, I build and train an adversarial network using the Tensorflow API. The adversarial networks consists of a generator and discriminator networks, both build using the Tensorflow API and trained on the MNIST dataset available in Tensorflow as well.

I had initially experimented with other datasets, but finally arrived at MNIST because the images in the training data are 28x28 pixels and grayscale, which facilitated the training by reducing the computational and time resources needed. This meant I could potentially arrive at good results and stable training with simpler networks architecures. The goal of this project was not to achieve high quality generated data but rather just to experiment in building adversarial networks.

Overall, the network achieved stable training and decent quality results. Futher improvements could consist of tweaking the network's architecture and/or implementing other regularization strategies.

