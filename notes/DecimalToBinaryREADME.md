# DECIMAL TO BINARY represenatation in a neural network

This is a python implementation of NNADL to convert a digit classification neural network classification's decimal output to bitwise representation. 

Magic is in last layer.

### [Question](http://neuralnetworksanddeeplearning.com/chap1.html#exercise_513527)

>There is a way of determining the bitwise representation of a digit by adding an extra layer to the three-layer network above. 
The extra layer converts the output from the previous layer into a binary representation, as illustrated in the figure below. 

>Find a set of weights and biases for the new output layer. 
Assume that the first 3 layers of neurons are such that the correct output in the third layer (i.e., the old output layer) has activation at least 0.99, and incorrect outputs have activation less than 0.01.

![nn_image](https://github.com/tajain07/neuralnetworksanddeeplearning-exercise-solution/blob/master/tikz13.png)
