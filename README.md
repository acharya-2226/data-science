# 📊 Data Science Lab Work

A collection of **Data Science** lab notebooks covering Python and statistics foundations, data visualization, data wrangling and EDA, hypothesis testing, feature engineering, regression, and clustering. Each lab has a guided manual notebook and a lab-task notebook with solved practice questions.

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Labs](https://img.shields.io/badge/Labs-9-blue)

---

## 📑 Table of Contents

- [Lab Index](#-lab-index)
- [Datasets](#-datasets)
- [Tools and Libraries](#-tools-and-libraries)
- [Repository Structure](#-repository-structure)
- [Getting Started](#-getting-started)
- [Author](#-author)

---

## 🧪 Lab Index

| Lab | Topic | What it covers |
|-----|-------|----------------|
| [Lab 1](Lab_1/) | Python Basics | Data types, variables, and basic operations |
| [Lab 2](Lab_2/) | Data Science Tools and Statistics | NumPy, Pandas, Matplotlib and Seaborn; descriptive and inferential statistics |
| [Lab 3](Lab_3/) | Data Visualization and Optimization | Line, bar, heatmap, box and scatter plots; matrix factorization and gradient descent |
| [Lab 4](Lab_4/) | Data Wrangling, ETL and EDA | Cleaning, transforming, and exploring the Titanic and Wine Quality datasets |
| [Lab 5](Lab_5/) | Hypothesis Testing | One-sample, two-sample, and paired t-tests, and testing claims with hypotheses, test statistics and decision rules |
| [Lab 6](Lab_6/) | Feature Extraction and Selection | One-hot, label, target, frequency and binary encoding; min-max scaling; removing correlated features; creating new features |
| [Lab 7](Lab_7/) | Linear Regression | Simple and multiple regression, visualizing fits, and residual analysis |
| [Lab 8 & 9](Lab_8%269/) | Logistic Regression and K-Means | Classification metrics (accuracy, precision, recall, confusion matrix, ROC/AUC); clustering with the elbow method and silhouette score |

Most labs include:

- **Manual** notebook: theory, worked examples, and practice questions
- **Lab-task** notebook: solutions to the assigned tasks
- `.html` and `.pdf` exports for viewing without Jupyter

---

## 🗂️ Datasets

| File | Location | Used for |
|------|----------|----------|
| `students.csv` | `Lab_2/` | Basic Pandas and statistics practice |
| `titanic.csv` | `Lab_4/`, `Lab_8&9/` | Data wrangling, EDA, and clustering (891 passengers) |
| `processed_titanic.csv` | `Lab_4/` | Output of the ETL step |
| `winequality-red.csv` | `Lab_4/` | Data exploration practice (1,599 samples, semicolon-separated) |
| `mall_customers.csv` | `Lab_8&9/` | K-Means customer segmentation (200 customers) |
| `Womens_Clothing_Reviews.csv` | repository root | Additional practice dataset (ratings, recommendations, departments) |

---

## 🧰 Tools and Libraries

| Library | Purpose |
|---------|---------|
| **NumPy** | Numerical arrays and operations |
| **Pandas** | Data loading, cleaning, and manipulation |
| **Matplotlib** and **Seaborn** | Visualization |
| **SciPy** | Statistical tests |
| **scikit-learn** | Preprocessing, regression, classification, PCA, and clustering |
| **Jupyter** | Interactive notebooks |

---

## 📁 Repository Structure

```text
data-science/
├── Lab_1/            # Python basics
├── Lab_2/            # NumPy, Pandas, visualization, statistics
│   └── students.csv
├── Lab_3/            # Visualization, matrix factorization, gradient descent
├── Lab_4/            # Wrangling, ETL, EDA
│   ├── titanic.csv
│   ├── processed_titanic.csv
│   ├── winequality-red.csv
│   └── Figure_1.png
├── Lab_5/            # Hypothesis testing
├── Lab_6/            # Feature extraction and selection
├── Lab_7/            # Linear regression
├── Lab_8&9/          # Logistic regression and K-Means
│   ├── titanic.csv
│   └── mall_customers.csv
├── Womens_Clothing_Reviews.csv
└── README.md
```

---

## 🚀 Getting Started

```bash
git clone https://github.com/acharya-2226/data-science.git
cd data-science

pip install numpy pandas matplotlib seaborn scipy scikit-learn notebook
jupyter notebook
```

Open the notebook you want from its lab folder. Launch it from inside that folder so the relative CSV paths resolve.

---

## 👤 Author

**Siddharth Acharya**
B.E. Computer Engineering, Himalaya College of Engineering (HCOE), Tribhuvan University
GitHub: [@acharya-2226](https://github.com/acharya-2226)
