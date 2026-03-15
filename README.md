<<<<<<< HEAD

# Iris Flower Classification using KNN

This project builds a machine learning model to classify iris flowers using the K-Nearest Neighbors (KNN) algorithm.

## Dataset
The Iris dataset contains 150 flower samples with 4 features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target classes:
- Setosa
- Versicolor
- Virginica

Place the dataset file **iris.csv** inside the `data` folder.

## Project Structure

iris_knn_project
│
├── data
│   └── iris.csv
│
├── model
│   └── knn_iris_model.sav
│
├── notebooks
│   ├── train_knn_model.ipynb
│   └── example_prediction.ipynb
│
└── requirements.txt

## Workflow

1. Load dataset
2. Split into training and testing sets
3. Train KNN model
4. Evaluate model accuracy
5. Save trained model
6. Load model and make predictions

## Libraries Used

- pandas
- numpy
- scikit-learn
- joblib

## Example Prediction

Input:
[6.8, 3.0, 1.7, 0.5]

Output: Setosa

## Author
Kavindu Dulanjana
=======
# iris-knn-classifier
KNN Machine Learning model to classify Iris flowers
>>>>>>> ad03c1d80d5c8122b5ac0eec99d82f916396fbcf
