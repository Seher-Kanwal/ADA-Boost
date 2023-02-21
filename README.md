# ADA-Boost
AdaBoost (short for Adaptive Boosting) is a machine learning algorithm that can be used for both classification and regression problems. It is an ensemble learning method that combines several weak models (also called base models or weak learners) to form a stronger model. The basic idea behind AdaBoost is to give more weight to the misclassified data points so that the next base model will focus more on the misclassified data points in order to correctly classify them.

### Here are the basic steps of the AdaBoost algorithm:

- __Initialize weights__

    Each data point is assigned an initial weight of 1/n, where n is the total number of data points.

- __Train a weak learner__

    A weak learner is trained on the data set using the current weights.

- __Evaluate the weak learner__

    The weak learner is evaluated on the data set, and the misclassified data points are identified.

- __Update the weights__

    The weights of the misclassified data points are increased, and the weights of the correctly classified data points are decreased. The updated weights are then normalized so that they sum up to 1.

- __Repeat__
   Steps 2 to 4 are repeated until the desired number of weak learners is reached, or until the accuracy of the model has reached a satisfactory level.


- __Combine the weak learners__

   The weak learners are combined to form a strong model, where the contribution of each weak learner is determined by its accuracy.

The final model can be used to make predictions on new data points. The AdaBoost algorithm is known for its high accuracy and robustness to overfitting, but it can be sensitive to noisy data.



