# lab_assignment3

student number 230793983
module code BICT332
Artificial Intelligence

Key Questions

1.How does regularization prevent overfitting?

Regularization (e.g., L2 in Logistic Regression, C in SVM) penalizes large weights, simplifying the model and reducing sensitivity to noise. For example, smaller C in SVM widens margins, prioritizing generalization over fitting every point. In Logistic Regression, lower C shrinks weights, smoothing decision boundaries. This reduces variance, preventing overfitting on noisy or small datasets like Iris.


2.When to use ensembles vs. simple models?

Ensembles (e.g., Random Forests):

Use for complex, noisy, or nonlinear data (e.g., moons), as they reduce variance through averaging (bagging) and handle high-dimensional data well.
Ideal when interpretability is less critical, and computational resources allow multiple trees.
Example: Random Forests outperformed linear models on moons (~0.967 vs. ~0.833).
Simple models (e.g., Perceptron, Logistic Regression):
Use for linearly separable data (e.g., Iris), small datasets, or when interpretability is key (e.g., Logistic Regression’s probabilities).
Faster to train and suitable for resource-constrained environments.
Example: Logistic Regression and Linear SVM performed well on Iris (~0.956) with less complexity than Random Forests.
