# Breast Cancer Detection using Logistic Regression

This project implements a **Logistic Regression** model to detect whether a tumor is **benign** or **malignant** based on features extracted from a breast cancer dataset. It walks through the entire machine learning pipeline including data cleaning, exploration, model training, and evaluation using Python and Scikit-learn.

---

## Dataset

The dataset used is based on the [Breast Cancer Wisconsin (Original) Data Set](https://archive.ics.uci.edu/dataset/15/breast+cancer+wisconsin+original), which contains:
- **Target labels**:  
  - `2` → Benign  
  - `4` → Malignant

---

## Features in the Pipeline

### Data Preparation
- Removed duplicates
- Checked for missing values
- Separated features and labels

### Exploratory Data Analysis (EDA)
- Dataset shape and summary
- Class distribution
- Basic statistics with `.describe()`

### Model Training
- Logistic Regression with `scikit-learn`
- 80/20 train-test split
- Model fitting on training data

### Evaluation
- Confusion Matrix
- Accuracy Score

---

## Technologies Used

| Tool            | Purpose                          |
|-----------------|----------------------------------|
| Python          | Main programming language        |
| Pandas          | Data manipulation and analysis   |
| NumPy           | Numerical operations             |
| Scikit-learn    | ML model training and evaluation |
| Jupyter Notebook| Interactive analysis environment |

---


