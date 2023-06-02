# MLP_Perceptron
To implement the internal workings of perceptron and testing the accuracy of in train and test dataset. 
#### A Perceptron 
The perceptron model is a general computational. 
It takes an input, aggregates it (weighted sum) and returns 1 only if the aggregated sum is more than some threshold else returns 0.
###### Perceptron Learning Algorithm
Our goal is to find the w vector(weights) that can perfectly classify positive inputs and negative inputs in our data.
#### We first implement AND, OR and XOR logic with perceptron-learning algorithm by plugging in the approriate weights and computational logic. 
Hence, we create our own perceptrons 
#### AND logic with perceptron
![image](https://github.com/Manjari-99/MLP_Perceptron/assets/69254860/48df42a4-ce44-416f-a899-c87c8d1ff84a)

#### OR logic with perceptron
![image](https://github.com/Manjari-99/MLP_Perceptron/assets/69254860/95b57ba1-c371-4738-acf2-4a07c10ab37a)

#### XOR logic with perceptron
![image](https://github.com/Manjari-99/MLP_Perceptron/assets/69254860/b8327135-c96e-4f95-941c-c73b939ad4e9)

### MLP - Multilayer Perceptron
If a multilayer perceptron has a linear activation function in all neurons, that is,
a linear function that maps the weighted inputs to the output of each neuron, 
then linear algebra shows that any number of layers can be reduced to a two-layer input-output model. 
In MLPs some neurons use a nonlinear activation function that was developed to model the frequency of action potentials, 
or firing, of biological neurons.
![image](https://github.com/Manjari-99/MLP_Perceptron/assets/69254860/1b55962e-6065-4d60-a228-b51a63d717be)


##### IRIS DATASET USING MLP 
We use MLP to classify Iris Dataset. 
![image](https://github.com/Manjari-99/MLP_Perceptron/assets/69254860/2ca63835-ff21-46da-b43e-88711a84f097)
<br>
We use Label Encoder to encode the Class Label - Species Column 
<br>
We next divide the dataset into training 70%  and testing sets 30%.
<br><br>
We use Sequentail Keras Model. We add 3 layers. First two layers have 4 perceptrons and last one has 3 perceptrons. 
The first two layers implement rectified linear unit activation function (ramp), last layer implements softmax to scale it
into probabilities. We then plot the mean-square error and its changes with each epoch (here 10). 
![image](https://github.com/Manjari-99/MLP_Perceptron/assets/69254860/038e36ff-f9fe-4e81-a81a-220ce93b763b)




