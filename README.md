# Image_denoising

Here I implemented autoendocer to denoise image. First of all I added some noise to the existing dataset image. Then I trained a neural network model using these noisy dataset.   

A normal ANN is kindof supervised algo, Where the autoencider is unsupervised training. It is called representation learning. Here we provide the image as an input in the `encoded` section. It also has a `decoded` section, which predicts the output as a reconstructed version. In between this 2 layer, we have a bottleneck `code` layer i.e. the encoded image. We always try to minimize the recontructor error.
