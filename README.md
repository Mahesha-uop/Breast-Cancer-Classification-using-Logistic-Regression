# Breast-Cancer-Classification-using-Logistic-Regression
Classification of breast cancer patient as Benign and Malignant type using 30 features.

Dataset downloaded from: https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset

## Dataset features

Includes 595 patients data of features
1. Diagnosis
2. Radius mean	
3. Texture mean
4. Perimeter mean
5. Area_mean
6. Smoothness mean
7. Compactness mean
8. Concavity mean
9. Concave points mean
10. Radius worst
11. Texture worst
12. Perimeter worst
13. Area worst
14. Smoothness worst
15. Compactness worst
16. Concavity worst
17. Concave points worst
18. Symmetry worst
19. Fractal dimension worst

## Regression Method

Logistic regression is a statistical method used for modeling the probability of a binary outcome based on one or more predictor variables. Unlike linear regression, which predicts continuous outcomes, logistic regression predicts the probability that a given instance belongs to a particular category or class. It's widely applied in various fields such as economics, medicine, and social sciences for tasks like classification, risk assessment, and forecasting. The model employs the logistic function, also known as the sigmoid function, to map input variables onto a range between 0 and 1, representing the probability of the outcome. Logistic regression is favored for its simplicity, interpretability, and efficiency, making it a fundamental tool in the arsenal of predictive modeling techniques.

## Training

From Linear models in Sklearn library here logistic regression model is used.
As oiginal dataset is more biased towards Benign type. Dropped some of Belign type patient data.
Training Accuracy: 94.94%

## Test

Test accuracy is 92.45%.
