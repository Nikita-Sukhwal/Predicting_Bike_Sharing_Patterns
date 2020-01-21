# Predicting_Bike_Sharing_Patterns

### Introduction
In this project, a neural network is built from scratch to carry out a prediction problem on a real dataset! By building a neural network from the ground up, and had a much better understanding of gradient descent and backpropagation.

The data comes from the UCI Machine Learning Database.

### Instructions
1. Download the project materials from our GitHub repository. You can get download the repository with git clone https://github.com/udacity/deep-learning-v2-pytorch.git. cd into the project-bikesharing directory.
2. In your browser, open Predicting_bike_sharing_data.ipynb. 
3. Follow the instructions in the notebook; my_answers.py is a python file whose components are imported into the notebook at various places.

### Steps Followed for project
1. Loading and Preparing Data
2. Data Analysis
3. Data Preprocessing
   - Adding Dummy Variables for some categorical data.
   - Scaling continuous variables such that they have zero mean and a standard deviation of 1.
   - Splitting the data into training, testing, and validation sets.
 4. Building Neural Network.
    - Tasks
      - Implementing the sigmoid function to use as the activation function. 
      - Implementing the forward pass in the train method.
      - Implementing the backpropagation algorithm in the train method, including calculating the output error.
      - Implementing the forward pass in the run method.
 5. Training the neural network.
    - Hyperparameters
      - iterations = 4500
      - learning_rate = 0.5
      - hidden_nodes = 17
      - output_nodes = 1
 6. Testing the network
    - Training loss: 0.066
    - Validation loss: 0.167
