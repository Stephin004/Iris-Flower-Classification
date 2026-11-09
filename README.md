# Iris Flower Classification

A machine learning classification project using the Iris dataset and three algorithms: Logistic Regression, K-Nearest Neighbors (KNN), and Decision Tree.

## Project Overview

This project explores the Iris dataset, prepares the features, trains classification models, and compares their performance.

## Algorithms Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier

## Project Workflow

1. Import Python libraries
2. Load and explore the Iris dataset
3. Prepare input features and target labels
4. Split data into training and testing sets
5. Train the three classification models
6. Evaluate models using accuracy and classification reports
7. Plot confusion matrices
8. Compare cross-validation scores
9. Compare Decision Tree depths
10. Visualize the Decision Tree
11. Test predictions on a new flower sample
12. Demonstrate Gini impurity

## Dataset

The notebook loads the Iris dataset directly from `scikit-learn`. You do not need to download or upload a separate `Iris.csv` file.

The dataset contains four measurements:
- Sepal length
- Sepal width
- Petal length
- Petal width

The target is the flower species.

## Technologies

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

## How to Run

### Google Colab
1. Upload `Iris_Flower_Classification.ipynb` to Google Colab.
2. Run the notebook cells from top to bottom.

### Local machine
1. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
2. Open the notebook in Jupyter:
   ```bash
   jupyter notebook
   ```

## Repository Structure

```text
Iris-Flower-Classification/
├── Iris_Flower_Classification.ipynb
├── README.md
└── requirements.txt
```

## Results

The notebook displays test accuracy, precision, recall, F1-score, confusion matrices, and cross-validation results for each model. Run the notebook to generate the exact results for the current environment.

## Author

Stephin Mathew
