# Notes:

# characteristics of the gradient descent process.

The cost starts large and rapidly declines as described in the slide from the lecture.
The partial derivatives, dj_dw, and dj_db also get smaller, rapidly at first and then more slowly. As shown in the diagram from the lecture, as the process nears the 'bottom of the bowl' progress is slower due to the smaller value of the derivative at that point.
progress slows though the learning rate, alpha, remains fixed

# Overfitting and underfitting 

Overfitting and underfitting are two common problems that occur when building machine learning models.

## Overfitting 

Overfitting happens when the model learns the training data too well, to the point that it memorizes it instead of learning the underlying patterns. This can result in poor performance on new, unseen data or even fail to predict, as the model is too specialized to the training set.

## Underfitting

Underfitting happens when the model is not complex enough to capture the patterns in the training data. This can result in poor performance on both the training set and new data, as the model is not able to learn the underlying relationships between the features and the target variable.

In both cases, the model is not able to generalize well to new, unseen data, and is therefore not very useful for making predictions.
