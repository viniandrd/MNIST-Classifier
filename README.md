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
conda install -c pytorch -c fastai fastai
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
