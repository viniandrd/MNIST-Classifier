# MNIST-Classifier

This repository contains a notebook implementing a binary classifier to classify only the digits **0** and **5** from MNIST dataset. 
The solution is implemented in [PyTorch](https://pytorch.org/) framework, using the [fastai](https://docs.fast.ai/) API.

## Requirements

To properly run this notebook, two things needs to be setted:

1. Fastai API
2. Jupyter Notebook

The installation guide of these two items can be seen in the sections below.


### Fastai API
Following the instructions provided by fastai, you will need to install the API via anaconda or pip.

If you are using [Anaconda](https://www.anaconda.com/), create a new environment and run this command to install pytorch and fastai. (It will also install support for GPU, which is cuda toolkit)

```
conda install -c fastai fastai -c pytorch
```

But if you want to install fastai with PIP, you will need to install PyTorch first, following the PyTorch [installation guide](https://pytorch.org/get-started/locally/). After installing PyTorch, install fastai with:

```
pip install fastai
```

### Jupyter notebook

To start a new jupyter server and run this or new notebooks, you will need to install jupyter.
Following the instructions provided by [Jupyter](https://jupyter.org/install), there are two ways to install it.

1. If you are using Anaconda, you can install running:

```
conda install -c conda-forge notebook
```

2. Or if you want to install with PIP, just run:

```
pip install notebook
```

## Steps

The notebook is organized as follows:

1. Prepare dataset with properly preprocessing.
2. Define the loss function and metrics.
3. Create a `Sequential` model (neural network).
4. Create a `Leaner`, provided by fastai.
5. Train the model
6. Analyze results

## Conclusion

The classifier implemented here is a simple classifier model, composed only of linear layers and activation function. It is also possible to do this using Convolutional Neural Networks (CNN), which has convolution layers.

By training the model for `40` epochs with a learning rate of `0.1`, the batch accuracy reached a value of 98%. This shows that the model has a 98% chance of differentiating the digits 0 and 5 correctly. 

Analyzing the graphics on the notebook, it can be seen that the training had good performance and stability, and the loss could easily converge.
