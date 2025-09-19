# Iris Flower Classification with SVM

This project demonstrates the classification of the Iris dataset using a Support Vector Machine (SVM) algorithm. The goal is to build a model that can accurately predict the species of an Iris flower based on its sepal and petal measurements.

## Dataset

The **Iris dataset** is a classic dataset in machine learning, containing 150 samples of Iris flowers from three different species:
- Iris setosa
- Iris versicolor
- Iris virginica

For each flower, four features were measured:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

## Analysis and Results

The analysis notebook explores the data through visualizations like pairplots and scatter plots to understand the separability of the classes. An SVM model is then trained and evaluated. The results demonstrate that the model can achieve a perfect classification score on the test set due to the clear linear separability of the classes, particularly when using petal dimensions.

## Key Steps

- **Data Loading and Preprocessing:** The Iris dataset is loaded and prepared for machine learning.
- **Data Visualization:** Plots are generated to visualize the relationships between features and classes.
- **Model Training:** An SVM model is trained on the preprocessed data.
- **Evaluation:** The model's performance is evaluated using accuracy, a classification report, and a confusion matrix.

## Perfect Classification

The model's perfect score on the test data is attributed to the dataset's characteristics, specifically the distinct linear separability of the Iris species based on their features. The perfect classification is not a sign of overfitting in this context, but rather a reflection of the data's structure.

## How to Run

1. Clone this repository.
2. Ensure you have the necessary libraries installed (`pandas`, `scikit-learn`, `matplotlib`, `seaborn`).
3. Run the Jupyter notebook to replicate the analysis.
