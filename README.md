# Multi-Layered-perceptron
This program implements a feedforward neural network with a single hidden layer that is trained using the backpropagation learning algorithm. The user first specifies the network parameters, including the number of training samples, input neurons, hidden neurons, training epochs, and learning rate. Training data can then be entered manually or imported from a CSV file, with validation ensuring that only binary values (0 and 1) are accepted. The network randomly initialises weights connecting the input layer to the hidden layer and the hidden layer to the output layer. During training, forward propagation is used to calculate hidden and output neuron activations using the sigmoid activation function. The difference between the predicted and expected outputs is then used in backpropagation to adjust the weights and reduce prediction error over multiple epochs. After training is complete, the final weights are displayed and the network generates predictions for each input sample, allowing the user to evaluate the network’s learned behaviour.

<img width="693" height="230" alt="image" src="https://github.com/user-attachments/assets/dcb6a833-dba8-4f67-a7ad-80493d1913bf" />

Figure 1 The figure shows the inputs for the multi layered perceptron 

<img width="246" height="663" alt="image" src="https://github.com/user-attachments/assets/3c6c3973-1deb-48f0-9bdd-96926da6fe39" />

Figure 2 shows the results from the inputs above
