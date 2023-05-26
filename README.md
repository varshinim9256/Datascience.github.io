The Multi-layer Perceptron(MLP) is a feedforward neural network, which means that the data is transmitted from the input layer to the output layer in the forward direction.The connections between the layers are assigned weights. The weight of a connection specifies its importance. While the inputs take their values from the surroundings, the values of all the other neurons are calculated through a mathematical function involving the weights and values of the layer before it. Backpropagation is a technique used to optimize the weights of an MLP using the outputs as inputs.In a conventional MLP, random weights are assigned to all the connections. These random weights propagate values through the network to produce the actual output. Naturally, this output would differ from the expected output. The difference between the two values is called the error.

Libraries used:
Matplotlib. pyplot  and seaborn are used for data visualisation
Numpy  is used for finding the exponential value
Sklearn is used for preprocessing techniques like Scaling and also for drawing the results by plotting classification report which gives the performance of the model in terms of f1 score, accuracy, precision etc .

Dataset used:
BankNote Authentication dataset 

The Seaborn Pairplot allows us to plot pairwise relationships between variables within a dataset. This creates a nice visualization and helps us understand the data by summarising a large amount of data in a single figure.

Scaling :
Scaling of Features is essential in modeling the algorithms with the datasets. The data that is usually used for the purpose of modeling is derived through various means . So, the data obtained contains features of various dimensions and scales altogether. Different scales of the data features affect the modeling of a dataset adversely.It leads to a biased outcome of predictions in terms of misclassification error and accuracy rates. Thus, it is necessary to Scale the data prior to modeling. Standardization is a scaling technique wherein it makes the data scale-free by converting the statistical distribution of the data into mean 0 and standard deviation 1 format.

Initialising the  parameters:
Learning rate : the learning rate is a configurable hyperparameter used in the training of neural networks that has a small positive value, often in the range between 0.0 and 1.0. here learning rate lr is intialised as 0.03

Activation function : The Activation function plays  a crucial role in NN. The self defined activation function  k0+k1*x  is used in hidden layer where k0,k1 are the parameters k0=0.5 and k1=0.5 and softmax activation function is used in case of output layer .

Epochs : epochs shows the number of times the model is trained to learn from the data, more the number of epochs better the model learns

Weights and bias : weights and bias are assigned to the inputs in order to give importance to certain values,bias b1 and b2 both are initialised as 1.

Cost function : The cost function is the technique of evaluating “the performance of our algorithm/model”. It takes both predicted outputs by the model and actual outputs and calculates how much wrong the model was in its prediction.here root mean square error is used as cost function.
