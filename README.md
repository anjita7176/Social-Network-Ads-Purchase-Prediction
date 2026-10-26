<div align="center">

# 📊 Social Network Ads — Purchase Prediction

### Machine Learning | Logistic Regression | Python

*A classification project exploring how age and estimated salary relate to purchase decisions.*

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square\&logo=pandas\&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square\&logo=scikitlearn\&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square\&logo=jupyter\&logoColor=white)

</div>

---

## 🎯 Project Overview

This project builds a **Logistic Regression classification model** to predict whether a user purchases a product using two input features:

* **Age**
* **Estimated Salary**

The project demonstrates a complete introductory machine learning workflow, from data exploration and visualization to model training and evaluation.

## 🎯 Objectives

* Explore relationships between customer attributes and purchase outcomes.
* Understand and prepare a dataset for machine learning.
* Apply feature scaling to numerical features.
* Train a Logistic Regression classifier.
* Evaluate model predictions using classification metrics.

## 📁 Dataset

The dataset contains **400 records** and the following columns:

| Feature          | Description                 |
| ---------------- | --------------------------- |
| User ID          | Customer identifier         |
| Gender           | Customer gender             |
| Age              | Customer age                |
| Estimated Salary | Customer's estimated salary |
| Purchased        | Purchase outcome (target)   |

**Model inputs:** Age and Estimated Salary
**Target variable:** Purchased

The identifier and gender columns are excluded from model training.

Dataset location: `data/Social_Network_Ads.csv`

## ⚙️ Machine Learning Workflow

1. Load the dataset using Pandas.
2. Inspect the data and explore its structure.
3. Visualize relationships between features and purchase outcomes.
4. Separate input features and the target variable.
5. Split the data into training and testing sets using stratification.
6. Standardize numerical features using `StandardScaler`.
7. Train a Logistic Regression classifier.
8. Evaluate predictions on the test set.

## 🧠 Model Details

| Component        | Configuration                               |
| ---------------- | ------------------------------------------- |
| Algorithm        | Logistic Regression                         |
| Input features   | Age, Estimated Salary                       |
| Target           | Purchased                                   |
| Train/test split | 70% / 30%                                   |
| Random state     | 42                                          |
| Feature scaling  | StandardScaler                              |
| Evaluation       | Classification metrics and confusion matrix |

The preprocessing and classification steps are combined into a scikit-learn pipeline to keep the workflow consistent and help prevent data leakage.

## 📈 Model Evaluation

The notebook calculates:

* **Accuracy:** Overall proportion of correct predictions.
* **Precision:** Proportion of positive predictions that are correct.
* **Recall:** Proportion of actual positive cases identified.
* **F1-score:** Harmonic mean of precision and recall.
* **Confusion Matrix:** Breakdown of correct and incorrect classifications.

The actual metric values can be obtained by running the notebook. Results should be interpreted in the context of this small educational dataset and do not establish real-world purchasing behavior.

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/anjita7176/Social-Network-Ads-Purchase-Prediction.git
```

### 2. Open the project directory

```bash
cd Social-Network-Ads-Purchase-Prediction
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `social_network_ads_logistic_regression.ipynb` and run the cells in order.

## 🔮 Future Improvements

* Compare Logistic Regression with other classification algorithms.
* Evaluate the model using cross-validation.
* Explore additional classification metrics.
* Improve visualizations and error analysis.
* Experiment with model parameters and feature selection.

## 👩‍💻 Author

**Anjita Kumari**

Aspiring Data Scientist | Machine Learning | Generative AI

* GitHub: [@anjita7176](https://github.com/anjita7176)
* LinkedIn: [Connect with me](https://www.linkedin.com/in/anjita-kumari-48975624b/)

---

<div align="center">

*Learning by building. Improving through data.*

</div>
