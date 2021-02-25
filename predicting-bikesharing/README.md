# Predict Bike Sharing

![Bike Share](img.png)

In this project, I built a neural network from scratch to carry out a prediction problem on a real dataset! By building a neural network from the ground up, I had a much better understanding of gradient descent, backpropagation, and other concepts that are important to know before I move to higher-level tools such as PyTorch.

The data comes from the UCI Machine Learning Database.
> https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset

#### Packages Required
 - numpy
 - pandas
 - matplotlib
 - jupyter notebook

#### Checkpoints
 1. The activation function should be a sigmoid
 2. The number of epochs should be between 50 and 15000
 3. The number of hidden nodes should be 5 and 100
 4. There should be exactly one output node
 5. The learning_rate should be between 0.05 and 5
     - Hidden to output = [[0.37275328], [-0.03172939]]   
     - Input to hidden=[[0.10562014, -0.20185996], [0.39775194, 0.50074398], [-0.29887597, 0.19962801]]
 6. The run method should have an expected input as 0.09998924
 7. Produces good results when running the network on full data. Requirements are:
     - Training loss should be less than 0.09
     - Validation loss should be less than 0.18
