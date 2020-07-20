# Artificial-Neural-Network
What is ANN
Neural networks form the base of deep learning, which is a subfield of machine learning, where the structure of the human brain inspires the algorithms. Neural networks take input data, train themselves to recognize patterns found in the data, and then predict the output for a new set of similar data. Therefore, a neural network can be thought of as the functional unit of deep learning, which mimics the behavior of the human brain to solve complex data-driven problems.
 It is like an artificial human nervous system for receiving, processing, and transmitting information in terms of Computer Science.
It isacomputational system inspired by the
Structure
Processing Method
Learning Ability
of a biological brain

Characteristics of Artificial Neural Networks:
A large number of very simple processing neuron-lik e processing
elements
A large number of weighted connections between the elements
Distributed representation of knowledge over the connections
Knowledge is acquired by network through a learning process
Basically, there are 3 different layers in a neural network :-
Input Layer (All the inputs are fed in the model through this layer)
Hidden Layers (There can be more than one hidden layers which are used for processing the inputs received from the input layers)
Output Layer (The data after processing is made available at the output layer)
Furthermore the learning happens in two steps:
Forward-Propagation
Back-Propagation

Components of artificialneural networks:
A neural network is characterized by
1) Its pattern of connections between the neurons (called its
architecture).
2) Its method of determining the weights on the connections (called its
training, or learning, algorithm).
3) Its activation function.

ANN Application:
a. Classification of data:
Based on a set of data, our trained neural network predicts whether it is a dog or a cat?
b. Anomaly detection:
Given the details about transactions of a person, it can say that whether the transaction is fraud or not.
c. Speech recognition:
We can train our neural network to recognize speech patterns. Example: Siri, Alexa, Google assistant.
d. Audio generation:
Given the inputs as audio files, it can generate new music based on various factors like genre, singer, and others.
e. Time series analysis:
A well trained neural network can predict the stock price.
f. Spell checking:
We can train a neural network that detects misspelled spellings and can also suggest a similar meaning for words. Example: Grammarly
g. Character recognition:
A well trained neural network can detect handwritten characters.
h. Machine translation:
We can develop a neural network that translates one language into another language.
i. Image processing:

Advantages:

ANN's have the abiity to learn and model non linear and complex relatiionshis.
it does not impose any restriction on the input varaibles

About The project

Aim:
The main aim of this proect is to help deploy a Python module that can be downloaded by uers via pip to create neural networks. 

How Do We Achieve this:

Mathematics involved:

Calculate the dot product between inputs and weights
Pass the result from step 1 through an activation function
The result from Step 1 can be a set of any values. However, in our output we have the values in the form of 1 and 0. We want our output to be in the same format. To do so we need an activation function, which squashes input values between 1 and 0. One such activation function is the sigmoid function.
Back Propagation
We start by letting the network make random predictions about the output. We then compare the predicted output of the neural network with the actual output. Next, we fine-tune our weights and the bias in such a manner that our predicted output becomes closer to the actual output, which is basically known as "training the neural network".
Calculating the cost
Minimizing the cost

Implementation by python:

 Import Required libraries:
 
First, we are going to import Python libraries. We are using NumPy for the calculations:
Next, we are going to take input values for which we want to train our neural network. Here we can see that we have taken two input features. In actual data sets, the value of the input features is mostly high.
For the input features, we want to have a specific output for specific input features. It is called the target output. We are going to train the model that gives us the target output for our input features.

Assign the Weights :
Next, we are going to assign random weights to the input features. Note that our model is going to modify these weight values to be optimum. At this point, we are taking these values randomly. Here we have two input features, so we are going to take two weight values.
Adding Bias Values and Assigning a Learning Rate :

Now here we are going to add the bias value. The value of bias = 1. However, the weight assigned to it is random at first, and our model will optimize it for our target output.
The other parameter is called the learning rate(LR). We are going to use the learning rate in a gradient descent algorithm to update the weight values. Generally, we keep the learning rate as low as possible so that we can achieve a minimum error rate.
Applying a Sigmoid Function:

Once we have our weight values and input features, we are going to send it to the main function that predicts the output. Now notice that our input features and weight values can be anything, but here we want to classify data, so we need the output between 0 and 1. For such, we are going to a sigmoid function.
 Derivative of sigmoid function:
 
In gradient descent algorithm we are going to need the derivative of the sigmoid function.
when it comes to AI the longer we train a model ,the better we can yeild accurate result.

This project helps serve this very purpose .it helps users to download a Python module(using pip ),to create neural networks.it makes the user's job easy ,while providing  great precision and accuracy.

https://user-images.githubusercontent.com/65071309/84528081-a9479c00-acfc-11ea-88b9-bcd515b30849.png

Contribution Guidelines:

This document provides a set of best practices for open source contributions bug reportscode submissions/pull requests,etc
