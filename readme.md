# SPI ( GPA ) Predictor

## Introduction
* This project is a simple implementation of a linear regression model using PyTorch library to predict SPI (Standardized Precipitation Index) values based on input precipitation data.

* The dataset consists of 20 rows of input data, each with 3 features, and a corresponding SPI value.

* The model is trained using mean squared error loss and gradient descent optimization.

 ## Requirements
The following libraries are required to run the code:

  [NumPy](https://numpy.org/doc/)
  
  [PyTorch](https://pytorch.org/docs/stable/index.html)

## Usage
* To run the code, simply execute the script in a Python environment that has the required libraries installed. The script will output the final loss, weights, and bias of the trained model.

## Algorithm

* Gradient Descent Algorithm with Linear Regression is used to train this model

## Code Explanation
* The input data is defined as a NumPy array with 20 rows and 3 columns. The target output is also defined as a NumPy array with 20 rows and 1 column.

* The weights and bias of the neural network model are initialized randomly and with requires_grad set to True, indicating that they need to be updated during training.

* The model is trained for a fixed number of iterations using gradient descent optimization. The loss function used is mean squared error loss.

* After training, the final loss, weights, and bias are printed to the console.

## Future Improvements
* Some potential areas of improvement for this project include:

* Use a larger and more diverse dataset to improve the accuracy of the model.

* Experiment with different neural network architectures and hyperparameters to find the best model configuration.

* Implement techniques such as early stopping and regularization to prevent overfitting.
