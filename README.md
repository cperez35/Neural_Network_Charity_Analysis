# Neural_Network_Charity_Analysis

### Overview
The analysis aimed to create a binary classifier that predicts the success of applicants funded by a charity using deep learning neural networks with TensorFlow. The objectives were to preprocess and construct datasets, implement neural network and deep neural network models, and save trained TensorFlow models for later use.

### Results
The input data had 40 features, 25724 samples, and 9 columns as model features, while the 'EIN' and 'NAME' columns were removed. The neural network model had two hidden layers with 80 and 30 neurons and used ReLU activation functions in the hidden layers and sigmoid activation functions in the output layer. However, the model did not achieve the target performance of 75% accuracy. Further optimization techniques, such as adding an extra hidden layer, increasing the number of neurons, altering activation functions, and changing the number of epochs, were used but resulted in a maximum accuracy of 72.7%.

### Summary
The deep learning model did not meet the target accuracy, and a random forest classifier may be an alternative to predict the success of charity applicants.
