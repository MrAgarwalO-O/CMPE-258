# Assignment 05 - Basic neural networks using numpy tensorflow pytorch jax


## About the Assignment

This assignment is designed to explore the implementation of deep learning models for non-linear regression tasks using various frameworks including Numpy, PyTorch, TensorFlow, and JAX. It focuses on constructing a three-layer neural network from scratch. The task requires an understanding of manual backpropagation, chain rule-based gradient propagation, and the utilization of TensorFlow's `einsum` for matrix operations, aiming for a deeper understanding of neural network internals.

## Assignment Description

### Objective

- **To implement a three-layer deep neural network for non-linear regression.** The models should predict outputs from synthetic data generated based on a non-linear equation involving three variables. This project requires manual construction of the networks, including defining layers, activation functions, and the backpropagation algorithm without relying on high-level API functionalities for the deep learning tasks.

### Overview

- **Generated synthetic data** based on a non-linear equation with three variables. Used this data to train and test the models.
- **Constructed and trained three-layer neural networks** using different deep learning frameworks:
  - Numpy (manual implementation from scratch)
  - PyTorch (both scratch and class-based implementations)
  - TensorFlow (various implementations including low-level operations, built-in layers, functional API, and high-level API)
  - PyTorch Lightning
  - JAX
- **Utilized TensorFlow's `einsum`** for matrix multiplication tasks.
- **Analyzed and visualized the training process** using metrics such as loss and accuracy over epochs. Implemented a 4D plot to visualize the data and model predictions.

## Deliverables

1. `PartA_numpy_scratch.ipynb` - Numpy implementation of the three-layer neural network from scratch.
2. `PartB_pytorch_scratch.ipynb` - PyTorch implementation of the three-layer neural network from scratch, without using built-in layer functionalities.
3. `PartC_pytorch_classes.ipynb` - PyTorch class-based implementation, using built-in functionalities for layers and backpropagation.
4. `PartD_pytorch_lightening.ipynb` - Implementation using PyTorch Lightning to streamline the model training process.
5. `PartE1_Tensorflow.ipynb` - TensorFlow low-level API implementation, including manual operations.
6. `PartE2_Tensorflow_scratch.ipynb` - TensorFlow implementation from scratch, not using high-level APIs.
7. `PartE3_Tensorflow_builtIn.ipynb` - TensorFlow implementation using built-in layers.
8. `PartE4_Tensorflow_functionalAPI.ipynb` - TensorFlow implementation using the functional API.
9. `PartE5_Tensorflow_highLevelAPI.ipynb` - TensorFlow implementation using high-level API functionalities.
10. `PartH_JAX.ipynb` - Implementation using JAX for efficient automatic differentiation and GPU/TPU computations.

## References Used

1. [Neural Network with numpy](https://medium.com/@waleedmousa975/building-a-neural-network-from-scratch-using-numpy-and-math-libraries-a-step-by-step-tutorial-in-608090c20466)
2. [Neural Network with pytorch](https://pytorch.org/tutorials/beginner/basics/buildmodel_tutorial.html)
3. [Neural Network with tensorflow](https://www.turing.com/kb/building-neural-network-in-tensorflow)
4. [Pytorch from scratch]( https://docs.google.com/presentation/d/13Oo5gXwcsoq9oMC4XriAyxkvgicatBxfI4cZzDhRyiE/edit#slide=id.g826a355833_0_525)
5. [you-dont-know-jax.ipynb](https://github.com/craffel/jax-tutorial/blob/master/you-don-t-know-jax.ipynb)
6. [How to make a 4D plot with Matplotlib using arbitrary data?](https://www.tutorialspoint.com/how-to-make-a-4d-plot-with-matplotlib-using-arbitrary-data)
7. [JAX Quickstart.ipynb](https://colab.research.google.com/github/google/jax/blob/main/docs/notebooks/quickstart.ipynb)
