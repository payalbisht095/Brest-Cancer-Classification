# 🩺 Breast Cancer Classification Using Machine Learning

## Project Overview

This project uses machine learning to classify breast tumors as **Benign (non-cancerous)** or **Malignant (cancerous)** using the Breast Cancer Wisconsin (Diagnostic) dataset. Two classification algorithms, Logistic Regression and Random Forest, are trained and evaluated to compare their performance.

## Objectives

* Understand and preprocess the dataset.
* Perform Exploratory Data Analysis (EDA).
* Train machine learning classification models.
* Evaluate and compare model performance.
* Visualize important patterns and results.

## Dataset

The project uses the Breast Cancer Wisconsin (Diagnostic) dataset obtained from Kaggle.

* **Target column:** `diagnosis`
* **B:** Benign
* **M:** Malignant
* **Features:** Numerical measurements of cell nuclei, including radius, texture, perimeter, area, smoothness, and other characteristics.

The `id` and `Unnamed: 32` columns are removed during preprocessing because they are not useful for prediction.

## Technologies Used

* Python
* Pandas and NumPy
* Matplotlib and Seaborn
* Scikit-learn
* Google Colab

## Project Workflow

1. Load the dataset.
2. Clean the data and handle missing values and duplicates.
3. Perform exploratory data analysis using visualizations.
4. Separate features (`X`) and target (`y`).
5. Split the data into training and testing sets.
6. Scale features for Logistic Regression.
7. Train Logistic Regression and Random Forest models.
8. Evaluate models using accuracy, precision, recall, F1-score, and confusion matrices.
9. Compare model performance and analyze feature importance.

## Project Screenshots

Screenshots of data analysis, visualizations, confusion matrices, and model results are stored in the `screenshots` folder.

To display a screenshot in this README, use:

```markdown
![Model Results](screenshots/model_output.png)
```

Replace `model_output.png` with your actual screenshot filename.

## Results

The models are compared using multiple evaluation metrics to identify the better-performing classifier. The actual results depend on the model outputs obtained during execution.
