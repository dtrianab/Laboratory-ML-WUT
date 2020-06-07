# Laboratory-ML-[WUT](https://www.pw.edu.pl/)

This repository contains some laboratory tasks to perform in the AI Course given at [WUT](https://www.pw.edu.pl/).

**May of 2018**

## Classification using the MultiLayer Perceptron (MLP)  feedforward neural network

The following datasets will be studied along with the topology of the multilayer perceptron (MLP) model. The performance measurements will be collected on the basis of its percentage error taking into account the number of neurons and the number of repetitions in the training process.

Datasets:
* Simple Classes Data Set
* Iris Flowers
* Breast Cancer
* Type of Glass
* Thyroid
* Wine Vintage

The laboratory is aimed to tune a suitable number of  hidden neurons and analyze the testing percentage error according to number of repetitions while training the model. 

### Neural network structure

The studied neural network is composed of three layers: input layer, one hidden layer and the output layer. The input layer is defined according to the number of inputs or features which are going to be evaluated by the neural network. The hidden layer contains a given number of neurons specified by the user. The output layer contains the number of outputs of the neural network which are the labels of the classification. 

 Structure of the multilayer perceptron in MATLAB.

## Results 

* Simple Classes Dataset

Targets of a simple classes data set is a 4x1000 matrix, representing static data: 1000 samples of 4 elements.  Inputs is a 2x1000 matrix, representing static data: 1000 samples of 2 elements.

Table below presents the results of the percentage error in testing data simulated fifty times. Simulation started with 10 hidden neurons and due to the obtained error was 0 we decided to simulate with less number of hidden neurons and we got that the suitable number of neurons for this case is 3 since below 3 the error increases. 

We can also use the confusion plot to observe how well the neural network has fit the data. The confusion matrix shows the percentages of correct and incorrect classifications. Correct classifications are the green squares on the matrix diagonal and incorrect classifications are the red squares, as you can observe  in the following figure.


* Iris Flowers

