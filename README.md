# Image_denoising

Here I implemented autoendocer to denoise image. First of all I added some noise to the existing dataset image. Then I trained a neural network model using these noisy dataset.   

A normal ANN is kindof supervised algo, Where the autoencider is unsupervised training. It is called representation learning. Here we provide the image as an input in the `encoded` section. It also has a `decoded` section, which predicts the output as a reconstructed version. In between this 2 layer, we have a bottleneck `code` layer i.e. the encoded image. We always try to minimize the reconstructor error.      

Here I trained 2 different network for mnist and fashion mnist dataset, both of these are very popular. The source codes in python are available in the respective notebook. The related theory and maths are discussed in the notebook which also can be found in the `Immages` folder. 

Dataset can be found from `tensorflow.keras.datasets`
