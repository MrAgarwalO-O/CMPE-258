# Assignment 6

## Description

Note this is multiple colabs assignment - please put proper readme with all colabs - do not copy paste from hint colabs. write it in your own way.
Give a detailed video going over the code of each colab and upload it.
Make sure you organize your GitHub directory properly and readme
You should execute and show while explaining what you wrote in colabs.

### Part 1

a) Write simple colabs to illustrate various data augmentation and generalization techniques (with A/B tests)

 

Write in both tensorflow

showcase various regularizations

a) l1 l2

b) dropout

c) earlystop

d) montecarlo dropout

e) various initializations and when to use what

f) batch norm

g) custsom dropout, custom regularization

h) using callbacks and tensorboard 

i) using keras tuner

j)_ use keras cv data augmentation 
k) write colabs for data augmentation and classification  for image, video, text (nlpaug), timeseries, tabulardata, speech, document images 

l) Demonstrate fastai data augmentation capablities 

### Part 2

A) Write a colab/colabs where you will use advanced Keras deep learning constructs concepts

This is a very important assignment - helps you understand and have an edge over others

Please ensure you use the links i provided for hints as examples. Use your own creativity. Properly annotate your colab/colabs appropriately and write proper explanation and description. Properly demonstrate each of these aspects with either individual colabs or one colab having all these. 

i) User custom learning rate scheduler (see https://github.com/ageron/handson-ml2/blob/master/11_training_deep_neural_networks.ipynbLinks to an external site.Links to an external site. onecyclescheduler example)

ii) use custom dropout - ( see MCAlphaDropout in above link)

iii) Use custom normalization - (see MaxNormDense in above link)

iv) use tensorboard - (see above link)

v) use custom loss function - (see HuberLoss in https://github.com/ageron/handson-ml2/blob/master/12_custom_models_and_training_with_tensorflow.ipynbLinks to an external site.Links to an external site.) 

vi) use custom activation function,initializer regularizer and kernel weight constraint (see leaky_relu, my_glorot_initializer, MyL1Regularizer , my_positive_weights in above link)

vii) use custom metric (see HuberMetric in above link)

viii) Use custom layers (see exponential_layer, MyDense, AddGaussianNoise, LayerNormalization in above link)

ix) Use custom model (see ResidualRegressor and ResidualBlock example in above link)

x) Custom optimizer (See MyMomentumOptimizer in above link)

xi) Custom Training Loop (see 13 section for fashion mnist in above link)

## Assignment Deliverables

1. Neural networks with Keras-Part1.ipynb
2. Neural networks with Keras-Part2.ipynb


## References Used

1. [10_neural_nets_with_keras.ipynb](https://github.com/ageron/handson-ml3/blob/main/10_neural_nets_with_keras.ipynb)
2. [11_training_deep_neural_networks.ipynb](https://github.com/ageron/handson-ml3/blob/main/11_training_deep_neural_networks.ipynb)
3. [awesome-data-augmentation](https://brunokrinski.github.io/awesome-data-augmentation/)
4. [keras_cv](https://keras.io/keras_cv/)
5. [tensorflow](https://www.tensorflow.org/)
6. [07_sizing_and_tta.ipynb](https://github.com/fastai/fastbook/blob/master/07_sizing_and_tta.ipynb)
7. [11_training_deep_neural_networks.ipynb](https://github.com/ageron/handson-ml2/blob/master/11_training_deep_neural_networks.ipynb)
8. [12_custom_models_and_training_with_tensorflow.ipynb](https://github.com/ageron/handson-ml2/blob/master/12_custom_models_and_training_with_tensorflow.ipynb)
