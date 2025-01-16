## Iris_dataset_classification
## Project Description
This project involves building a classification model to predict the species of a flower based on its features, such as the length and width of sepals and petals. The well-known Iris Dataset was used, which is a classic dataset in machine learning.

## Dataset
Name: Iris Dataset
Source: Built-in dataset from the scikit-learn library.
Description:
Number of samples: 150
Number of features: 4 (sepal length, sepal width, petal length, petal width)
Number of classes: 3 (setosa, versicolor, virginica)
Goal: Predict the species of a flower based on its features.

## Project Goals
The main goals of this project are:

To understand the basic steps in machine learning, such as data exploration, preprocessing, model building, and evaluation.
To build a classification model using the Logistic Regression algorithm.
To visualize the results and analyze the model's performance.
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
Split the data into training and testing sets (75%/25%).
Standardized the features using StandardScaler.
Model Building:
Used the Logistic Regression algorithm.
Trained the model on the training set.
Model Evaluation:
Achieved an accuracy of 94.7% on the test set.
Visualized the confusion matrix to analyze the classification performance.
Results Visualization:
Plotted the decision boundaries to show how the model separates the classes.
## Results
The model achieved an accuracy of 94.7% on the test set.
The confusion matrix shows that the model performs well in classifying all three flower species.
The decision boundary visualization confirms that the model effectively separates the classes.
