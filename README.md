# Neural_Network

## Resources
* Data Source: charity_data.csv
* Software: Python 3.7.6, Jupyter Notebook
* Libraries: Pandas, Sklearn

## Summary

1. How many neurons and layers did you select for your neural network model? Why?
After a lot of trail and error, 2 layers was the one i settled on.

2. Were you able to achieve the target model performance? What steps did you take to try and increase model performance?

I fail to acheieve the traget model performance. 

Here are the steps that i took to try to increse the model performance.

* Removed highly distributed column
* Binning and drop columns
* Changed the number of neurons
* Changed the number of layers
* Change the number of epochs
* Different types of activation function for input and output


3. If you were to implement a different model to solve this classification problem, which would you choose? Why?

To solve this classification problem I would choose to use random forest because:

* It handles well tabular, nonlinear data
* Is robust against overfitting
* Faster than a neural network