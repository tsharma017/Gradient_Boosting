# Gradient_Boosting

Gradient Boosting is a powerful machine learning technique used for both classification and regression tasks. It is based on the concept of boosting, where multiple weak models (usually decision trees) are combined to create a strong model.

1. What is Boosting?
Boosting is an ensemble learning method that builds models sequentially, where each new model learns from the mistakes of the previous ones.

✅ Key idea: Instead of training all models independently, boosting corrects errors made by earlier models.

2. How Does Gradient Boosting Work?
Gradient Boosting is an iterative process that builds new models step by step to minimize the error.

Step-by-Step Process:
Start with a Simple Model (Weak Learner)

Usually, a shallow Decision Tree (stump) is used as the first model.
Calculate the Errors (Residuals)

Compute the difference between the actual values and the model’s predictions.
Train a New Model on the Residuals

The next model focuses on correcting the mistakes of the previous model.
It learns to predict the residuals instead of the original values.

The process continues until the model reaches a stopping criterion (e.g., no further improvement).


3. Why "Gradient" Boosting?
The term "Gradient" comes from the fact that it minimizes errors using gradient descent.
Instead of simply adjusting weights like AdaBoost, Gradient Boosting optimizes the loss function directly.
It uses the gradient (slope) of the loss function to improve predictions.
