# 🌸 Iris Flower Classification

## 📌 Project Overview

This project is part of the **Oasis Infobyte Data Science Internship**.

The objective is to build machine learning classification models that can predict the species of an iris flower based on its physical measurements.

The project covers the complete machine learning workflow, including data exploration, preprocessing, model training, evaluation, and model comparison.

---

## 🎯 Objective

Predict one of the following iris flower species:

- Setosa
- Versicolor
- Virginica

using the flower's measurements.

---

## 📊 Dataset

The Iris dataset is loaded directly from **Scikit-learn**.

- 150 samples
- 4 numerical features
- 3 flower species
- No missing values

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target:

- Species

---

## 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset overview
- Missing value check
- Descriptive statistics
- Pairplot
- Box plots
- Correlation Heatmap
- Feature Importance Analysis

---

## ⚙️ Data Preprocessing

- Train/Test Split (80/20)
- Stratified sampling
- Feature Scaling using StandardScaler (for Logistic Regression and KNN)

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest

---

## 📈 Evaluation Metrics

Each model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 🏆 Results

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **93.33%** |
| K-Nearest Neighbors | **93.33%** |
| Decision Tree | **93.33%** |
| Random Forest | **90.00%** |

Logistic Regression achieved the best overall performance due to its balanced evaluation metrics and simple, interpretable model.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook (Google Colab)

---

## 📂 Project Structure

```
DataScience-Task1-IrisFlowerClassification/
│
├── Iris_Flower_Classification.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

## 🚀 How to Run

1. Clone the repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```
Iris_Flower_Classification.ipynb
```

4. Run all cells.

---

## 📌 Key Learning Outcomes

- Exploratory Data Analysis (EDA)
- Feature Selection
- Feature Scaling
- Classification Algorithms
- Model Evaluation
- Model Comparison
- Writing clean and reusable code

---

## 👤 Author

**Sara Khaled Amin Abdelmonem**

Faculty of Computers and Artificial Intelligence  
Cairo University

Data Science Graduate
