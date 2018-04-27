# AI-Bank-Classifier
First AI project: making a classifier that determines whether a user will stay with a bank according to their bank account information


Information about customers, including CreditScore, Age, Balance, is collected from a bank. The data is processed by appropriately managing categorical data, and applying feature scaling. The data set is split into a 80% training set and 20% test set. The network is constructed through using the keras library with 2 hidden dense layers each with 6 neurons. The final output layer is one neuron using the sigmoid activation function, to give us the probability of the user staying with the bank. Finally, the model is trained using our training data, the 'adam' optimizer and binary cross entropy as the loss function. 

After training the model repeatedly, the average accuracy was around 87%

This is part of my learning process to master AI and deep learning. This is my first project applying my machine learning knowledge, and it was done with the help of an online course on Udemy.
