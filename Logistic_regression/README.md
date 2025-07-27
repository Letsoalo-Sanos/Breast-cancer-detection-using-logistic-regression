##  Model Training and Evaluation

This section outlines the full process for training and evaluating a logistic regression model using the cleaned breast cancer dataset.

---

###  Train-Test Split

We begin by dividing the dataset into training and testing sets using an 80/20 split:

```python
from sklearn.model_selection import train_test_split

X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.2, random_state=42)
```

###  Model Evaluation
- **Confusion Matrix**: Visual assessment of TP, FP, TN, FN
- **Accuracy Score**: Measures classification success rate

##  Technologies Used

| Tool             | Purpose                                   |
|------------------|-------------------------------------------|
| Python         | Programming language                      |
| Pandas         | Data loading, cleaning, and manipulation  |
| NumPy          | Numerical operations                      |
| Scikit-learn   | Model training and evaluation             |
| Jupyter Notebook | Interactive development environment     |

##  Key Takeaways

- Simple yet powerful classification technique
- Clean and interpretable ML pipeline
- Excellent baseline model for binary classification in healthcare