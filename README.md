# Keras optimizers comparison and training analysis

## Definition 
In Keras, an open-source neural network library written in Python, optimizers are algorithms or methods used to adjust the weights of a neural network during training to minimize the loss function. Essentially, they help in finding the best parameters for the model to make accurate predictions.

1. **SGD (Stochastic Gradient Descent)**: The simplest form of optimization algorithm. It updates the weights using the gradient of the loss function with respect to the weights, often with a small learning rate. Variants include momentum and Nesterov accelerated gradient (NAG).
2. **Adam (Adaptive Moment Estimation)**: Combines the advantages of two other extensions of stochastic gradient descent. It computes adaptive learning rates for each parameter and uses momentum-like terms.
3. **RMSprop (Root Mean Square Propagation)**: Adjusts the learning rate for each weight based on the average of recent gradients for that weight. It is particularly useful for handling non-stationary objectives.
4. **Adagrad (Adaptive Gradient Algorithm)**: Adapts the learning rate for each parameter based on the frequency of updates. It tends to perform well for sparse data.
5. **Adadelta**: An extension of Adagrad that seeks to reduce its aggressive, monotonically decreasing learning rate. It uses a window of accumulated past gradients to normalize the gradients.
6. **FTRL (Follow The Regularized Leader)**: An optimization algorithm that incorporates regularization into the learning process. It is useful in scenarios where data is sparse and there are many features.


