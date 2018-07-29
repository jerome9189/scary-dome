# scary-dome
Simple neural network model using Keras for predicting benign and malignant breast tumors.
Reaches accuracy of over 95%.

## Dataset
Breast Cancer Wisconsin (Diagnostic) Data Set
https://www.kaggle.com/uciml/breast-cancer-wisconsin-data

This dataset labels each tumor as either malignant('M' or 1), or benign('B' or 0). There are thirty features.

![alt text](https://github.com/jerome9189/scary-dome/blob/master/images/plot.png?raw=true "Data")


## Model design
This neural network has thirty inputs and one 10-neuron hidden layer with a Rectified Linear Unit(ReLU) activation, followed by an output layer with a sigmoid activation.

![alt text](https://github.com/jerome9189/scary-dome/blob/master/images/model.png?raw=true "Neural Network Model")