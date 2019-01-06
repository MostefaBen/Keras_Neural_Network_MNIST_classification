# MNIST Classification using Fully connected Neural Network

I have developped a fully connected neural network to classify MNIST images using keras as a Deep Learning library with Tensorflow as backend, 
where the pipeline of the is model as follows:
1) First step is: the imports
2) Second step is: data collection 
3) third step is: data preparation
4) fourth step is data normalization
5) fifth step is data tranformation
6) sixth step is: to define the model
7) seventh step is: to compile the created model, thus this model will become as a computaional graph
8) eighth step: after doing all above steps, we can start the model training 
9) the last step is model evaluation

After aplying only all the above steps, we have obtained a test accuracy = 0.95, and a test loss = 0.16

# To improve the proposed fully connected model, there are many methods and steps:
1) first step: adding more epochs
2) second step: to obtain more accurate results, we adjust the batch size
3) to avoid the problem of unbalanced data, we add a weighted cross entropy loss function 
instead of cross entropy loss function there are several methods to get the best weight for each class, but here
we will assign each weight to 0.1
4) the fourth step: changing the architecture, for example adding more neurons in each hidden layer
5) the last step: we will add more layers, for example 3 hidden layers, each with 256 neurons

After aplying the new steps to improve the fully connected neural network, we have obtained a test accuracy= 0.98, and a test loss= 0.083.

# Author
This project has been developed by Mostefa Ben naceur https://fr.linkedin.com/in/mostefabennaceurphd
