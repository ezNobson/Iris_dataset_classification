## Iris_dataset_classification
## Project Description
This project aims to compare the performance of three popular classification algorithms:

Logistic Regression,
K-Nearest Neighbours (KNN),
Support Vector Machine (SVM).
The well-known Iris dataset is used, which contains information about three species of iris flowers and their features
## Dataset
Name: Iris Dataset
Source: Built-in dataset from the scikit-learn library.
Description:
Number of samples: 150
Number of features: 4 (sepal length, sepal width, petal length, petal width)
Number of classes: 3 (setosa, versicolor, virginica)
Goal: Predict the species of a flower based on its features.

## Algorithms
The following algorithms were implemented and evaluated in this project:

Logistic Regression:
A classic linear classification algorithm.
Results were evaluated using accuracy and confusion matrices.
K-Nearest Neighbours (KNN):
A distance-based classification algorithm.
The hyperparameter 
𝑘
k (number of neighbors) was optimized using GridSearchCV.
Support Vector Machine (SVM):
A classification algorithm that maximizes the margin between classes.

## Technologies and Tools
The following technologies were used in this project:

Programming Language: Python
Libraries:
pandas - for data manipulation
numpy - for numerical computations
matplotlib and seaborn - for data visualization
scikit-learn - for building and evaluating the machine learning model
## Steps Taken
Data Exploration:
Analyzed the distribution of features and visualized the data.
Checked for missing values (no missing data in the Iris Dataset).
Data Preparation:
Selected two features: petal length (cm) and petal width (cm).
Split the data into training, validation testing sets (75%/25%).
Standardized the features using StandardScaler.
Model Building:
Used the algorithms.
Trained the model on the training set.
Model Evaluation:
Achieved an accuracy of 97.4% on the test set.
Visualized the confusion matrix to analyze the classification performance.
Results Visualization:
Plotted the decision boundaries to show how the model separates the classes.
## Comparison of Results:
The performance of all three algorithms was compared based on their accuracy and confusion matrices.
Observations were made about which algorithm performed best and why.
